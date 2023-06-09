# Use the official JMeter base image
FROM justb4/jmeter:latest

# Copy the JMeter script to the container
COPY test.jmx /jmeter/test.jmx

# Run the JMeter script and generate the HTML report
ENTRYPOINT ["jmeter", "-n", "-t", "/jmeter/test.jmx", "-l", "/jmeter/results.jtl", "-e", "-o", "/jmeter/report"]




#Commands need to be given in terminal
#
#
#sudo docker build -t jmeter-docker4 .
#
#
#sudo docker run --rm -v ~/Downloads/Projects/Docker\ YouTube\ Github/JMeter/3rd/api/results:/jmeter/results -v ~/Downloads/Projects/Docker\ YouTube\ Github/JMeter/3rd/api/report:/jmeter/report jmeter-docker4
#














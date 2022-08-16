# Customer-complaints-analysis
NYC 311's mission is to provide the public with quick and easy access to all New York City government services and information while offering the best customer service. Each day, NYC311 receives thousands of requests related to several hundred types of non-emergency services, including noise complaints, plumbing issues, and illegally parked cars. These requests are received by NYC311 and forwarded to the relevant agencies such as the police, buildings, or transportation. The agency responds to the request, addresses it, and then closes it.
Analysis Tasks performed:
  1) Imported a 311 NYC service request.
  2) Convert the columns ‘Created Date’ and Closed Date’ to datetime datatype and created a new column ‘Request_Closing_Time’ as the time elapsed between request creation and request closing.
4 major conclusions.
Ordered the complaint types based on the average ‘Request_Closing_Time’, grouping them for different locations.
Performed a statistical test for the following:
  1) Whether the average response time across complaint types is similar or not (overall)
  2) Are the type of complaint or service requested and location related?

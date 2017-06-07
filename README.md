# Alexa Bus Tracker
Alexa bus tracker for the Seattle and San Francisco bus systems. Available to install on [this page](https://www.amazon.com/Daniel-Jamrozik-Champaign-Urbana-Times/dp/B06XDWHPT6/ref=sr_1_1?s=digital-skills&ie=UTF8&qid=1489084208&sr=1-1&keywords=cumtd).

The single .js file is meant to be ran as a lambda function on AWS. It also uses a DynamoDB key store to save default bus stops. The Lambda function will make API calls to CUMTD when triggered. OneBusAway/NextBus Integration pending.

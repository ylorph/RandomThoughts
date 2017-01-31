* Let's Fail -- not all of us are doing 10^12 msg/Sec
* who am I

* Intro
 Not only a technical talk But want to show the impact of what we build on the business
* Integrating with external third parties
* getting information
* Security

* Are all messages equal ?
* Are all messages of the same type equal ?
* Soa, µSvc, integration all needs messaging of some sort,
but since it's considered obvious (Cynefin) & supporting context (DDD),we can easily fall into Chaos (Cynefin)



* Explain Original title => Messaging for the Middleman

* Questions to audience
  * How many messages are you really doing per day?
  * Do we all do 10^12 messages day?
  * Can you do the quick math for the number of messages/hits you handle ?


* make clear: using messaging as an excuse to tell the stories
* make clear: the stories have a point

* Stories
  * Leasing & latency
  * Logistics & Denial & Priorities are not the same when in chaos
  * Leasing & the cost & caching
  * HR: the switching switch & got queueing & snowballs ...  
  * HR: 5 days Downtime! What is the business priority ?
  * Other client: can you define your problem in term of business?

* in the end: feedback loop.
* in the end: pattern language of failures ?
* in the end: because we need to document this.


* Mention Talks
  * Greg Young: "Stop Over-Engineering"  
  * Greg Young: "Production issues", "Production Lessons"
  * Ali Kheyrollahi: "5 must-have patterns for your web-scale Microservices."  
  * Ali Kheyrollahi: "From hard science to baseless opinions: where did we go wrong?"  


* Mention Books
  * Matthew Syed: Black Box Thinking
  * Jim Manzi: Uncontrolled
  * Michael T. Nygard: Release It!


* Leasing
* Business Case : about latency as business needs it
* Business case: the cost of messaging
* the cost of messaging
* the case of the data provider cost that went up
* latency & stale data (Eventual Consistency ?)


* logistics
* Business case
* the case of the 3d party that wen mad which client is more important, is it the one with the highest priced message ?


* legacy
* Business Cases
* replacing part of legacy
* new features (no, problems solved) integrating with legacy *


* Other
* Business Cases : HR - Computer based tests
* Security as an afterthought
* it's about the API/protocol and the business problem it solves
* Failures
* from the network in between (NserviceBus)
* from message handlers (NserviceBus).

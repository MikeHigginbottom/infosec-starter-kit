# SIEM Tool Comparison
- For learning, start with [Splunk](splunk.md) and then progress to [SecurityOnion](security-onion.md)
- Best bet for powerful free system is [SecurityOnion](security-onion.md)
- [Splunk](splunk.md) is another alternative but free version has a 500MB/day limit. Can be extended to 50GB with a developer licence.
- The main difference between [Splunk](splunk.md) and the [Elastic Stack](elastic-stack.md) are splunk can handle a lot more data and comes with lots of searches, data displays, data importors and exportors and data storage schemas. It is also ready to go right out of the box.
- The Elastic stack you are given a blank system and you have setup all those displays, the data schemas, etc by yourself. So there is lots of up front setup. They are getting better but expect to spend lots of time.
- Security Onion does a lot of that setup and is ready to setup to take network traffic right from the start. It is weak on handling logs.
- Jask.com is an upcoming SEIM with AI in mind
- ArcSight ESM does real time correlation.
- ArcSight Event Broker uses Apache Kafka and Zookeeper as a distributed messaging system and allows third-party vendors who can collect from Apache Kafka to consumer security events.
- ArcSight Investigate with Vertica DB is for big data and log searching but is still new.
- Splunk doesn't do real time correlation and it's just a better choice over ArcSight Logger.
- ELK is a Dashboard integration from data in ArcSight and Splunk and others.
- Security Onion is home grown for professionals that don't need support and know how to tune and collect logs.
## My Notes
[Notes](mynotes/siem-tool-comparison-notes.md)

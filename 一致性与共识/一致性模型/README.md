# 一致性模型

分布式系统常常通过数据的复制来提高系统的可靠性和容错性，并且将数据的副本存放到不同的机器上，由于多个副本的存在，使得维护副本一致性的代价很高。因此，许多分布式系统都采用弱一致性或者是最终一致性，来提高系统的性能和吞吐能力，这样不同的一致性模型也相继被提出。

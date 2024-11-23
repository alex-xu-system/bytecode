Reference Materials for System Design Interview - An Insider's Guide (Volume 1) book (https://amzn.to/3ggPKAG)

## Chapter 1: Scale From Zero To Millions Of Users

[[1] Hypertext Transfer Protocol](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)  
[[2] Should you go Beyond Relational Databases?](https://blog.teamtreehouse.com/should-you-go-beyond-relational-databases)  
[[3] Replication](<https://en.wikipedia.org/wiki/Replication_(computing)>)  
[[4] Multi-master replication](https://en.wikipedia.org/wiki/Multi-master_replication)  
[[5] NDB Cluster Replication - Multi-Master and Circular Replication](https://dev.mysql.com/doc/refman/5.7/en/mysql-cluster-replication-multi-source.html)  
[[6] Caching Strategies and How to Choose the Right One](https://codeahoy.com/2017/08/11/caching-strategies-and-how-to-choose-the-right-one/)  
[[7] Scaling Memcache at Facebook](https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final170_update.pdf)  
[[8] Single point of failure](https://en.wikipedia.org/wiki/Single_point_of_failure)  
[[9] Amazon CloudFront Dynamic Content Delivery](https://aws.amazon.com/cloudfront/dynamic-content/)  
[[10] Configure Sticky Sessions for Your Classic Load Balancer](https://docs.aws.amazon.com/elasticloadbalancing/latest/classic/elb-sticky-sessions.html)  
[[11] Active-Active for Multi-Regional Resiliency](https://netflixtechblog.com/active-active-for-multi-regional-resiliency-c47719f6685b)  
[[12] Amazon EC2 High Memory Instances](https://aws.amazon.com/ec2/instance-types/high-memory/)  
[[13] What it takes to run Stack Overflow](http://nickcraver.com/blog/2013/11/22/what-it-takes-to-run-stack-overflow)  
[[14] What The Heck Are You Actually Using NoSQL For](http://highscalability.com/blog/2010/12/6/what-the-heck-are-you-actually-using-nosql-for.html)

## Chapter 2: Back-of-the-envelope Estimation

[[1] J. Dean.Google Pro Tip - Use Back-Of-The-Envelope-Calculations To Choose The Best Design](http://highscalability.com/blog/2011/1/26/google-pro-tip-use-back-of-the-envelope-calculations-to-choo.html)  
[[2] System design primer](https://github.com/donnemartin/system-design-primer)  
[[3] Latency Numbers Every Programmer Should Know](https://colin-scott.github.io/personal_website/research/interactive_latency.html)  
[[4] Amazon Compute Service Level Agreement](https://aws.amazon.com/compute/sla/)  
[[5] Compute Engine Service Level Agreement (SLA)](https://cloud.google.com/compute/sla)  
[[6] SLA summary for Azure services](https://azure.microsoft.com/en-us/support/legal/sla/summary/)

## Chapter 4: Design A Rate Limiter:

[[1] Rate-limiting strategies and techniques](https://cloud.google.com/solutions/rate-limiting-strategies-techniques)  
[[2] Twitter rate limits](https://developer.twitter.com/en/docs/basics/rate-limits)  
[[3] Google docs usage limits](https://developers.google.com/docs/api/limits)  
[[4] IBM microservices](https://www.ibm.com/cloud/learn/microservices)  
[[5] Throttle API requests for better throughput](https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-request-throttling.html)  
[[6] Stripe rate limiters](https://stripe.com/blog/rate-limiters)  
[[7] Shopify REST Admin API rate limits](https://help.shopify.com/en/api/reference/rest-admin-api-rate-limits)  
[[8] Better Rate Limiting With Redis Sorted Sets](https://engineering.classdojo.com/blog/2015/02/06/rolling-rate-limiter/)  
[[9] System Design - Rate limiter and Data modelling](https://medium.com/@saisandeepmopuri/system-design-rate-limiter-and-data-modelling-9304b0d18250)  
[[10] How we built rate limiting capable of scaling to millions of domains](https://blog.cloudflare.com/counting-things-a-lot-of-different-things/)  
[[11] Redis website](https://redis.io/)  
[[12] Lyft rate limiting](https://github.com/lyft/ratelimit)  
[[13] Scaling your API with rate limiters](https://gist.github.com/ptarjan/e38f45f2dfe601419ca3af937fff574d#request-rate-limiter)  
[[14] What is edge computing](https://www.cloudflare.com/learning/serverless/glossary/what-is-edge-computing/)  
[[15] Rate Limit Requests with Iptables](https://blog.programster.org/rate-limit-requests-with-iptables)  
[[16] OSI model](https://en.wikipedia.org/wiki/OSI_model#Layer_architecture)

## Chapter 5: Design Consistent Hashing

[[1] Consistent hashing wiki](https://en.wikipedia.org/wiki/Consistent_hashing)  
[[2] Consistent Hashing](https://tom-e-white.com/2007/11/consistent-hashing.html)  
[[3] Dynamo - Amazon's Highly Available Key-value Store](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)  
[[4] Cassandra - A Decentralized Structured Storage System](http://www.cs.cornell.edu/Projects/ladis2009/papers/Lakshman-ladis2009.PDF)  
[[5] How Discord Scaled Elixir to 5,000,000 Concurrent Users](https://discord.com/blog/how-discord-scaled-elixir-to-5-000-000-concurrent-users)  
[[6] CS168 - The Modern Algorithmic Toolbox Lecture #1: Introduction and Consistent Hashing](http://theory.stanford.edu/~tim/s16/l/l1.pdf)  
[[7] Maglev - A Fast and Reliable Software Network Load Balancer](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44824.pdf)

## Chapter 6: Design A Key-value Store

[[1] Amazon DynamoDB](https://aws.amazon.com/dynamodb/)  
[[2] memcached](https://memcached.org/)  
[[3] Redis](https://redis.io/)  
[[4] Dynamo: Amazon's Highly Available Key-value Store](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)  
[[5] Cassandra](https://cassandra.apache.org/)  
[[6] Bigtable: A Distributed Storage System for Structured Data](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)  
[[7] Merkle tree](https://en.wikipedia.org/wiki/Merkle_tree)  
[[8] Cassandra architecture](https://cassandra.apache.org/doc/latest/architecture/)  
[[9] SStable](https://www.igvita.com/2012/02/06/sstable-and-log-structured-storage-leveldb/)  
[[10] Bloom filter](https://en.wikipedia.org/wiki/Bloom_filter)

## Chapter 7: Design A Unique Id Generator In Distributed Systems

[[1] Universally unique identifier](https://en.wikipedia.org/wiki/Universally_unique_identifier)  
[[2] Ticket Servers - Distributed Unique Primary Keys on the Cheap](https://code.flickr.net/2010/02/08/ticket-servers-distributed-unique-primary-keys-on-the-cheap/)  
[[3] Announcing Snowflake](https://blog.twitter.com/engineering/en_us/a/2010/announcing-snowflake.html)  
[[4] Network time protocol](https://en.wikipedia.org/wiki/Network_Time_Protocol)

## Chapter 8: Design A Url Shortener

[[1] A RESTful Tutorial](https://www.restapitutorial.com/index.html)  
[[2] Bloom filter](https://en.wikipedia.org/wiki/Bloom_filter)

## Chapter 9: Design A Web Crawler

[[1] US Library of Congress](https://www.loc.gov/websites/)  
[[2] EU Web Archive](http://data.europa.eu/webarchive)  
[[3] Digimarc](https://www.digimarc.com/products/digimarc-services/piracy-intelligence)  
[[4] Mercator: A scalable, extensible web crawler](https://courses.cs.washington.edu/courses/cse454/15wi/papers/mercator.pdf)  
[[5] Web Crawling](http://infolab.stanford.edu/~olston/publications/crawling_survey.pdf)  
[[6] 29% Of Sites Face Duplicate Content Issues](https://tinyurl.com/y6tmh55y)  
[7] Rabin M.O., et al. Fingerprinting by random polynomials Center for Research in Computing Techn., Aiken Computation Laboratory, Univ. (1981)  
[8] B. H. Bloom, Space/time trade-offs in hash coding with allowable errors, Communications of the ACM, vol. 13, no. 7, pp. 422-426, 1970.  
[[9] Donald J. Patterson, Web Crawling](https://www.ics.uci.edu/~lopes/teaching/cs221W12/slides/Lecture05.pdf)  
[10] L. Page, S. Brin, R. Motwani, and T. Winograd, The PageRank citation ranking: Bringing order to the web, Technical Report, Stanford University, 1998.  
[11] Burton Bloom. Space/time trade-offs in hash coding with allowable errors. Communications of the ACM, 13(7), pages 422--426, July 1970.  
[[12] Google Dynamic Rendering](https://developers.google.com/search/docs/guides/dynamic-rendering)  
[13] T. Urvoy, T. Lavergne, and P. Filoche, Tracking web spam with hidden style similarity, in Proceedings of the 2nd International Workshop on Adversarial Information Retrieval on the Web, 2006.  
[[14] IRLbot: Scaling to 6 billion pages and beyond](http://irl.cs.tamu.edu/people/hsin-tsang/papers/tweb2009.pdf)

## Chapter 10: Design A Notification System

[[1] Twilio SMS](https://www.twilio.com/sms)  
[[2] Nexmo SMS](https://www.nexmo.com/products/sms)  
[[3] Sendgrid](https://sendgrid.com/)  
[[4] Mailchimp](https://mailchimp.com/)  
[[5] You Cannot Have Exactly-Once Delivery](https://bravenewgeek.com/you-cannot-have-exactly-once-delivery/)  
[[6] App Keys & Secrets: Security](https://bit.ly/36txfnV)  
[[7] RadditMQ](https://bit.ly/2sotIa6)

## Chapter 11: Design A News Feed System

[[1] How News Feed Works](https://www.facebook.com/help/327131014036297/)  
[[2] Friend of Friend recommendations Neo4j and SQL Sever](https://bit.ly/3rcNPlO)

## Chapter 12: Design A Chat System

[[1] Erlang at Facebook](https://www.erlang-factory.com/upload/presentations/31/EugeneLetuchy-ErlangatFacebook.pdf)  
[[2] Messenger and WhatsApp process 60 billion messages a day](https://www.theverge.com/2016/4/12/11415198/facebook-messenger-whatsapp-number-messages-vs-sms-f8-2016)  
[[3] Long tail](https://en.wikipedia.org/wiki/Long_tail)  
[[4] The Underlying Technology of Messages](https://www.facebook.com/notes/facebook-engineering/the-underlying-technology-of-messages/454991608919/)  
[[5] How Discord Stores Billions of Messages](https://blog.discordapp.com/how-discord-stores-billions-of-messages-7fa6ec7ee4c7)  
[[6] Announcing Snowflake](https://blog.twitter.com/engineering/en_us/a/2010/announcing-snowflake.html)  
[[7] Apache ZooKeeper](https://zookeeper.apache.org/)  
[[8] From nothing: the evolution of WeChat background system (Article in Chinese)](https://www.infoq.cn/article/the-road-of-the-growth-weixin-background)  
[[9] End-to-end encryption](https://faq.whatsapp.com/en/android/28030015/)  
[[10] Flannel: An Application-Level Edge Cache to Make Slack Scale](https://slack.engineering/flannel-an-application-level-edge-cache-to-make-slack-scale-b8a6400e2f6b)

## 13: Design A Search Autocomplete System

[[1] The Life of a Typeahead Query](https://www.facebook.com/notes/facebook-engineering/the-life-of-a-typeahead-query/389105248919/)  
[[2] How We Built Prefixy: A Scalable Prefix Search Service for Powering Autocomplete](https://medium.com/@prefixyteam/how-we-built-prefixy-a-scalable-prefix-search-service-for-powering-autocomplete-c20f98e2eff1)  
[[3] Prefix Hash Tree An Indexing Data Structure over Distributed Hash Tables](https://people.eecs.berkeley.edu/~sylvia/papers/pht.pdf)  
[[4] MongoDB wikipedia](https://en.wikipedia.org/wiki/MongoDB)  
[[5] Unicode frequently asked questions](https://www.unicode.org/faq/basic_q.html)  
[[6] Apache hadoop](https://hadoop.apache.org/)  
[[7] Spark streaming](https://spark.apache.org/streaming/)  
[[8] Apache storm](https://storm.apache.org/)  
[[9] Apache kafka](https://kafka.apache.org/documentation/)

## Chapter 14: Design Youtube

[[1] YouTube by the numbers](https://www.omnicoreagency.com/youtube-statistics/)  
[[2] 2019 YouTube Demographics](https://blog.hubspot.com/marketing/youtube-demographics)  
[[3] Cloudfront Pricing](https://aws.amazon.com/cloudfront/pricing/)  
[[4] Netflix on AWS](https://aws.amazon.com/solutions/case-studies/netflix/)  
[[5] Akamai homepage](https://www.akamai.com/)  
[[6] Binary large object](https://en.wikipedia.org/wiki/Binary_large_object)  
[[7] Here's What You Need to Know About Streaming Protocols](https://www.dacast.com/blog/streaming-protocols/)  
[[8] SVE: Distributed Video Processing at Facebook Scale](https://www.cs.princeton.edu/~wlloyd/papers/sve-sosp17.pdf)  
[[9] Weibo video processing architecture (in Chinese)](https://www.upyun.com/opentalk/399.html)  
[[10] Delegate access with a shared access signature](https://docs.microsoft.com/en-us/rest/api/storageservices/delegate-access-with-shared-access-signature)  
[[11] YouTube scalability talk by early YouTube employee](https://www.youtube.com/watch?v=w5WVu624fY8)  
[[12] Understanding the characteristics of internet short video sharing: A youtube-based measurement study](https://arxiv.org/pdf/0707.3670.pdf)  
[[13] Content Popularity for Open Connect](https://netflixtechblog.com/content-popularity-for-open-connect-b86d56f613b)

## Chapter 15: Design Google Drive

[[1] Google Drive](https://www.google.com/drive/)  
[[2] Upload file data](https://developers.google.com/drive/api/v2/manage-uploads)  
[[3] Amazon S3](https://aws.amazon.com/s3)  
[[4] Differential Synchronization](https://neil.fraser.name/writing/sync/)  
[[5] Differential Synchronization youtube talk](https://www.youtube.com/watch?v=S2Hp_1jqpY8)  
[[6] How We've Scaled Dropbox](https://youtu.be/PE4gwstWhmc)  
[[7] The rsync algorithm](https://www.andrew.cmu.edu/course/15-749/READINGS/required/cas/tridgell96.pdf)  
[[8] Librsync. (n.d.). Retrieved April 18, 2015, from](https://github.com/librsync/librsync)  
[[9] ACID](https://en.wikipedia.org/wiki/ACID)  
[[10] Dropbox security white paper](https://www.dropbox.com/static/business/resources/Security_Whitepaper.pdf)  
[[11] Amazon S3 Glacier](https://aws.amazon.com/glacier/faqs/)

### Real-world systems

The following materials can help you understand general design ideas of real system architectures behind different companies.  
[Facebook Timeline: Brought To You By The Power Of Denormalization](https://goo.gl/FCNrbm)  
[Scale at Facebook](https://www.infoq.com/presentations/Scale-at-Facebook/)  
[Building Timeline: Scaling up to hold your life story](https://goo.gl/8p5wDV)  
[Erlang at Facebook (Facebook chat)](https://goo.gl/zSLHrj)  
[Finding a needle in Haystack: Facebook's photo storage](https://goo.gl/edj4FL)  
[Serving Facebook Multifeed: Efficiency, performance gains through redesign](https://goo.gl/adFVMQ)  
[Scaling Memcache at Facebook](https://goo.gl/rZiAhX)  
[TAO: Facebook's Distributed Data Store for the Social Graph](https://goo.gl/Tk1DyH)  
[Amazon Architecture](https://goo.gl/k4feoW)  
[Dynamo: Amazon's Highly Available Key-value Store](https://goo.gl/C7zxDL)  
[A 360 Degree View Of The Entire Netflix Stack](https://goo.gl/rYSDTz)  
[It's All A/Bout Testing: The Netflix Experimentation Platform](https://goo.gl/agbA4K)  
[Netflix Recommendations: Beyond the 5 stars (Part 1)](https://goo.gl/A4FkYi)  
[Netflix Recommendations: Beyond the 5 stars (Part 2)](https://goo.gl/XNPMXm)  
[Google Architecture](https://goo.gl/dvkDiY)  
[The Google File System (Google Docs)](https://goo.gl/xj5n9R)  
[Differential Synchronization (Google Docs)](https://goo.gl/9zqG7x)  
[YouTube Architecture](https://goo.gl/mCPRUF)  
[Seattle Conference on Scalability: YouTube Scalability](https://goo.gl/dH3zYq)  
[Bigtable: A Distributed Storage System for Structured Data](https://goo.gl/6NaZca)  
[Instagram Architecture: 14 Million Users, Terabytes Of Photos, 100s Of Instances, Dozens Of Technologies](https://goo.gl/s1VcW5)  
[The Architecture Twitter Uses To Deal With 150M Active Users](https://goo.gl/EwvfRd)  
[Scaling Twitter: Making Twitter 10000 Percent Faster](https://goo.gl/nYGC1k)  
[Announcing Snowflake (Snowflake is a network service for generating unique ID numbers at high scale with some simple guarantees)](https://goo.gl/GzVWYm)  
[Timelines at Scale](https://goo.gl/8KbqTy)  
[How Uber Scales Their Real-Time Market Platform](https://goo.gl/kGZuVy)  
[Scaling Pinterest](https://goo.gl/KtmjW3)  
[Pinterest Architecture Update](https://goo.gl/w6rRsf)  
[A Brief History of Scaling LinkedIn](https://goo.gl/8A1Pi8)  
[Flickr Architecture](https://goo.gl/dWtgYa)  
[How We've Scaled Dropbox](https://goo.gl/NjBDtC)  
[The WhatsApp Architecture Facebook Bought For $19 Billion](https://bit.ly/2AHJnFn)

### Company engineering blogs

[Airbnb](https://medium.com/airbnb-engineering)  
[Amazon](https://developer.amazon.com/blogs)  
[Asana](https://blog.asana.com/category/eng)  
[Atlassian](https://developer.atlassian.com/blog)  
[Bittorrent](http://engineering.bittorrent.com)  
[Cloudera](https://blog.cloudera.com)  
[Docker](https://blog.docker.com)  
[Dropbox](https://blogs.dropbox.com/tech)  
[eBay](http://www.ebaytechblog.com)  
[Facebook](https://code.facebook.com/posts)  
[GitHub](https://githubengineering.com)  
[Google](https://developers.googleblog.com)  
[Groupon](https://engineering.groupon.com)  
[Highscalability](http://highscalability.com)  
[Instacart](https://tech.instacart.com)  
[Instagram](https://engineering.instagram.com)  
[Linkedin](https://engineering.linkedin.com/blog)  
[Mixpanel](https://mixpanel.com/blog)  
[Netflix](https://medium.com/netflix-techblog)  
[Nextdoor](https://engblog.nextdoor.com)  
[PayPal](https://www.paypal-engineering.com)  
[Pinterest](https://engineering.pinterest.com)  
[Quora](https://engineering.quora.com)  
[Reddit](https://redditblog.com)  
[Salesforce](https://developer.salesforce.com/blogs/engineering)  
[Shopify](https://engineering.shopify.com)  
[Slack](https://slack.engineering)  
[Soundcloud](https://developers.soundcloud.com/blog)  
[Spotify](https://labs.spotify.com)  
[Stripe](https://stripe.com/blog/engineering)  
[System design primer](https://github.com/donnemartin/system-design-primer)  
[Twitter](https://blog.twitter.com/engineering/en_us.html)  
[Thumbtack](https://www.thumbtack.com/engineering)  
[Uber](http://eng.uber.com)  
[Yahoo](https://yahooeng.tumblr.com)  
[Yelp](https://engineeringblog.yelp.com)  
[Zoom](https://medium.com/zoom-developer-blog)

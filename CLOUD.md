# Cloud Data

PuffinDB is a **Cloud Data** engine for datasets of any size.

Data has weight, it lives in the cloud, and PuffinDB is the engine working against the cloud's gravitational pull.

## Data Weight
When thinking about data, one should not think in terms of small data or big data. This volumetric classification isn't really helpful anymore. Instead, one should think in terms of **weight**. Data has mass (the larger the dataset, the larger its mass), and lives within a cloud that exerts a gravitational pull (weight) on the data, with a fixed [gravitational constant](https://en.wikipedia.org/wiki/Gravitational_constant). The larger data gets, the stronger a gravitational pull is exerted on it by the cloud it resides in. According to Newton's second law of motion:

```
W = m·g
```

According to this analogy, a cloud's gravitational constant `g` is a factor of its internal bandwidth (how fast can you move data from S3 to an EC2 instance), its external bandwidth (how fast can you download data from the cloud to your client computer), and its data egress cost (how much does it cost to do the latter).
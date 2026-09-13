---
title: "Two zones or three? A design framework for zone-resilient Azure workloads"
url: "https://azure.microsoft.com/en-us/blog/two-zones-or-three-a-design-framework-for-zone-resilient-azure-workloads/"
date: "2026-09-09"
author: "Mark Russinovich, Eric Henry and Sai Vaidhyanathan"
feed_url: "https://azure.microsoft.com/en-us/blog/feed/atom/"
---
Zone resiliency isn't a single number you apply to a whole workload. The useful question isn't “how many zones?” but “how many zones does each component need to survive the loss of one?” Decide zone patterns component by component, use service-managed zone redundancy wherever it fits, and reserve three-zone designs for the components that genuinely require a third failure domain. The post Two zones or three?

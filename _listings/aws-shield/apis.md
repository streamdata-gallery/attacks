---
name: AWS Shield
description: AWS Shield is a managed Distributed Denial of Service protection service
  that safeguards web applications running on AWS. AWS Shield provides always-on detection
  and automatic inline mitigations that minimize application downtime and latency,
  so there is no need to engage AWS Support to benefit from DDoS protection. There
  are two tiers of AWS Shield, Standard and Advanced. All AWS customers benefit from
  the automatic protections of AWS Shield Standard, at no additional charge. AWS Shield
  Standard defends against most common, frequently occurring network and transport
  layer DDoS attacks that target your web site or applications.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
  Shot 2016-12-30 at 10.35.48 PM.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Amazon Web Services
created: "2018-03-27"
modified: "2018-03-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/attacks/master/_listings/aws-shield/apis.yaml
specificationVersion: "0.14"
apis:
- name: AWS Shield API
  description: AWS Shield is a managed Distributed Denial of Service protection service
    that safeguards web applications running on AWS
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2016-12-30 at 10.35.48 PM.png
  humanURL: ""
  baseURL: :///
  tags: Attacks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/attacks/master/_listings/aws-shield/action-listattacks-get.md
- name: AWS Shield API List Attacks
  description: |-
    Returns all ongoing DDoS attacks or all DDoS attacks during a specified time
             period.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2016-12-30 at 10.35.48 PM.png
  humanURL: https://aws.amazon.com/shield/
  baseURL: http:://{host}//
  tags: Attacks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/attacks/master/_listings/aws-shield/action-listattacks-get.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/waf/latest/APIReference/
- type: x-documentation
  url: http://docs.aws.amazon.com/waf/latest/DDOSAPIReference/Welcome.htm
- type: x-faq
  url: https://aws.amazon.com/shield/faqs/
- type: x-pricing
  url: https://aws.amazon.com/shield/pricing/
- type: x-website
  url: https://aws.amazon.com/shield/
- type: x-documentation
  url: http://docs.aws.amazon.com/waf/latest/APIReference/
- type: x-documentation
  url: http://docs.aws.amazon.com/waf/latest/DDOSAPIReference/Welcome.htm
- type: x-faq
  url: https://aws.amazon.com/shield/faqs/
- type: x-pricing
  url: https://aws.amazon.com/shield/pricing/
- type: x-website
  url: https://aws.amazon.com/shield/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
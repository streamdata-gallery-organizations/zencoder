---
name: Zencoder
x-slug: zencoder
description: Audio and video encoding/transcoding software as a service. Convert videos
  online into web and mobile formats using our cloud encoding API.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
x-kinRank: "7"
x-alexaRank: "596400"
tags: Zencoder
created: "2018-09-01"
modified: "2018-09-01"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/apis.md
specificationVersion: "0.14"
apis:
- name: Zencoder - Get Account Details
  x-api-slug: account-get
  description: Get Account Details
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/account-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/account-get-openapi.md
- name: Zencoder - Create an Account
  x-api-slug: account-post
  description: Create an Account
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/account-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/account-post-openapi.md
- name: Zencoder - Integration Mode
  x-api-slug: accountintegration-put
  description: Integration Mode
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/accountintegration-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/accountintegration-put-openapi.md
- name: Zencoder - Integration Mode - Live
  x-api-slug: accountlive-put
  description: Integration Mode - Live
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/accountlive-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/accountlive-put-openapi.md
- name: Zencoder - Get Input Details
  x-api-slug: inputsinput-id-get
  description: Get Input Details
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/inputsinput-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/inputsinput-id-get-openapi.md
- name: Zencoder - Input Progress
  x-api-slug: inputsinput-idprogress-get
  description: 'The return will contain one or more of the following keys: state,
    current_event, current_event_progress and progress.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/inputsinput-idprogress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/inputsinput-idprogress-get-openapi.md
- name: Zencoder - List Jobs
  x-api-slug: jobs-get
  description: A list of jobs can be obtained by sending an HTTP GET request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobs-get-openapi.md
- name: Zencoder - Create a Job
  x-api-slug: jobs-post
  description: Encoding jobs are created by sending an HTTP POST request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobs-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobs-post-openapi.md
- name: Zencoder - Get Job Details
  x-api-slug: jobsjob-id-get
  description: Get Job Details
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobsjob-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobsjob-id-get-openapi.md
- name: Zencoder - Cancel a Job
  x-api-slug: jobsjob-idcancel-put
  description: If you wish to cancel a job that has not yet finished processing you
    may send a request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobsjob-idcancel-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobsjob-idcancel-put-openapi.md
- name: Zencoder - Finish a LIve Job
  x-api-slug: jobsjob-idfinish-put
  description: Finishes the input on a Live streaming job.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobsjob-idfinish-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobsjob-idfinish-put-openapi.md
- name: Zencoder - Job Progress
  x-api-slug: jobsjob-idprogress-get
  description: 'The return will contain one or more of the following keys: state,
    input, outputs, and progress.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobsjob-idprogress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobsjob-idprogress-get-openapi.md
- name: Zencoder - Resubmit a Job
  x-api-slug: jobsjob-idresubmit-put
  description: If a job has failed processing you may request that it be attempted
    again.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobsjob-idresubmit-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/jobsjob-idresubmit-put-openapi.md
- name: Zencoder - Output Progress
  x-api-slug: outputsoutput-idprogress-get
  description: 'The return will contain one or more of the following keys: state,
    current_event, current_event_progress and progress.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/outputsoutput-idprogress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/outputsoutput-idprogress-get-openapi.md
- name: Zencoder - Get Usage for VOD & Live
  x-api-slug: reportsall-get
  description: Get Usage for VOD & Live
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/reportsall-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/reportsall-get-openapi.md
- name: Zencoder - Get Usage for Live
  x-api-slug: reportslive-get
  description: Get Usage for Live
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/reportslive-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/reportslive-get-openapi.md
- name: Zencoder - Get Minutes Used
  x-api-slug: reportsminutes-get
  description: Get Minutes Used
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/reportsminutes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/reportsminutes-get-openapi.md
- name: Zencoder - Get Usage for VOD
  x-api-slug: reportsvod-get
  description: Get Usage for VOD
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/reportsvod-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/reportsvod-get-openapi.md
- name: Zencoder - Get Output Details
  x-api-slug: v2outputsoutput-id-get
  description: Get Output Details
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/282-zencoder.jpg
  humanURL: http://zencoder.com/
  baseURL: https://app.zencoder.com//api/v2
  tags: Encoding, Video Encoding, Getting Started Example, Stack Network, SaaS, Technology,
    Enterprise, internet, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/v2outputsoutput-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/zencoder/master/_listings/zencoder/v2outputsoutput-id-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://youtube.api.gallery.streamdata.io
- type: x-api-stack
  url: http://zencoder.stack.network
- type: x-base
  url: https://app.zencoder.com/api/
- type: x-blog
  url: http://blog.zencoder.com/
- type: x-blog-rss
  url: http://blog.zencoder.com/feed/
- type: x-contact-form
  url: https://zencoder.com/en/sales
- type: x-crunchbase
  url: http://www.crunchbase.com/company/zencoder
- type: x-crunchbase
  url: https://crunchbase.com/organization/zencoder
- type: x-developer
  url: http://zencoder.com/api/
- type: x-email
  url: privacy@zencoder.com
- type: x-error-codes
  url: https://app.zencoder.com/docs/errors
- type: x-facebook
  url: http://www.facebook.com/zencoderinc
- type: x-faq
  url: https://app.zencoder.com/docs/faq
- type: x-getting-started
  url: https://app.zencoder.com/docs/guides/getting-started
- type: x-github
  url: https://github.com/zencoder
- type: x-pricing
  url: https://zencoder.com/en/file-transcoding/pricing#basic
- type: x-pricing
  url: https://zencoder.com/en/live-transcoding/pricing
- type: x-privacy
  url: http://zencoder.com/privacy
- type: x-selfservice-registration
  url: https://app.zencoder.com/signup
- type: x-terms-of-service
  url: http://zencoder.com/terms
- type: x-twitter
  url: https://twitter.com/zencoderinc
- type: x-website
  url: http://zencoder.com/
- type: x-website
  url: http://zencoder.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
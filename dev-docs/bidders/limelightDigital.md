---
layout: bidder
title: Limelight Digital
description: Prebid Limelight Digital Bidder Adaptor
biddercode: limelightDigital
pbjs: true
pbs: false
media_types: video, banner
userIds: all
fpd_supported: false
gdpr_supported: true
usp_supported: true
coppa_supported: true
schain_supported: true
prebid_member: false
ortb_blocking_supported: true
multiformat_supported: will-bid-on-one
floors_supported: false
---

### Bid Params

{: .table .table-bordered .table-striped }

| Name           | Scope      | Description                                                    | Example            |type|
| :-----------   | :--------- | :------------                                                  | :----------------- |:---|
| `host` | required | Ad network's RTB host | `'exchange.ortb.net'` | `string` |
| `adUnitId` | required   | Ad Unit Id will be generated on Limelight Digital Platform. | 0                        | `integer` |
| `adUnitType`      | required   | Type of Ad Unit (`'video'`, `'banner'`)                                             | `'banner'`                 | `string` |
| `publisherId` | optional | Publisher ID | `'12345'` | `string` |

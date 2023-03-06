### Sources/Statistics
*Sources used for compiling the block lists (for the individual licenses of the sources, see the source files or source repositories!) :*
#### LIGHT
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/light-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/light-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/light-removed-dead.txt)
```
585713 (96%) included | 181 (0%) removed | 25356 (4%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% |   99740 | personal.txt
  2 |      63% |   1% |     36% |     140 | personal-wildcard-rules.txt
  3 |     100% |   0% |      0% |  111885 | personal-tif.txt
  4 |     100% |   0% |      0% |    3003 | fake.txt
  5 |      94% |   2% |      4% |    2994 | black.list

For domain and host lists, additionally: matching/missing subdomains (see at the bottom)
```
#### MULTI
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/multi-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/multi-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/multi-removed-dead.txt)
```
1024211 (94%) included | 878 (0%) removed | 62100 (6%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% |  585713 | light.txt
  2 |      98% |   1% |      1% |  106745 | https://o0.pages.dev/Lite/hosts.txt
  3 |      94% |   6% |      0% |   83890 | adguarddns.domains.txt
  4 |      98% |   2% |      0% |  848976 | oisd.domains.txt
  5 |      97% |   3% |      0% |     359 | https://raw.githubusercontent.com/manic-code/Emerging-Malicious-Domain-Blocklist/main/hosts.txt
  6 |      92% |   8% |      0% |     256 | https://raw.githubusercontent.com/AssoEchap/stalkerware-indicators/master/quad9_blocklist.txt

For domain and host lists, additionally: matching/missing subdomains (see at the bottom)
```
#### PRO
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/pro-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/pro-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/pro-removed-dead.txt)
```
1285113 (82%) included | 943 (0%) removed | 288639 (18%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% | 1024211 | multi.txt
  2 |      65% |  35% |      0% |  185701 | https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts
  3 |      77% |  23% |      0% |  408180 | notracking.domains.txt
  4 |      93% |   7% |      0% |   56682 | easylist.domains.txt
  5 |      96% |   4% |      0% |    1274 | ublock.domains.txt

For domain and host lists, additionally: matching/missing subdomains (see at the bottom)
```
#### PRO.PLUS
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/pro.plus-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/pro.plus-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/pro.plus-removed-dead.txt)
```
1429119 (82%) included | 1910 (0%) removed | 304464 (18%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% | 1285113 | pro.txt
  2 |     100% |   0% |      0% |   24086 | pro.plus.extension.domains
  3 |      98% |   1% |      1% |  264357 | https://o0.pages.dev/Pro/hosts.txt
  4 |      65% |  35% |      0% |  185701 | https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts
  5 |      77% |  23% |      0% |  408180 | notracking.domains.txt
  6 |      98% |   2% |      0% |  848976 | oisd.domains.txt
  7 |      93% |   7% |      0% |   48713 | https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt
  8 |      77% |  23% |      0% |     550 | https://raw.githubusercontent.com/AdguardTeam/AdGuardSDNSFilter/master/Filters/rules.txt
  9 |      89% |  10% |      1% |     835 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_11_Mobile/filter.txt
 10 |      74% |  26% |      0% |     125 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_13_Turkish/filter.txt
 11 |      82% |  17% |      1% |     194 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt
 12 |      87% |  13% |      0% |    9310 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_16_French/filter.txt
 13 |      97% |   0% |      3% |      37 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_18_Annoyances_Cookies/filter.txt
 14 |      76% |  24% |      0% |     128 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_19_Annoyances_Popups/filter.txt
 15 |      78% |  22% |      0% |     540 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_1_Russian/filter.txt
 16 |     100% |   0% |      0% |       5 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_21_Annoyances_Other/filter.txt
 17 |      90% |  10% |      0% |    7421 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt
 18 |      92% |   8% |      0% |      24 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_22_Annoyances_Widgets/filter.txt
 19 |      98% |   2% |      0% |   25757 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt
 20 |      98% |   2% |      0% |   24254 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt
 21 |      50% |  50% |      0% |       2 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_4_Social/filter.txt
 22 |      86% |  14% |      0% |      56 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_6_German/filter.txt
 23 |      99% |   1% |      0% |     155 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_7_Japanese/filter.txt
 24 |      95% |   5% |      0% |      21 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_8_Dutch/filter.txt
 25 |      74% |  26% |      0% |      86 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_9_Spanish/filter.txt
 26 |      98% |   2% |      0% |    1125 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/adservers.txt
 27 |     100% |   0% |      0% |     158 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/adservers_firstparty.txt
 28 |      96% |   4% |      0% |      84 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/cryptominers.txt
 29 |     100% |   0% |      0% |      34 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/foreign.txt
 30 |      58% |  42% |      0% |     304 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/ChineseFilter/sections/adservers.txt
 31 |     100% |   0% |      0% |       2 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/DutchFilter/sections/adservers.txt
 32 |     100% |   0% |      0% |       5 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/DutchFilter/sections/adservers_firstparty.txt
 33 |      62% |  38% |      0% |      13 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/FrenchFilter/sections/adservers.txt
 34 |      94% |   3% |      3% |      33 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/GermanFilter/sections/adservers.txt
 35 |      98% |   1% |      1% |     335 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/JapaneseFilter/sections/adservers.txt
 36 |      89% |  10% |      1% |     858 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/MobileFilter/sections/adservers.txt
 37 |      65% |  35% |      0% |    3728 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/adservers.txt
 38 |      71% |  29% |      0% |     171 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/adservers_firstparty.txt
 39 |      64% |  36% |      0% |      56 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/news_exchange.txt
 40 |      78% |  20% |      2% |     172 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpanishFilter/sections/adservers.txt
 41 |      90% |   9% |      1% |     661 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/mobile.txt
 42 |      95% |   3% |      2% |    4797 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers.txt
 43 |      86% |  14% |      0% |    2196 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers_firstparty.txt
 44 |      83% |  17% |      0% |     281 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/TurkishFilter/sections/adservers.txt
 45 |      62% |  38% |      0% |      61 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/TurkishFilter/sections/adservers_firstparty.txt
 46 |      98% |   2% |      0% |   21491 | https://easylist-downloads.adblockplus.org/easylist.txt
 47 |      99% |   1% |      0% |   15304 | https://easylist-downloads.adblockplus.org/easyprivacy.txt
 48 |      97% |   2% |      1% |      96 | https://easylist-downloads.adblockplus.org/antiadblockfilters.txt
 49 |      77% |  23% |      0% |      13 | https://easylist-downloads.adblockplus.org/Liste_AR.txt
 50 |      47% |  53% |      0% |    1928 | https://easylist-downloads.adblockplus.org/advblock.txt
 51 |      90% |  10% |      0% |    7365 | https://easylist-downloads.adblockplus.org/easylistchina.txt
 52 |      94% |   6% |      0% |      16 | https://easylist-downloads.adblockplus.org/easylistdutch.txt
 53 |      87% |  13% |      0% |      40 | https://easylist-downloads.adblockplus.org/easylistgermany.txt
 54 |      91% |   7% |      2% |      46 | https://easylist-downloads.adblockplus.org/easylistitaly.txt
 55 |     100% |   0% |      0% |       3 | https://easylist-downloads.adblockplus.org/easylistpolish.txt
 56 |     100% |   0% |      0% |      15 | https://easylist-downloads.adblockplus.org/easylistportuguese.txt
 57 |     100% |   0% |      0% |       7 | https://easylist-downloads.adblockplus.org/easylistspanish.txt
 58 |     100% |   0% |      0% |       3 | https://easylist-downloads.adblockplus.org/indianlist.txt
 59 |     100% |   0% |      0% |       3 | https://easylist-downloads.adblockplus.org/koreanlist.txt
 60 |      87% |  13% |      0% |    9302 | https://easylist-downloads.adblockplus.org/liste_fr.txt
 61 |      47% |  53% |      0% |    1928 | https://easylist-downloads.adblockplus.org/ruadlist.txt
 62 |      63% |  37% |      0% |      19 | https://fanboy.co.nz/enhancedstats.txt
 63 |      60% |  40% |      0% |      15 | https://notabug.org/latvian-list/adblock-latvian/raw/master/lists/latvian-list.txt
 64 |      92% |   8% |      0% |      24 | https://raw.github.com/tomasko126/easylistczechandslovak/master/filters.txt
 65 |      42% |  58% |      0% |      40 | https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo.txt
 66 |     100% |   0% |      0% |       9 | https://raw.githubusercontent.com/EasyList-Lithuania/easylist_lithuania/master/easylistlithuania.txt
 67 |     100% |   0% |      0% |      70 | https://raw.githubusercontent.com/abpvn/abpvn/master/filter/abpvn.txt
 68 |      90% |   9% |      1% |     617 | https://raw.githubusercontent.com/easylist-thailand/easylist-thailand/master/subscription/easylist-thailand.txt
 69 |      71% |  29% |      0% |      31 | https://raw.githubusercontent.com/easylist/EasyListHebrew/master/EasyListHebrew.txt
 70 |      89% |  11% |      0% |      53 | https://raw.githubusercontent.com/hufilter/hufilter/master/hufilter.txt
 71 |      95% |   5% |      0% |      98 | https://raw.githubusercontent.com/yous/YousList/master/youslist.txt
 72 |      97% |   0% |      3% |     180 | https://secure.fanboy.co.nz/fanboy-annoyance.txt
 73 |      96% |   0% |      4% |     141 | https://secure.fanboy.co.nz/fanboy-cookiemonster.txt
 74 |     100% |   0% |      0% |       4 | https://secure.fanboy.co.nz/fanboy-social.txt
 75 |     100% |   0% |      0% |       4 | https://stanev.org/abp/adblock_bg.txt
 76 |      77% |  23% |      0% |      30 | https://www.void.gr/kargig/void-gr-filters.txt
 77 |      85% |  10% |      5% |     117 | https://www.zoso.ro/pages/rolist.txt
 78 |      67% |  33% |      0% |     263 | https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/src/advert/adservers.txt
 79 |      56% |  44% |      0% |      18 | https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/src/advert/thirdparty.txt
 80 |      98% |   2% |      0% |   22154 | https://raw.githubusercontent.com/easylist/easylist/master/easylist/easylist_adservers.txt
 81 |     100% |   0% |      0% |     736 | https://raw.githubusercontent.com/easylist/easylist/master/easylist/easylist_thirdparty.txt
 82 |      98% |   0% |      2% |    1273 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_thirdparty.txt
 83 |      99% |   0% |      1% |     480 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_thirdparty_international.txt
 84 |      97% |   0% |      3% |    4444 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_trackingservers.txt
 85 |      97% |   0% |      3% |     926 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_trackingservers_international.txt
 86 |      92% |   4% |      4% |      23 | https://raw.githubusercontent.com/easylist/easylistdutch/master/easylistdutch/block_third_party_server.txt
 87 |      93% |   6% |      1% |     283 | https://raw.githubusercontent.com/easylist/easylistgermany/master/easylistgermany/easylistgermany_adservers.txt
 88 |      95% |   5% |      0% |     134 | https://raw.githubusercontent.com/easylist/easylistitaly/master/easylistitaly/easylistitaly_adservers.txt
 89 |      88% |  10% |      2% |    1052 | https://raw.githubusercontent.com/lassekongo83/Frellwits-filter-lists/master/Frellwits-Swedish-Hosts-File.txt
 90 |      94% |   2% |      4% |      54 | https://raw.githubusercontent.com/realodix/AdBlockID/master/src/adservers.adfl
 91 |      97% |   3% |      0% |     314 | https://raw.githubusercontent.com/DandelionSprout/adfilt/master/NorwegianExperimentalList%20alternate%20versions/NordicFiltersAdGuardHome.txt
 92 |     100% |   0% |      0% |       7 | https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Other%20domains%20versions/BrowseWebsitesWithoutLoggingInAGH.txt
 93 |      99% |   1% |      0% |     823 | https://raw.githubusercontent.com/bigdargon/hostsVN/master/filters/adservers.txt
 94 |      96% |   4% |      0% |     221 | https://raw.githubusercontent.com/MasterKia/PersianBlocker/main/PersianBlockerHosts.txt
 95 |      46% |  51% |      3% |     744 | https://raw.githubusercontent.com/craiu/mobiletrackers/master/list.txt
 96 |     100% |   0% |      0% |       2 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/annoyances.txt
 97 |      96% |   4% |      0% |     896 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/badware.txt
 98 |      97% |   3% |      0% |      40 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2020.txt
 99 |      95% |   5% |      0% |      41 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2021.txt
100 |      95% |   5% |      0% |      56 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2022.txt
101 |     100% |   0% |      0% |      46 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2023.txt
102 |      97% |   3% |      0% |     136 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters.txt
103 |     100% |   0% |      0% |      36 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/privacy.txt
104 |     100% |   0% |      0% |       5 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/resource-abuse.txt
105 |      96% |   1% |      3% |     492 | https://gitlab.com/quidsup/notrack-annoyance-blocklist/-/raw/master/notrack-annoyance.txt
106 |      98% |   1% |      1% |   16573 | https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-blocklist.txt
107 |      88% |  10% |      2% |     252 | https://assets.windscribe.com/custom_blocklists/clickbait.txt
108 |      97% |   3% |      0% |      31 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-matomo.txt
109 |      97% |   3% |      0% |     359 | https://raw.githubusercontent.com/manic-code/Emerging-Malicious-Domain-Blocklist/main/hosts.txt
110 |      92% |   8% |      0% |     256 | https://raw.githubusercontent.com/AssoEchap/stalkerware-indicators/master/quad9_blocklist.txt
111 |      97% |   3% |      0% |    2753 | analytics-metrics-extension.txt
112 |     100% |   0% |      0% |      22 | native.apple.txt
113 |     100% |   0% |      0% |      65 | native.huawei.txt
114 |      70% |   0% |     30% |     145 | windows-office.txt
115 |     100% |   0% |      0% |     260 | native.tiktok.txt
116 |      95% |   5% |      0% |      66 | lg-webos.txt
117 |      97% |   2% |      1% |    2994 | black.list
118 |     100% |   0% |      0% |       2 | black.list.plus
119 |      93% |   0% |      7% |    4120 | black.list.size
120 |     100% |   0% |      0% |   99740 | personal.txt
121 |      80% |   1% |     19% |     140 | personal-wildcard-rules.txt
122 |     100% |   0% |      0% |    3003 | fake.txt
123 |     100% |   0% |      0% |  111885 | personal-tif.txt

For domain and host lists, additionally: matching/missing subdomains (see at the bottom)
```
#### ULTIMATE
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/ultimate-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/ultimate-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/ultimate-removed-dead.txt)
```
2249203 (86%) included | 1822 (0%) removed | 376142 (14%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% | 1429119 | pro.plus.txt
  2 |     100% |   0% |      0% |   45463 | ultimate.extension.domains
  3 |      99% |   1% |      0% |  264357 | https://o0.pages.dev/Pro/hosts.txt
  4 |      65% |  35% |      0% |  185701 | https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts
  5 |      77% |  23% |      0% |  408180 | notracking.domains.txt
  6 |      98% |   2% |      0% |  848976 | oisd.domains.txt
  7 |      93% |   7% |      0% |   48713 | https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt
  8 |      77% |  23% |      0% |     550 | https://raw.githubusercontent.com/AdguardTeam/AdGuardSDNSFilter/master/Filters/rules.txt
  9 |      90% |  10% |      0% |     835 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_11_Mobile/filter.txt
 10 |      74% |  26% |      0% |     125 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_13_Turkish/filter.txt
 11 |      82% |  17% |      1% |     194 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt
 12 |      87% |  13% |      0% |    9310 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_16_French/filter.txt
 13 |      97% |   0% |      3% |      37 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_18_Annoyances_Cookies/filter.txt
 14 |      76% |  24% |      0% |     128 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_19_Annoyances_Popups/filter.txt
 15 |      78% |  22% |      0% |     540 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_1_Russian/filter.txt
 16 |     100% |   0% |      0% |       5 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_21_Annoyances_Other/filter.txt
 17 |      90% |  10% |      0% |    7421 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt
 18 |      92% |   8% |      0% |      24 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_22_Annoyances_Widgets/filter.txt
 19 |      98% |   2% |      0% |   25757 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt
 20 |      98% |   2% |      0% |   24254 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt
 21 |      50% |  50% |      0% |       2 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_4_Social/filter.txt
 22 |      86% |  14% |      0% |      56 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_6_German/filter.txt
 23 |      99% |   1% |      0% |     155 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_7_Japanese/filter.txt
 24 |      95% |   5% |      0% |      21 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_8_Dutch/filter.txt
 25 |      74% |  26% |      0% |      86 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_9_Spanish/filter.txt
 26 |      98% |   2% |      0% |    1125 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/adservers.txt
 27 |     100% |   0% |      0% |     158 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/adservers_firstparty.txt
 28 |      96% |   4% |      0% |      84 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/cryptominers.txt
 29 |     100% |   0% |      0% |      34 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/foreign.txt
 30 |      58% |  42% |      0% |     304 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/ChineseFilter/sections/adservers.txt
 31 |     100% |   0% |      0% |       2 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/DutchFilter/sections/adservers.txt
 32 |     100% |   0% |      0% |       5 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/DutchFilter/sections/adservers_firstparty.txt
 33 |      62% |  38% |      0% |      13 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/FrenchFilter/sections/adservers.txt
 34 |      94% |   3% |      3% |      33 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/GermanFilter/sections/adservers.txt
 35 |      98% |   1% |      1% |     335 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/JapaneseFilter/sections/adservers.txt
 36 |      90% |  10% |      0% |     858 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/MobileFilter/sections/adservers.txt
 37 |      65% |  35% |      0% |    3728 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/adservers.txt
 38 |      71% |  29% |      0% |     171 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/adservers_firstparty.txt
 39 |      64% |  36% |      0% |      56 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/news_exchange.txt
 40 |      79% |  20% |      1% |     172 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpanishFilter/sections/adservers.txt
 41 |      91% |   9% |      0% |     661 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/mobile.txt
 42 |      95% |   3% |      2% |    4797 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers.txt
 43 |      86% |  14% |      0% |    2196 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers_firstparty.txt
 44 |      83% |  17% |      0% |     281 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/TurkishFilter/sections/adservers.txt
 45 |      62% |  38% |      0% |      61 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/TurkishFilter/sections/adservers_firstparty.txt
 46 |      98% |   2% |      0% |   21491 | https://easylist-downloads.adblockplus.org/easylist.txt
 47 |      99% |   1% |      0% |   15304 | https://easylist-downloads.adblockplus.org/easyprivacy.txt
 48 |      97% |   2% |      1% |      96 | https://easylist-downloads.adblockplus.org/antiadblockfilters.txt
 49 |      77% |  23% |      0% |      13 | https://easylist-downloads.adblockplus.org/Liste_AR.txt
 50 |      47% |  53% |      0% |    1928 | https://easylist-downloads.adblockplus.org/advblock.txt
 51 |      90% |  10% |      0% |    7365 | https://easylist-downloads.adblockplus.org/easylistchina.txt
 52 |      94% |   6% |      0% |      16 | https://easylist-downloads.adblockplus.org/easylistdutch.txt
 53 |      87% |  13% |      0% |      40 | https://easylist-downloads.adblockplus.org/easylistgermany.txt
 54 |      91% |   7% |      2% |      46 | https://easylist-downloads.adblockplus.org/easylistitaly.txt
 55 |     100% |   0% |      0% |       3 | https://easylist-downloads.adblockplus.org/easylistpolish.txt
 56 |     100% |   0% |      0% |      15 | https://easylist-downloads.adblockplus.org/easylistportuguese.txt
 57 |     100% |   0% |      0% |       7 | https://easylist-downloads.adblockplus.org/easylistspanish.txt
 58 |     100% |   0% |      0% |       3 | https://easylist-downloads.adblockplus.org/indianlist.txt
 59 |     100% |   0% |      0% |       3 | https://easylist-downloads.adblockplus.org/koreanlist.txt
 60 |      87% |  13% |      0% |    9302 | https://easylist-downloads.adblockplus.org/liste_fr.txt
 61 |      47% |  53% |      0% |    1928 | https://easylist-downloads.adblockplus.org/ruadlist.txt
 62 |      63% |  37% |      0% |      19 | https://fanboy.co.nz/enhancedstats.txt
 63 |      60% |  40% |      0% |      15 | https://notabug.org/latvian-list/adblock-latvian/raw/master/lists/latvian-list.txt
 64 |      92% |   8% |      0% |      24 | https://raw.github.com/tomasko126/easylistczechandslovak/master/filters.txt
 65 |      42% |  58% |      0% |      40 | https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo.txt
 66 |     100% |   0% |      0% |       9 | https://raw.githubusercontent.com/EasyList-Lithuania/easylist_lithuania/master/easylistlithuania.txt
 67 |     100% |   0% |      0% |      70 | https://raw.githubusercontent.com/abpvn/abpvn/master/filter/abpvn.txt
 68 |      91% |   9% |      0% |     617 | https://raw.githubusercontent.com/easylist-thailand/easylist-thailand/master/subscription/easylist-thailand.txt
 69 |      71% |  29% |      0% |      31 | https://raw.githubusercontent.com/easylist/EasyListHebrew/master/EasyListHebrew.txt
 70 |      89% |  11% |      0% |      53 | https://raw.githubusercontent.com/hufilter/hufilter/master/hufilter.txt
 71 |      95% |   5% |      0% |      98 | https://raw.githubusercontent.com/yous/YousList/master/youslist.txt
 72 |      97% |   0% |      3% |     180 | https://secure.fanboy.co.nz/fanboy-annoyance.txt
 73 |      96% |   0% |      4% |     141 | https://secure.fanboy.co.nz/fanboy-cookiemonster.txt
 74 |     100% |   0% |      0% |       4 | https://secure.fanboy.co.nz/fanboy-social.txt
 75 |     100% |   0% |      0% |       4 | https://stanev.org/abp/adblock_bg.txt
 76 |      77% |  23% |      0% |      30 | https://www.void.gr/kargig/void-gr-filters.txt
 77 |      87% |  10% |      3% |     117 | https://www.zoso.ro/pages/rolist.txt
 78 |      67% |  33% |      0% |     263 | https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/src/advert/adservers.txt
 79 |      56% |  44% |      0% |      18 | https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/src/advert/thirdparty.txt
 80 |      98% |   2% |      0% |   22154 | https://raw.githubusercontent.com/easylist/easylist/master/easylist/easylist_adservers.txt
 81 |     100% |   0% |      0% |     736 | https://raw.githubusercontent.com/easylist/easylist/master/easylist/easylist_thirdparty.txt
 82 |      99% |   0% |      1% |    1273 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_thirdparty.txt
 83 |      99% |   0% |      1% |     480 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_thirdparty_international.txt
 84 |      97% |   0% |      3% |    4444 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_trackingservers.txt
 85 |      97% |   0% |      3% |     926 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_trackingservers_international.txt
 86 |      92% |   4% |      4% |      23 | https://raw.githubusercontent.com/easylist/easylistdutch/master/easylistdutch/block_third_party_server.txt
 87 |      93% |   6% |      1% |     283 | https://raw.githubusercontent.com/easylist/easylistgermany/master/easylistgermany/easylistgermany_adservers.txt
 88 |      95% |   5% |      0% |     134 | https://raw.githubusercontent.com/easylist/easylistitaly/master/easylistitaly/easylistitaly_adservers.txt
 89 |      88% |  10% |      2% |    1052 | https://raw.githubusercontent.com/lassekongo83/Frellwits-filter-lists/master/Frellwits-Swedish-Hosts-File.txt
 90 |      94% |   2% |      4% |      54 | https://raw.githubusercontent.com/realodix/AdBlockID/master/src/adservers.adfl
 91 |      97% |   3% |      0% |     314 | https://raw.githubusercontent.com/DandelionSprout/adfilt/master/NorwegianExperimentalList%20alternate%20versions/NordicFiltersAdGuardHome.txt
 92 |     100% |   0% |      0% |       7 | https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Other%20domains%20versions/BrowseWebsitesWithoutLoggingInAGH.txt
 93 |      99% |   1% |      0% |     823 | https://raw.githubusercontent.com/bigdargon/hostsVN/master/filters/adservers.txt
 94 |      96% |   4% |      0% |     221 | https://raw.githubusercontent.com/MasterKia/PersianBlocker/main/PersianBlockerHosts.txt
 95 |      47% |  51% |      2% |     744 | https://raw.githubusercontent.com/craiu/mobiletrackers/master/list.txt
 96 |     100% |   0% |      0% |       2 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/annoyances.txt
 97 |      96% |   4% |      0% |     896 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/badware.txt
 98 |      97% |   3% |      0% |      40 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2020.txt
 99 |      95% |   5% |      0% |      41 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2021.txt
100 |      95% |   5% |      0% |      56 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2022.txt
101 |     100% |   0% |      0% |      46 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2023.txt
102 |      97% |   3% |      0% |     136 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters.txt
103 |     100% |   0% |      0% |      36 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/privacy.txt
104 |     100% |   0% |      0% |       5 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/resource-abuse.txt
105 |      96% |   1% |      3% |     492 | https://gitlab.com/quidsup/notrack-annoyance-blocklist/-/raw/master/notrack-annoyance.txt
106 |      98% |   1% |      1% |   16573 | https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-blocklist.txt
107 |      88% |  10% |      2% |     252 | https://assets.windscribe.com/custom_blocklists/clickbait.txt
108 |      89% |  11% |      0% |     906 | https://raw.githubusercontent.com/AssoEchap/stalkerware-indicators/master/generated/hosts_full
109 |      57% |  29% |     14% |       7 | https://raw.githubusercontent.com/yourduskquibbles/webannoyances/master/ultralist.txt
110 |      74% |   8% |     18% |      91 | https://raw.githubusercontent.com/yokoffing/filterlists/main/privacy_essentials.txt
111 |      64% |   0% |     36% |      11 | https://raw.githubusercontent.com/yokoffing/filterlists/main/annoyance_list.txt
112 |      95% |   3% |      2% |    1040 | https://raw.githubusercontent.com/symbuzzer/Turkish-Ad-Hosts/main/hosts
113 |      95% |   4% |      1% |   16707 | https://raw.githubusercontent.com/migueldemoura/ublock-umatrix-rulesets/master/Hosts/ads-tracking
114 |      94% |   6% |      0% |   75636 | https://raw.githubusercontent.com/Cats-Team/AdRules/main/ad-domains.txt
115 |      91% |   8% |      1% |   57448 | https://anti-ad.net/easylist.txt
116 |      95% |   4% |      1% |   17560 | https://raw.githubusercontent.com/bigdargon/hostsVN/master/hosts
117 |      97% |   3% |      0% |    1788 | https://raw.githubusercontent.com/bigdargon/hostsVN/master/option/hosts-VN
118 |      84% |  16% |      0% |  150285 | https://raw.githubusercontent.com/bongochong/CombinedPrivacyBlockLists/master/newhosts-final.hosts
119 |      68% |  29% |      3% |     347 | https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt
120 |      86% |  11% |      3% |      35 | https://raw.githubusercontent.com/nextdns/cname-cloaking-blocklist/master/domains
121 |      97% |   3% |      0% |      31 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-matomo.txt
122 |      97% |   3% |      0% |     359 | https://raw.githubusercontent.com/manic-code/Emerging-Malicious-Domain-Blocklist/main/hosts.txt
123 |      99% |   0% |      1% |     168 | https://raw.githubusercontent.com/Potterli20/file/main/ad-hosts/hosts
124 |      99% |   1% |      0% |   22098 | https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Scam
125 |      99% |   1% |      0% |   18558 | ads-tracking-extension.txt
126 |      97% |   3% |      0% |    2753 | analytics-metrics-extension.txt
127 |     100% |   0% |      0% |      22 | native.apple.txt
128 |     100% |   0% |      0% |      65 | native.huawei.txt
129 |      76% |   0% |     24% |     145 | windows-office.txt
130 |     100% |   0% |      0% |     260 | native.tiktok.txt
131 |      95% |   5% |      0% |      66 | lg-webos.txt
132 |      98% |   2% |      0% |    2994 | black.list
133 |     100% |   0% |      0% |       2 | black.list.plus
134 |      94% |   0% |      6% |    4120 | black.list.size
135 |     100% |   0% |      0% |   99740 | personal.txt
136 |      85% |   1% |     14% |     140 | personal-wildcard-rules.txt
137 |     100% |   0% |      0% |    3003 | fake.txt
138 |     100% |   0% |      0% | 1209266 | tif.txt

For domain and host lists, additionally: matching/missing subdomains (see at the bottom)
```
#### FAKE
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/fake-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/fake-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/fake-removed-dead.txt)
```
3003 (97%) included | 0 (0%) removed | 108 (3%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |      99% |   1% |      0% |    1355 | fake.ts.txt
  2 |      99% |   1% |      0% |     338 | fake.vzni.txt
```
#### TIF
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/tif-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/tif-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/tif-removed-dead.txt)
```
1209266 (45%) included | 353 (0%) removed | 1452367 (55%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |      79% |  20% |      1% |     156 | https://gitlab.com/cmiksche/blacklists/-/raw/master/hosts
  2 |      33% |  67% |      0% |   97069 | https://hole.cert.pl/domains/domains_hosts.txt
  3 |      85% |  15% |      0% |   29226 | https://malware-filter.gitlab.io/malware-filter/phishing-filter-hosts.txt
  4 |      79% |  21% |      0% |     194 | https://malware-filter.gitlab.io/malware-filter/pup-filter-hosts.txt
  5 |      94% |   6% |      0% |   17600 | https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-hosts.txt
  6 |      69% |  31% |      0% |   15890 | https://malware-filter.gitlab.io/malware-filter/vn-badsite-filter-hosts.txt
  7 |      85% |  15% |      0% |     544 | https://paulgb.github.io/BarbBlock/blacklists/hosts-file.txt
  8 |      96% |   4% |      0% |   10129 | https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareHosts.txt
  9 |      29% |  71% |      0% |   23203 | https://raw.githubusercontent.com/Dogino/Discord-Phishing-URLs/main/pihole-phishing-adlist.txt
 10 |      91% |   9% |      0% |    2189 | https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts
 11 |      92% |   4% |      4% |      57 | https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts
 12 |      42% |  58% |      0% |    3319 | https://raw.githubusercontent.com/HexxiumCreations/threat-list/gh-pages/hosts.txt
 13 |      80% |  20% |      0% |    3392 | https://raw.githubusercontent.com/Th3M3/blocklists/master/malware.list
 14 |      61% |  39% |      0% |    3728 | https://raw.githubusercontent.com/bigdargon/hostsVN/master/extensions/threat/hosts
 15 |      90% |  10% |      0% |      58 | https://raw.githubusercontent.com/davidonzo/Threat-Intel/master/lists/latestdomains.piHole.txt
 16 |     100% |   0% |      0% |    1021 | https://raw.githubusercontent.com/durablenapkin/scamblocklist/master/hosts.txt
 17 |      20% |  80% |      0% |    8624 | https://raw.githubusercontent.com/guardicore/labs_campaigns/master/Autodiscover/autodiscover-tlds.txt
 18 |      54% |  45% |      1% |     724 | https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt
 19 |      27% |  73% |      0% |    1071 | https://raw.githubusercontent.com/metamask/eth-phishing-detect/master/src/hosts.txt
 20 |      76% |  23% |      1% |    1384 | https://raw.githubusercontent.com/mitchellkrogza/Badd-Boyz-Hosts/master/hosts
 21 |      58% |  42% |      0% |   13464 | https://raw.githubusercontent.com/mitchellkrogza/The-Big-List-of-Hacked-Malware-Web-Sites/master/hosts
 22 |      87% |  13% |      0% |   26225 | https://threatfox.abuse.ch/downloads/hostfile
 23 |     100% |   0% |      0% |     581 | https://urlhaus.abuse.ch/downloads/hostfile
 24 |      35% |  65% |      0% |  104204 | https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/malware-domains.txt
 25 |      88% |  12% |      0% |      26 | https://raw.githubusercontent.com/iam-py-test/vxvault_filter/main/domains_file.txt
 26 |      49% |  51% |      0% |     879 | https://raw.githubusercontent.com/piperun/iploggerfilter/master/filterlist
 27 |      96% |   4% |      0% |     896 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/badware.txt
 28 |      43% |  57% |      0% |     983 | https://azorult-tracker.net/api/list/domain?format=plain
 29 |      12% |  87% |      1% |     898 | https://cert-agid.gov.it/download/log4shell-iocs-raw-domain.txt
 30 |      42% |  58% |      0% |   12201 | https://dl.red.flag.domains/red.flag.domains_fr.txt
 31 |      22% |  78% |      0% |    9781 | https://gitlab.com/KevinThomas0/cryptoscamdb-lists/-/raw/master/cryptoscamdb-blocklist.txt
 32 |      20% |  80% |      0% |    1055 | https://gitlab.com/nitrohorse/government-malware-domains-blocklist/-/raw/master/domains.txt
 33 |      43% |  57% |      0% |    1077 | https://gitlab.com/quidsup/notrack-blocklists/-/raw/master/notrack-malware.txt
 34 |      63% |  37% |      0% |    1100 | https://orca.pet/notonmyshift/domains.txt
 35 |      90% |  10% |      0% |      58 | https://osint.digitalside.it/Threat-Intel/lists/latestdomains.txt
 36 |      40% |  60% |      0% |  120854 | https://phishing.army/download/phishing_army_blocklist.txt
 37 |      41% |  59% |      0% |  125124 | https://phishing.army/download/phishing_army_blocklist_extended.txt
 38 |      24% |  76% |      0% |    1438 | https://raw.githubusercontent.com/AmnestyTech/investigations/master/2021-07-18_nso/domains.txt
 39 |      45% |  55% |      0% |      29 | https://raw.githubusercontent.com/AmnestyTech/investigations/master/2021-10-07_donot/domains.txt
 40 |      25% |  75% |      0% |     326 | https://raw.githubusercontent.com/AmnestyTech/investigations/master/2021-12-16_cytrox/domains.txt
 41 |      88% |  12% |      0% |      34 | https://raw.githubusercontent.com/DRSDavidSoft/additional-hosts/master/domains/blacklist/fake-domains.txt
 42 |      45% |  55% |      0% |  107695 | https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADomains.txt
 43 |      83% |  17% |      0% |   33956 | https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Malware
 44 |      52% |  48% |      0% |     909 | https://raw.githubusercontent.com/SystemJargon/blocklists/main/lists/threats/aggregated-threats-1.txt
 45 |      58% |  42% |      0% |    4047 | https://raw.githubusercontent.com/bongochong/CombinedPrivacyBlockLists/master/NoFormatting/MD-ID-Fork.txt
 46 |      85% |  15% |      0% |      39 | https://raw.githubusercontent.com/craiu/iocs/main/log4shell/log4j_blocklist.txt
 47 |      71% |  29% |      0% |    5411 | https://raw.githubusercontent.com/elliotwutingfeng/GlobalAntiScamOrg-blocklist/main/global-anti-scam-org-scam-urls-pihole.txt
 48 |      48% |  52% |      0% |  601152 | https://raw.githubusercontent.com/elliotwutingfeng/Inversion-DNSBL-Blocklists/main/Google_hostnames.txt
 49 |      76% |  24% |      0% |    6801 | https://raw.githubusercontent.com/elliotwutingfeng/Inversion-DNSBL-Blocklists/main/Google_hostnames_light.txt
 50 |      68% |  32% |      0% |   10470 | https://raw.githubusercontent.com/iam-py-test/my_filters_001/main/Alternative%20list%20formats/antimalware_domains.txt
 51 |      20% |  80% |      0% |   16413 | https://raw.githubusercontent.com/ihgalis/pihole_collection/master/Sinking_Yachts_Phishing
 52 |      62% |  38% |      0% |    7331 | https://raw.githubusercontent.com/infinitytec/blocklists/master/scams-and-phishing.txt
 53 |      56% |  44% |      0% |     621 | https://raw.githubusercontent.com/marco-acorte/antispam-it/main/antispam-it.txt
 54 |      74% |  26% |      0% |    2243 | https://raw.githubusercontent.com/matomo-org/referrer-spam-blacklist/master/spammers.txt
 55 |      58% |  42% |      0% |   71155 | https://raw.githubusercontent.com/mitchellkrogza/Phishing.Database/master/phishing-domains-ACTIVE.txt
 56 |      78% |  22% |      0% |   16708 | https://raw.githubusercontent.com/mitchellkrogza/Phishing.Database/master/phishing-domains-NEW-today.txt
 57 |      22% |  78% |      0% |    2143 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-amnenstytech.txt
 58 |      49% |  51% |      0% |     534 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-certagid.txt
 59 |      36% |  64% |      0% |     387 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-certego.txt
 60 |      23% |  77% |      0% |    1009 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-citizenlabs.txt
 61 |      64% |  36% |      0% |    1830 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-csirt.txt
 62 |      65% |  35% |      0% |     297 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-cyble.txt
 63 |      43% |  57% |      0% |     242 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-drweb.txt
 64 |      66% |  34% |      0% |     224 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-eset.txt
 65 |      68% |  32% |      0% |     139 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-kaspersky.txt
 66 |      49% |  51% |      0% |    9307 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-main.txt
 67 |      44% |  56% |      0% |    2083 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-malware-traffic.txt
 68 |      15% |  85% |      0% |    1238 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-orangecyber.txt
 69 |      66% |  31% |      3% |      39 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-orangelog4shell.txt
 70 |      45% |  55% |      0% |    5491 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-personal.txt
 71 |      18% |  82% |      0% |     864 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-sentinelone.txt
 72 |      25% |  75% |      0% |      67 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-sophos.txt
 73 |      43% |  57% |      0% |     241 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-tag.txt
 74 |      48% |  52% |      0% |     508 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-unit42-playbook.txt
 75 |      11% |  89% |      0% |   23220 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-unit42-silverterrier.txt
 76 |      54% |  46% |      0% |     903 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-yoroi.txt
 77 |      38% |  62% |      0% |    5845 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-zscaler.txt
 78 |      50% |  50% |      0% |  274976 | https://raw.githubusercontent.com/stamparm/aux/master/maltrail-malware-domains.txt
 79 |      37% |  63% |      0% |   17843 | https://raw.githubusercontent.com/stamparm/blackbook/master/blackbook.txt
 80 |      32% |  68% |      0% |     500 | https://rescure.me/covid.txt
 81 |      74% |  26% |      0% |     500 | https://rescure.me/rescure_domain_blacklist.txt
 82 |      40% |  60% |      0% |      63 | https://www.botvrij.eu/data/ioclist.domain.raw
 83 |      55% |  45% |      0% |      53 | https://www.botvrij.eu/data/ioclist.hostname.raw
 84 |      70% |  30% |      0% |   43801 | https://www.stopforumspam.com/downloads/toxic_domains_whole.txt
 85 |      82% |  18% |      0% |   12265 | https://threatview.io/Downloads/DOMAIN-High-Confidence-Feed.txt
 86 |      45% |  55% |      0% |    2359 | https://hosts.tweedge.net/malicious.txt
 87 |      37% |  63% |      0% |   15883 | https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/cryptojacking/domains
 88 |      41% |  59% |      0% |   36784 | https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/phishing/domains
 89 |      41% |  59% |      0% |   37136 | https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/malware/domains
 90 |      92% |   8% |      0% |   23713 | black.list.threat-intelligence
 91 |     100% |   0% |      0% |      51 | black.list.hoster
 92 |     100% |   0% |      0% |  111885 | personal-tif.txt
```
#### DOH-VPN-PROXY-BYPASS
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/doh-vpn-proxy-bypass-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/doh-vpn-proxy-bypass-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/doh-vpn-proxy-bypass-removed-dead.txt)
```
1414 (51%) included | 3 (0%) removed | 1350 (49%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |      96% |   4% |      0% |     275 | https://raw.githubusercontent.com/oneoffdallas/dohservers/master/list.txt
  2 |      94% |   6% |      0% |     754 | https://raw.githubusercontent.com/SystemJargon/blocklists/main/lists/categories/dns-dot-quic-doh/TheGreaterWall-dns-dot.txt
  3 |      91% |   7% |      2% |     198 | https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/doh/domains
  4 |      14% |  86% |      0% |    1476 | https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/vpn/domains
  5 |      99% |   1% |      0% |     160 | https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/vpn
  6 |      92% |   8% |      0% |      12 | https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/tor
  7 |      93% |   7% |      0% |     287 | https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/proxies
  8 |     100% |   0% |      0% |       9 | https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/linux
  9 |      92% |   8% |      0% |     302 | https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/encrypted-dns
 10 |     100% |   0% |      0% |       9 | https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/browsers
 11 |     100% |   0% |      0% |       2 | https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/apple-private-relay
 12 |      94% |   6% |      0% |     493 | https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Tunnels
 13 |     100% |   0% |      0% |     352 | black.list.dohdot
```
#### DOH
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/doh-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/doh-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/doh-removed-dead.txt)
```
364 (94%) included | 0 (0%) removed | 24 (6%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |      92% |   8% |      0% |     302 | https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/encrypted-dns
  2 |     100% |   0% |      0% |     352 | black.list.dohdot
```
#### NOSAFESEARCH
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/nosafesearch-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/nosafesearch-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/nosafesearch-removed-dead.txt)
```
148 (83%) included | 0 (0%) removed | 30 (17%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |      83% |  17% |      0% |     174 | https://raw.githubusercontent.com/nextdns/no-safesearch/main/domains
```
#### DYNDNS
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/dyndns-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/dyndns-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/dyndns-removed-dead.txt)
```
1748 (100%) included | 0 (0%) removed | 0 (0%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% |    1664 | https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Dynamic
  2 |     100% |   0% |      0% |     790 | https://raw.githubusercontent.com/nextdns/ddns-domains/main/suffixes
  3 |     100% |   0% |      0% |       4 | black.list.dyndns
```
#### HOSTER
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/hoster-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/hoster-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/hoster-removed-dead.txt)
```
1795 (100%) included | 0 (0%) removed | 0 (0%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% |    1771 | https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Free
  2 |     100% |   0% |      0% |      51 | black.list.hoster
```
---
#### ANTI.PIRACY
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/anti.piracy-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/anti.piracy-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/anti.piracy-removed-dead.txt)
```
10250 (100%) included | 9 (0%) removed | 23 (0%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% |       5 | https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/dht-bootstrap-nodes
  2 |      98% |   0% |      2% |     110 | https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/file-hosting
  3 |     100% |   0% |      0% |      41 | https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/proxies
  4 |     100% |   0% |      0% |      65 | https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/streaming-audio
  5 |     100% |   0% |      0% |    1085 | https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/streaming-video
  6 |     100% |   0% |      0% |      31 | https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/torrent-clients
  7 |     100% |   0% |      0% |     351 | https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/torrent-trackers
  8 |     100% |   0% |      0% |    1266 | https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/torrent-websites
  9 |     100% |   0% |      0% |      12 | https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/usenet
 10 |     100% |   0% |      0% |     133 | https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/warez
 11 |     100% |   0% |      0% |    2134 | https://raw.githubusercontent.com/blocklistproject/Lists/master/piracy.txt
 12 |     100% |   0% |      0% |     701 | https://raw.githubusercontent.com/SM443/Pi-hole-Torrent-Blocklist/main/all-torrent-trackres.txt
 13 |     100% |   0% |      0% |    3814 | https://raw.githubusercontent.com/SM443/Pi-hole-Torrent-Blocklist/main/all-torrent-websites.txt
 14 |      99% |   1% |      0% |    1088 | whitelist-torrent_tracker.txt
 15 |     100% |   0% |      0% |    2128 | https://raw.githubusercontent.com/Entree3k/Pi-hole-Block-List/master/Piracy%20List
 16 |     100% |   0% |      0% |     805 | https://raw.githubusercontent.com/SM443/BDIX-Piracy-Blocklist/main/bdix_piracy_websites_only-domains.txt
 17 |      99% |   0% |      1% |      68 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/AndroidApps.md
 18 |      96% |   0% |      4% |      46 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/AudioBooks.md
 19 |      99% |   0% |      1% |     121 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/eBooks.md
 20 |      99% |   0% |      1% |     104 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Games.md
 21 |      98% |   0% |      2% |      53 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/iOSApps.md
 22 |      97% |   0% |      3% |      29 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Keygens.md
 23 |      98% |   0% |      2% |      47 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Lists.md
 24 |      99% |   0% |      1% |      71 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/macOsSoftware.md
 25 |      98% |   0% |      2% |      50 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/MangaAnime.md
 26 |      99% |   0% |      1% |     168 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Movies.md
 27 |     100% |   0% |      0% |     207 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Movies_English.md
 28 |      99% |   0% |      1% |      86 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Movies_Other.md
 29 |      99% |   0% |      1% |     123 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Music.md
 30 |      96% |   0% |      4% |      23 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/NavigationSoftware.md
 31 |      97% |   0% |      3% |      38 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Nfo.md
 32 |      97% |   0% |      3% |      38 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/NulledScripts.md
 33 |      50% |   0% |     50% |       2 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/SearchEngines.md
 34 |      98% |   1% |      1% |     193 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Series.md
 35 |     100% |   0% |      0% |     236 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Series_English.md
 36 |      99% |   0% |      1% |      81 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Series_Other.md
 37 |      99% |   0% |      1% |     104 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/SportStreams.md
 38 |      99% |   0% |      1% |      98 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Torrents.md
 39 |      94% |   0% |      6% |      18 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/TvSenders.md
 40 |      96% |   0% |      4% |      26 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/UsenetForums.md
 41 |      97% |   0% |      3% |      32 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/UsenetSearchEngines.md
 42 |      99% |   0% |      1% |     104 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Warez.md
 43 |      99% |   0% |      1% |      78 | https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/WindowsSoftware.md
 44 |     100% |   0% |      0% |     142 | black.list.antipiracy
```
---
### Subdomains
*The matching/missing subdomains for domain and hosts lists are extracted from the following lists:*
```
CISCO Umbrella 1M Toplist
TRANCO 1M Toplist
https://raw.githubusercontent.com/jawz101/subdomain_blocklists/main/hosts.txt
https://www.github.developerdan.com/hosts/lists/ads-and-tracking-extended.txt
```
---
### All known sources
```
https://abp.oisd.nl
https://abp.oisd.nl/basic
https://abp.oisd.nl/extra/
https://abp.oisd.nl/small
https://adaway.org/hosts.txt
https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt
https://adguardteam.github.io/HostlistsRegistry/assets/filter_25.txt
https://adguardteam.github.io/HostlistsRegistry/assets/filter_3.txt
https://anti-ad.net/adguard.txt
https://anti-ad.net/easylist.txt
https://assets.windscribe.com/custom_blocklists/clickbait.txt
https://azorult-tracker.net/api/list/domain?format=plain
https://big.oisd.nl
https://big.oisd.nl/
https://big.oisd.nl/domains
https://blocklistproject.github.io/Lists/adguard/abuse-ags.txt
https://blocklistproject.github.io/Lists/adguard/fraud-ags.txt
https://blocklistproject.github.io/Lists/adguard/malware-ags.txt
https://blocklistproject.github.io/Lists/adguard/phishing-ags.txt
https://blocklistproject.github.io/Lists/adguard/ransomware-ags.txt
https://blocklistproject.github.io/Lists/adguard/scam-ags.txt
https://cert-agid.gov.it/download/log4shell-iocs-raw-domain.txt
https://data.netlab.360.com/feeds/dga/chinad.txt
https://data.netlab.360.com/feeds/dga/conficker.txt
https://data.netlab.360.com/feeds/dga/cryptolocker.txt
https://data.netlab.360.com/feeds/dga/gameover.txt
https://data.netlab.360.com/feeds/dga/locky.txt
https://data.netlab.360.com/feeds/dga/necurs.txt
https://data.netlab.360.com/feeds/dga/suppobox.txt
https://data.netlab.360.com/feeds/dga/tofsee.txt
https://data.netlab.360.com/feeds/dga/virut.txt
https://dbl.oisd.nl
https://dbl.oisd.nl/basic
https://dbl.oisd.nl/extra/
https://dbl.oisd.nl/small
https://dbl.oisd.nl/small/
https://dl.red.flag.domains/red.flag.domains_fr.txt
https://easylist-downloads.adblockplus.org/abp-filters-anti-cv.txt
https://easylist-downloads.adblockplus.org/advblock.txt
https://easylist-downloads.adblockplus.org/antiadblockfilters.txt
https://easylist-downloads.adblockplus.org/easylistchina.txt
https://easylist-downloads.adblockplus.org/easylistdutch.txt
https://easylist-downloads.adblockplus.org/easylistgermany.txt
https://easylist-downloads.adblockplus.org/easylistitaly.txt
https://easylist-downloads.adblockplus.org/easylistpolish.txt
https://easylist-downloads.adblockplus.org/easylistportuguese.txt
https://easylist-downloads.adblockplus.org/easylistspanish.txt
https://easylist-downloads.adblockplus.org/easylist.txt
https://easylist-downloads.adblockplus.org/easyprivacy.txt
https://easylist-downloads.adblockplus.org/indianlist.txt
https://easylist-downloads.adblockplus.org/koreanlist.txt
https://easylist-downloads.adblockplus.org/Liste_AR.txt
https://easylist-downloads.adblockplus.org/liste_fr.txt
https://easylist-downloads.adblockplus.org/ruadlist.txt
https://easylist.to/easylist/easylist.txt
https://easylist.to/easylist/easyprivacy.txt
https://easylist.to/easylist/fanboy-social.txt
https://fanboy.co.nz/enhancedstats.txt
https://filters.adavoid.org/ultimate-ad-filter.txt
https://filters.adavoid.org/ultimate-privacy-filter.txt
https://github.com/blocklistproject/Lists/blob/master/piracy.txt
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/AndroidApps.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/AudioBooks.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/CryptoPlaces.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Documentations.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/eBooks.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Games.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/iOSApps.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Keygens.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Lists.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/macOsSoftware.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/MangaAnime.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Movies_English.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Movies.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Movies_Other.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Music.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/NavigationSoftware.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Nfo.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/NulledScripts.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/PortableApps.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/ScienceLibaries.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/SearchEngines.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Series_English.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Series.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Series_Other.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/SportStreams.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Torrents.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/TvSenders.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/UsenetForums.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/UsenetSearchEngines.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/Warez.md
https://github.com/SeppPenner/awesome-german-piracy/blob/master/Pages/WindowsSoftware.md
https://github.com/T145/black-mirror/releases/download/latest/white_domain.txt
https://github.com/yourduskquibbles/webannoyances/blob/master/ultralist.txt
https://gitlab.com/cmiksche/blacklists/-/raw/master/hosts
https://gitlab.com/KevinThomas0/cryptoscamdb-lists/-/raw/master/cryptoscamdb-blocklist.txt
https://gitlab.com/nitrohorse/government-malware-domains-blocklist/-/raw/master/domains.txt
https://gitlab.com/quidsup/notrack-annoyance-blocklist/-/raw/master/notrack-annoyance.txt
https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-blocklist.txt
https://gitlab.com/quidsup/notrack-blocklists/-/raw/master/notrack-malware.txt
https://gitlab.com/ZeroDot1/CoinBlockerLists/raw/master/hosts_browser
https://gitlab.com/ZeroDot1/CoinBlockerLists/-/raw/master/list.txt
https://hblock.molinero.dev/hosts_domains.txt
https://hole.cert.pl/domains/domains_hosts.txt
https://hostfiles.frogeye.fr/firstparty-trackers-hosts.txt
https://hostfiles.frogeye.fr/multiparty-trackers-hosts.txt
https://hosts.tweedge.net/malicious.txt
https://hosts.ubuntu101.co.za/domains.list
https://joewein.net/dl/bl/dom-bl-base.txt
https://joewein.net/dl/bl/dom-bl.txt
https://kriskintel.com/feeds/ktip_covid_domains.txt
https://kriskintel.com/feeds/ktip_malicious_domains.txt
https://kriskintel.com/feeds/ktip_ransomware_feeds.txt
https://malware-filter.gitlab.io/malware-filter/phishing-filter-hosts.txt
https://malware-filter.gitlab.io/malware-filter/pup-filter-hosts.txt
https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-hosts-online.txt
https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-hosts.txt
https://malware-filter.gitlab.io/malware-filter/vn-badsite-filter-hosts.txt
https://mkb2091.github.io/blockconvert/output/adblock.txt
https://nocdn.threat-list.com/0/domains.txt
https://notabug.org/latvian-list/adblock-latvian/raw/master/lists/latvian-list.txt
https://o0.pages.dev/Lite/adblock.txt
https://o0.pages.dev/Lite/hosts.txt
https://o0.pages.dev/mini/adblock.txt
https://o0.pages.dev/mini/hosts.txt
https://o0.pages.dev/Pro/adblock.txt
https://o0.pages.dev/Pro/hosts.txt
https://o0.pages.dev/Xtra/adblock.txt
https://o0.pages.dev/Xtra/hosts.txt
https://orca.pet/notonmyshift/domains.txt
https://osint.digitalside.it/Threat-Intel/lists/latestdomains.txt
https://paulgb.github.io/BarbBlock/blacklists/hosts-file.txt
https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&mimetype=plaintext&useip=0.0.0.0
https://phishing.army/download/phishing_army_blocklist_extended.txt
https://phishing.army/download/phishing_army_blocklist.txt
https://raw.github.com/tomasko126/easylistczechandslovak/master/filters.txt
https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/src/advert/adservers.txt
https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/src/advert/thirdparty.txt
https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo.txt
https://raw.githubusercontent.com/abpvn/abpvn/master/filter/abpvn.txt
https://raw.githubusercontent.com/AdAway/adaway.github.io/master/hosts.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/adservers_firstparty.tx
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/adservers_firstparty.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/adservers.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/cryptominers.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/foreign.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/ChineseFilter/sections/adservers.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/DutchFilter/sections/adservers_firstparty.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/DutchFilter/sections/adservers.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/FrenchFilter/sections/adservers.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/GermanFilter/sections/adservers.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/JapaneseFilter/sections/adservers.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/MobileFilter/sections/adservers.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/adservers_firstparty.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/adservers.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/news_exchange.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpanishFilter/sections/adservers.tx
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpanishFilter/sections/adservers.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/mobile.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers_firstparty.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/TurkishFilter/sections/adservers_firstparty.txt
https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/TurkishFilter/sections/adservers.txt
https://raw.githubusercontent.com/AdguardTeam/AdGuardSDNSFilter/master/Filters/rules.txt
https://raw.githubusercontent.com/AdguardTeam/cname-trackers/master/combined_disguised_trackers_justdomains.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_11_Mobile/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_13_Turkish/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_16_French/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_18_Annoyances_Cookies/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_19_Annoyances_Popups/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_1_Russian/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_21_Annoyances_Other/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_22_Annoyances_Widgets/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_4_Social/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_6_German/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_7_Japanese/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_8_Dutch/filter.txt
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_9_Spanish/filter.txt
https://raw.githubusercontent.com/AdguardTeam/HostlistsRegistry/main/filters/security/filter_10_ScamBlocklistByDurableNapkin/filter.txt
https://raw.githubusercontent.com/AdguardTeam/HostlistsRegistry/main/filters/security/filter_11_MaliciousURLBlocklist/filter.txt
https://raw.githubusercontent.com/AdguardTeam/HostlistsRegistry/main/filters/security/filter_30_PhishingURLBlocklist/filter.txt
https://raw.githubusercontent.com/AdroitAdorKhan/antipopads-re/master/formats/domains.txt
https://raw.githubusercontent.com/AmnestyTech/investigations/master/2021-07-18_nso/domains.txt
https://raw.githubusercontent.com/AmnestyTech/investigations/master/2021-10-07_donot/domains.txt
https://raw.githubusercontent.com/AmnestyTech/investigations/master/2021-12-16_cytrox/domains.txt
https://raw.githubusercontent.com/anudeepND/blacklist/master/adservers.txt
https://raw.githubusercontent.com/AssoEchap/stalkerware-indicators/master/generated/hosts
https://raw.githubusercontent.com/AssoEchap/stalkerware-indicators/master/generated/hosts_full
https://raw.githubusercontent.com/AssoEchap/stalkerware-indicators/master/quad9_blocklist.txt
https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/adblock.txt
https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/hosts.txt
https://raw.githubusercontent.com/badmojr/1Hosts/master/mini/adblock.txt
https://raw.githubusercontent.com/badmojr/1Hosts/master/mini/hosts.txt
https://raw.githubusercontent.com/badmojr/1Hosts/master/Pro/adblock.txt
https://raw.githubusercontent.com/badmojr/1Hosts/master/Pro/hosts.txt
https://raw.githubusercontent.com/badmojr/1Hosts/master/Xtra/adblock.txt
https://raw.githubusercontent.com/badmojr/1Hosts/master/Xtra/hosts.txt
https://raw.githubusercontent.com/bigdargon/hostsVN/master/extensions/threat/hosts
https://raw.githubusercontent.com/bigdargon/hostsVN/master/filters/adservers.tx
https://raw.githubusercontent.com/bigdargon/hostsVN/master/filters/adservers.txt
https://raw.githubusercontent.com/bigdargon/hostsVN/master/hosts
https://raw.githubusercontent.com/bigdargon/hostsVN/master/option/hosts-VN
https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts
https://raw.githubusercontent.com/blocklistproject/Lists/master/piracy.txt
https://raw.githubusercontent.com/bongochong/CombinedPrivacyBlockLists/master/newhosts-final.hosts
https://raw.githubusercontent.com/bongochong/CombinedPrivacyBlockLists/master/NoFormatting/MD-ID-Fork.txt
https://raw.githubusercontent.com/Cats-Team/AdRules/main/ad-domains.txt
https://raw.githubusercontent.com/Cats-Team/AdRules/main/dns.txt
https://raw.githubusercontent.com/cbuijs/shallalist/master/adv/domains
https://raw.githubusercontent.com/cbuijs/shallalist/master/tracker/domains
https://raw.githubusercontent.com/cbuijs/ut1/master/ads/domains
https://raw.githubusercontent.com/CipherOps/AdList/main/Blocklist
https://raw.githubusercontent.com/craiu/iocs/main/log4shell/log4j_blocklist.txt
https://raw.githubusercontent.com/craiu/mobiletrackers/master/list.txt
https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt
https://raw.githubusercontent.com/d3ward/toolz/master/src/d3host.txt
https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareHosts.txt
https://raw.githubusercontent.com/DandelionSprout/adfilt/master/NorwegianExperimentalList%20alternate%20versions/NordicFiltersAdGuardHome.txt
https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Other%20domains%20versions/BrowseWebsitesWithoutLoggingInAGH.txt
https://raw.githubusercontent.com/davidonzo/Threat-Intel/master/lists/latestdomains.piHole.txt
https://raw.githubusercontent.com/Dogino/Discord-Phishing-URLs/main/pihole-phishing-adlist.txt
https://raw.githubusercontent.com/DRSDavidSoft/additional-hosts/master/domains/blacklist/adservers-and-trackers.txt
https://raw.githubusercontent.com/DRSDavidSoft/additional-hosts/master/domains/blacklist/fake-domains.txt
https://raw.githubusercontent.com/durablenapkin/block/master/avast.txt
https://raw.githubusercontent.com/durablenapkin/block/master/luminati.txt
https://raw.githubusercontent.com/durablenapkin/block/master/streaming.txt
https://raw.githubusercontent.com/durablenapkin/block/master/tvstream.txt
https://raw.githubusercontent.com/durablenapkin/scamblocklist/master/hosts.txt
https://raw.githubusercontent.com/easylist/easylistdutch/master/easylistdutch/block_third_party_server.txt
https://raw.githubusercontent.com/easylist/easylistgermany/master/easylistgermany/easylistgermany_adservers.txt
https://raw.githubusercontent.com/easylist/EasyListHebrew/master/EasyListHebrew.txt
https://raw.githubusercontent.com/easylist/easylistitaly/master/easylistitaly/easylistitaly_adservers.txt
https://raw.githubusercontent.com/easylist/easylist/master/easylist/easylist_adservers.txt
https://raw.githubusercontent.com/easylist/easylist/master/easylist/easylist_thirdparty.txt
https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_specific_cname.txt
https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_thirdparty_international.txt
https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_thirdparty.txt
https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_trackingservers_international.txt
https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_trackingservers.txt
https://raw.githubusercontent.com/EasyList-Lithuania/easylist_lithuania/master/easylistlithuania.txt
https://raw.githubusercontent.com/easylist-thailand/easylist-thailand/master/subscription/easylist-thailand.txt
https://raw.githubusercontent.com/elliotwutingfeng/GlobalAntiScamOrg-blocklist/main/global-anti-scam-org-scam-urls-pihole.txt
https://raw.githubusercontent.com/elliotwutingfeng/Inversion-DNSBL-Blocklists/main/Google_hostnames_light.txt
https://raw.githubusercontent.com/elliotwutingfeng/Inversion-DNSBL-Blocklists/main/Google_hostnames.txt
https://raw.githubusercontent.com/Entree3k/Pi-hole-Block-List/master/Piracy%20List
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts
https://raw.githubusercontent.com/gioxx/xfiles/master/filtri.txt
https://raw.githubusercontent.com/guardicore/labs_campaigns/master/Autodiscover/autodiscover-tlds.txt
https://raw.githubusercontent.com/HexxiumCreations/threat-list/gh-pages/hosts.txt
https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt
https://raw.githubusercontent.com/hpthreatresearch/iocs/main/IcedID/domains.txt
https://raw.githubusercontent.com/hpthreatresearch/iocs/main/TA505/domains.txt
https://raw.githubusercontent.com/hpthreatresearch/iocs/main/TA551/domains.txt
https://raw.githubusercontent.com/hufilter/hufilter/master/hufilter.txt
https://raw.githubusercontent.com/iam-py-test/my_filters_001/main/Alternative%20list%20formats/antimalware_domains.txt
https://raw.githubusercontent.com/iam-py-test/vxvault_filter/main/domains_file.txt
https://raw.githubusercontent.com/ihgalis/pihole_collection/master/Sinking_Yachts_Phishing
https://raw.githubusercontent.com/infinitytec/blocklists/master/ads-and-trackers.txt
https://raw.githubusercontent.com/infinitytec/blocklists/master/scams-and-phishing.txt
https://raw.githubusercontent.com/jawz101/subdomain_blocklists/main/hosts.txt
https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts
https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Hosts/GoodbyeAds.txt
https://raw.githubusercontent.com/jkrejcha/AdmiraList/master/AdmiraList.txt
https://raw.githubusercontent.com/Kees1958/W3C_annual_most_used_survey_blocklist/master/EU_US%2Bmost_used_ad_and_tracking_networks.txt
https://raw.githubusercontent.com/Laicure/hosts/master/shithosts
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/adback-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/adkeeper-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/admaven-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/admeasures-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/bt-contentza-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/cdn-filter-list.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/combined-filters.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/cryptomining-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/fanboy-social-no-cosmetic.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/freecounterstat-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/getadmiral-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/hilltopads-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/istripper-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/kitty-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/macupload-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/malware-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/popads-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/propellerads-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/toradvertising-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/ubo-filters.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/unknown-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/videoadex-domains.txt
https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/volumedata-domains.txt
https://raw.githubusercontent.com/lassekongo83/Frellwits-filter-lists/master/Frellwits-Swedish-Hosts-File.txt
https://raw.githubusercontent.com/logroid/adaway-hosts/master/hosts.txt
https://raw.githubusercontent.com/manic-code/Emerging-Malicious-Domain-Blocklist/main/hosts.txt
https://raw.githubusercontent.com/marco-acorte/antispam-it/main/antispam-it.txt
https://raw.githubusercontent.com/marktron/fakenews/master/fakenews
https://raw.githubusercontent.com/MasterKia/PersianBlocker/main/PersianBlockerHosts.txt
https://raw.githubusercontent.com/matomo-org/referrer-spam-blacklist/master/spammers.txt
https://raw.githubusercontent.com/metamask/eth-phishing-detect/master/src/hosts.txt
https://raw.githubusercontent.com/migueldemoura/ublock-umatrix-rulesets/master/Hosts/ads-tracking
https://raw.githubusercontent.com/miriquidi/dns-block-lists/main/block.txt
https://raw.githubusercontent.com/mitchellkrogza/Badd-Boyz-Hosts/master/hosts
https://raw.githubusercontent.com/mitchellkrogza/Phishing.Database/master/phishing-domains-ACTIVE.txt
https://raw.githubusercontent.com/mitchellkrogza/Phishing.Database/master/phishing-domains-NEW-today.txt
https://raw.githubusercontent.com/mitchellkrogza/The-Big-List-of-Hacked-Malware-Web-Sites/master/hosts
https://raw.githubusercontent.com/nextdns/click-tracking-domains/main/domains
https://raw.githubusercontent.com/nextdns/cname-cloaking-blocklist/master/domains
https://raw.githubusercontent.com/nextdns/ddns-domains/main/suffixes
https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/apple-private-relay
https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/browsers
https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/encrypted-dns
https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/linux
https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/proxies
https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/tor
https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/vpn
https://raw.githubusercontent.com/nextdns/metadata/master/parentalcontrol/bypass-methods
https://raw.githubusercontent.com/nextdns/metadata/master/parentalcontrol/safesearch-not-supported
https://raw.githubusercontent.com/nextdns/metadata/master/security/ddns/suffixes
https://raw.githubusercontent.com/nextdns/metadata/master/security/parked-domains-cname
https://raw.githubusercontent.com/nextdns/no-safesearch/main/domains
https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/dht-bootstrap-nodes
https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/file-hosting
https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/proxies
https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/streaming-audio
https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/streaming-video
https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/torrent-clients
https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/torrent-trackers
https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/torrent-websites
https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/usenet
https://raw.githubusercontent.com/nextdns/piracy-blocklists/master/warez
https://raw.githubusercontent.com/notracking/hosts-blocklists/master/adblock/adblock.txt
https://raw.githubusercontent.com/notracking/hosts-blocklists/master/dnscrypt-proxy/dnscrypt-proxy.blacklist.txt
https://raw.githubusercontent.com/notracking/hosts-blocklists/master/domains.txt
https://raw.githubusercontent.com/notracking/hosts-blocklists/master/hostnames.txt
https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/cryptojacking/domains
https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/doh/domains
https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/malware/domains
https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/phishing/domains
https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/vpn/domains
https://raw.githubusercontent.com/oneoffdallas/dohservers/master/list.txt
https://raw.githubusercontent.com/ookangzheng/blahdns/master/hosts/blacklist.txt
https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/AmazonFireTV.txt
https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/android-tracking.txt
https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV.txt
https://raw.githubusercontent.com/piperun/iploggerfilter/master/filterlist
https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADomains.txt
https://raw.githubusercontent.com/Potterli20/file/main/ad-hosts/hosts
https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-domains.txt
https://raw.githubusercontent.com/realodix/AdBlockID/master/src/adservers.adfl
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-amnenstytech.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-certagid.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-certego.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-citizenlabs.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-csirt.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-cyble.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-drweb.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-eset.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-kaspersky.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-main.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-malware-traffic.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-matomo.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-orangecyber.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-orangelog4shell.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-personal.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-sentinelone.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-sophos.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-tag.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-unit42-playbook.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-unit42-silverterrier.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-yoroi.txt
https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-zscaler.txt
https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Cryptocurrency
https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Dynamic
https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Free
https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Malware
https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Risk
https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Scam
https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Tunnels
https://raw.githubusercontent.com/shreyasminocha/shady-hosts/main/hosts
https://raw.githubusercontent.com/sjhgvr/oisd/dda0cf5e3b68fcd25c8363242e3854c465cb36cf/abp_full.txt
https://raw.githubusercontent.com/sjhgvr/oisd/dda0cf5e3b68fcd25c8363242e3854c465cb36cf/dbl_full.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/abp_basic.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/abp_big.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/abp_extra.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/abp_full.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/abp_nsfw.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/abp_small.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/dbl_basic.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/dbl_big.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/dbl_extra.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/dbl_full.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/dbl_nsfw.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/dbl_small.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/domains_big.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/domains_small.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/oisd_big.txt
https://raw.githubusercontent.com/sjhgvr/oisd/main/oisd_small.txt
https://raw.githubusercontent.com/SM443/BDIX-Piracy-Blocklist/main/bdix_piracy_websites_only-domains.txt
https://raw.githubusercontent.com/SM443/Pi-hole-Torrent-Blocklist/main/all-torrent-trackres.txt
https://raw.githubusercontent.com/SM443/Pi-hole-Torrent-Blocklist/main/all-torrent-websites.txt
https://raw.githubusercontent.com/smed79/blacklist/master/hosts.txt
https://raw.githubusercontent.com/stamparm/aux/master/maltrail-malware-domains.txt
https://raw.githubusercontent.com/stamparm/blackbook/master/blackbook.txt
https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts
https://raw.githubusercontent.com/symbuzzer/Turkish-Ad-Hosts/main/hosts
https://raw.githubusercontent.com/SystemJargon/blocklists/main/lists/categories/dns-dot-quic-doh/TheGreaterWall-dns-dot.txt
https://raw.githubusercontent.com/SystemJargon/blocklists/main/lists/threats/aggregated-threats-1.txt
https://raw.githubusercontent.com/SystemJargon/blocklists/main/lists/threats/bad-image-icon-domains.txt
https://raw.githubusercontent.com/SystemJargon/blocklists/main/lists/threats/observed-bad-domains-1.txt
https://raw.githubusercontent.com/SystemJargon/blocklists/main/lists/threats/threats-june-2022.txt
https://raw.githubusercontent.com/SystemJargon/blocklists/main/lists/threats/threats.txt
https://raw.githubusercontent.com/Th3M3/blocklists/master/malware.list
https://raw.githubusercontent.com/tiuxo/hosts/master/ads
https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/annoyances.txt
https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/badware.txt
https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2020.txt
https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2021.txt
https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2022.txt
https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2023.txt
https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters.txt
https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/privacy.txt
https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/resource-abuse.txt
https://raw.githubusercontent.com/Ultimate-Hosts-Blacklist/Ultimate.Hosts.Blacklist/master/domains/domains0.list
https://raw.githubusercontent.com/Ultimate-Hosts-Blacklist/Ultimate.Hosts.Blacklist/master/domains/domains1.list
https://raw.githubusercontent.com/Ultimate-Hosts-Blacklist/Ultimate.Hosts.Blacklist/master/domains/domains2.list
https://raw.githubusercontent.com/uniartisan/adblock_list/master/adblock_lite.txt
https://raw.githubusercontent.com/uniartisan/adblock_list/master/adblock_plus.txt
https://raw.githubusercontent.com/uniartisan/adblock_list/master/adblock_privacy.txt
https://raw.githubusercontent.com/uniartisan/adblock_list/master/adblock.txt
https://raw.githubusercontent.com/VeleSila/yhosts/master/hosts
https://raw.githubusercontent.com/xinggsf/Adblock-Plus-Rule/master/rule.txt
https://raw.githubusercontent.com/yokoffing/filterlists/main/annoyance_list.txt
https://raw.githubusercontent.com/yokoffing/filterlists/main/privacy_essentials.txt
https://raw.githubusercontent.com/yourduskquibbles/webannoyances/master/ultralist.txt
https://raw.githubusercontent.com/yous/YousList/master/youslist.txt
https://raw.githubusercontent.com/z44499783/ChinaList2.0/master/ChinaList2.0.txt
https://rescure.me/covid.txt
https://rescure.me/rescure_domain_blacklist.txt
https://secure.fanboy.co.nz/fanboy-annoyance.txt
https://secure.fanboy.co.nz/fanboy-cookiemonster.txt
https://secure.fanboy.co.nz/fanboy-social.txt
https://small.oisd.nl
https://small.oisd.nl/
https://small.oisd.nl/domains
https://smokingwheels.github.io/Pi-hole/multiedit
https://someonewhocares.org/hosts/hosts
https://someonewhocares.org/hosts/zero/hosts
https://stanev.org/abp/adblock_bg.txt
http://stanev.org/abp/adblock_bg.txt
https://threatfox.abuse.ch/downloads/hostfile
https://threatview.io/Downloads/DOMAIN-High-Confidence-Feed.txt
https://threatview.io/Downloads/DOMAIN-High-Confidence-Feed.txttors/master/generated/hosts_full
https://urlhaus.abuse.ch/downloads/hostfile
https://v.firebog.net/hosts/Admiral.txt
https://v.firebog.net/hosts/static/w3kbl.txt
https://winhelp2002.mvps.org/hosts.txt
https://www.botvrij.eu/data/ioclist.domain.raw
https://www.botvrij.eu/data/ioclist.hostname.raw
https://www.github.developerdan.com/hosts/lists/ads-and-tracking-extended.txt
https://www.stopforumspam.com/downloads/toxic_domains_whole.txt
https://www.void.gr/kargig/void-gr-filters.txt
https://www.zoso.ro/pages/rolist.txt
```
---

### Credits
*A huge thank you to the following list maintainers of the sources used, alphabetical order:*
         
*abpindo, abpvn, abuse.ch, adaway, adguardteam, adroitadorkhan, amnestytech, anti-ad, anudeepnd, assoechap, azorult-tracker.net, badmojr, barbblock, bigdargon, bkrucarci, blahdns, bongochong, botvrij.eu, cats-team, cbuijs, cert-agid.gov.it, cipherops, cmiksche, craiu, d3ward, dandelionsprout, davidonzo, developerdan, digitalside.it, dogino, drsdavidsoft, durablenapkin, easylist, easylist-lithuania, easylist-thailand, elliotwutingfeng, fademind, fanboy, firebog.net, frogeye.fr, gioxx, guardicore, hblock, hexxiumcreations, hole.cert.pl, hoshsadiq, hpthreatresearch, hufilter, iam-py-test, ihgalis, infinitytec, jawz101, jdlingyu, jkrejcha, joewein.net, kargig, kees1958, kevinthomas0, kriskintel.com, laicure, laniksj, lassekongo83, latvian-list, list-kr, logroid, malware-filter, manic-code, marco-acorte, matomo-org, metamask, migueldemoura, mitchellkrogza, molinero.dev, mvps.org, netlab.360, nextdns, nitrohorse, notonmyshift, notracking, oisd.nl, olbat, oneoffdallas, ookangzheng, paulgb, perflyst, phishing.army, piperun, piquark6046, polishfiltersteam, prodaft, quidsup, rescure.me, scafroglia93, shadowwhisperer, shallalist, shreyasminocha, sjhgvr, smed79, someonewhocares.org, stamparm, stanev.org, stevenblack, stopforumspam.com, symbuzzer, systemjargon, t145, th3m3, tiuxo, tweedge, tomasko126, ublockorigin, ultimate-hosts, uniartisan, ut1, velesila, wally3k, yokoffing, yourduskquibbles, yous, yoyo.org, zerodot1, zoso.ro*

---

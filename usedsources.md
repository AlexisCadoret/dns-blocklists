### Sources/Statistics
*Sources used for compiling the block lists (for the individual licenses of the sources, see the source files or source repositories!) :*
#### LIGHT
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/light-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/light-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/light-removed-dead.txt)
```
621877 total unique domains | 595642 (96%) included | 646 (0%) removed | 25589 (4%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% |  100944 | personal.txt
  2 |      64% |   1% |     35% |     141 | personal-wildcard-rules.txt
  3 |     100% |   0% |      0% |  105811 | personal-tif.txt
  4 |     100% |   0% |      0% |    9825 | fake.txt
  5 |      84% |   1% |     15% |    2878 | black.list

For domain and host lists, additionally: matching/missing subdomains (see at the bottom)
```
#### MULTI
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/multi-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/multi-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/multi-removed-dead.txt)
```
1073959 total unique domains | 1008630 (94%) included | 10176 (1%) removed | 55153 (5%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% |  595642 | light.txt
  2 |      96% |   1% |      3% |  102062 | https://o0.pages.dev/Lite/hosts.txt
  3 |      92% |   8% |      0% |   49041 | https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt
  4 |      97% |   2% |      1% |  862782 | oisd.domains.txt

For domain and host lists, additionally: matching/missing subdomains (see at the bottom)
```
#### PRO
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/pro-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/pro-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/pro-removed-dead.txt)
```
1607911 total unique domains | 1286512 (80%) included | 23970 (1%) removed | 297429 (18%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% | 1008630 | multi.txt
  2 |      54% |  34% |     12% |  184020 | https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts
  3 |      75% |  25% |      0% |  415874 | https://raw.githubusercontent.com/notracking/hosts-blocklists/master/dnscrypt-proxy/dnscrypt-proxy.blacklist.txt
  4 |      96% |   1% |      3% |      95 | https://raw.githubusercontent.com/manic-code/Emerging-Malicious-Domain-Blocklist/main/hosts.txt

For domain and host lists, additionally: matching/missing subdomains (see at the bottom)
```
#### PRO.PLUS
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/pro.plus-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/pro.plus-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/pro.plus-removed-dead.txt)
```
1783696 total unique domains | 1421033 (80%) included | 45186 (3%) removed | 317477 (18%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% | 1283610 | pro.txt
  2 |      99% |   0% |      1% |   24407 | pro.plus.extension.domains
  3 |      93% |   1% |      6% |  253006 | https://o0.pages.dev/Pro/hosts.txt
  4 |      54% |  34% |     12% |  184020 | https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts
  5 |      75% |  25% |      0% |  416323 | https://raw.githubusercontent.com/notracking/hosts-blocklists/master/dnscrypt-proxy/dnscrypt-proxy.blacklist.txt
  6 |      97% |   2% |      1% |  862812 | oisd.domains.txt
  7 |      92% |   8% |      0% |   49033 | https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt
  8 |      76% |  23% |      1% |     550 | https://raw.githubusercontent.com/AdguardTeam/AdGuardSDNSFilter/master/Filters/rules.txt
  9 |      89% |   9% |      2% |    1019 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_11_Mobile/filter.txt
 10 |      73% |  27% |      0% |     125 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_13_Turkish/filter.txt
 11 |      80% |  18% |      2% |     191 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt
 12 |      87% |  13% |      0% |    9307 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_16_French/filter.txt
 13 |      97% |   0% |      3% |      36 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_18_Annoyances_Cookies/filter.txt
 14 |      74% |  25% |      1% |     126 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_19_Annoyances_Popups/filter.txt
 15 |      76% |  24% |      0% |     564 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_1_Russian/filter.txt
 16 |     100% |   0% |      0% |       5 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_21_Annoyances_Other/filter.txt
 17 |      89% |  11% |      0% |    8042 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt
 18 |      88% |   8% |      4% |      24 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_22_Annoyances_Widgets/filter.txt
 19 |      98% |   2% |      0% |   25414 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt
 20 |      97% |   2% |      1% |   24337 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt
 21 |      50% |  50% |      0% |       2 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_4_Social/filter.txt
 22 |      86% |  14% |      0% |      56 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_6_German/filter.txt
 23 |      99% |   1% |      0% |     155 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_7_Japanese/filter.txt
 24 |      95% |   5% |      0% |      21 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_8_Dutch/filter.txt
 25 |      74% |  26% |      0% |      85 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_9_Spanish/filter.txt
 26 |      95% |   5% |      0% |    1430 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/adservers.txt
 27 |      97% |   3% |      0% |     196 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/adservers_firstparty.txt
 28 |      64% |  36% |      0% |     130 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/cryptominers.txt
 29 |     100% |   0% |      0% |      34 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/foreign.txt
 30 |      57% |  43% |      0% |     304 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/ChineseFilter/sections/adservers.txt
 31 |     100% |   0% |      0% |       2 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/DutchFilter/sections/adservers.txt
 32 |     100% |   0% |      0% |       5 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/DutchFilter/sections/adservers_firstparty.txt
 33 |      50% |  50% |      0% |      10 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/FrenchFilter/sections/adservers.txt
 34 |      94% |   3% |      3% |      33 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/GermanFilter/sections/adservers.txt
 35 |      97% |   1% |      2% |     321 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/JapaneseFilter/sections/adservers.txt
 36 |      89% |   9% |      2% |    1048 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/MobileFilter/sections/adservers.txt
 37 |      64% |  36% |      0% |    3707 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/adservers.txt
 38 |      69% |  31% |      0% |     161 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/adservers_firstparty.txt
 39 |      64% |  36% |      0% |      56 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/news_exchange.txt
 40 |      78% |  20% |      2% |     172 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpanishFilter/sections/adservers.txt
 41 |      87% |   9% |      4% |     646 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/mobile.txt
 42 |      94% |   3% |      3% |    4802 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers.txt
 43 |      84% |  14% |      2% |    2200 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers_firstparty.txt
 44 |      81% |  18% |      1% |     280 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/TurkishFilter/sections/adservers.txt
 45 |      62% |  38% |      0% |      61 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/TurkishFilter/sections/adservers_firstparty.txt
 46 |      98% |   2% |      0% |   21128 | https://easylist-downloads.adblockplus.org/easylist.txt
 47 |      94% |   1% |      5% |   15288 | https://easylist-downloads.adblockplus.org/easyprivacy.txt
 48 |      97% |   2% |      1% |      96 | https://easylist-downloads.adblockplus.org/antiadblockfilters.txt
 49 |      77% |  23% |      0% |      13 | https://easylist-downloads.adblockplus.org/Liste_AR.txt
 50 |      47% |  53% |      0% |    1928 | https://easylist-downloads.adblockplus.org/advblock.txt
 51 |      89% |  11% |      0% |    7987 | https://easylist-downloads.adblockplus.org/easylistchina.txt
 52 |      94% |   6% |      0% |      16 | https://easylist-downloads.adblockplus.org/easylistdutch.txt
 53 |      87% |  13% |      0% |      40 | https://easylist-downloads.adblockplus.org/easylistgermany.txt
 54 |      91% |   7% |      2% |      46 | https://easylist-downloads.adblockplus.org/easylistitaly.txt
 55 |     100% |   0% |      0% |       3 | https://easylist-downloads.adblockplus.org/easylistpolish.txt
 56 |     100% |   0% |      0% |      14 | https://easylist-downloads.adblockplus.org/easylistportuguese.txt
 57 |     100% |   0% |      0% |       7 | https://easylist-downloads.adblockplus.org/easylistspanish.txt
 58 |     100% |   0% |      0% |       3 | https://easylist-downloads.adblockplus.org/indianlist.txt
 59 |     100% |   0% |      0% |       3 | https://easylist-downloads.adblockplus.org/koreanlist.txt
 60 |      87% |  13% |      0% |    9302 | https://easylist-downloads.adblockplus.org/liste_fr.txt
 61 |      47% |  53% |      0% |    1928 | https://easylist-downloads.adblockplus.org/ruadlist.txt
 62 |      63% |  37% |      0% |      19 | https://fanboy.co.nz/enhancedstats.txt
 63 |      60% |  40% |      0% |      15 | https://notabug.org/latvian-list/adblock-latvian/raw/master/lists/latvian-list.txt
 64 |      92% |   8% |      0% |      24 | https://raw.github.com/tomasko126/easylistczechandslovak/master/filters.txt
 65 |      39% |  61% |      0% |      38 | https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo.txt
 66 |     100% |   0% |      0% |       9 | https://raw.githubusercontent.com/EasyList-Lithuania/easylist_lithuania/master/easylistlithuania.txt
 67 |     100% |   0% |      0% |      68 | https://raw.githubusercontent.com/abpvn/abpvn/master/filter/abpvn.txt
 68 |      89% |  10% |      1% |     617 | https://raw.githubusercontent.com/easylist-thailand/easylist-thailand/master/subscription/easylist-thailand.txt
 69 |      71% |  29% |      0% |      31 | https://raw.githubusercontent.com/easylist/EasyListHebrew/master/EasyListHebrew.txt
 70 |      89% |  11% |      0% |      53 | https://raw.githubusercontent.com/hufilter/hufilter/master/hufilter.txt
 71 |      94% |   5% |      1% |      98 | https://raw.githubusercontent.com/yous/YousList/master/youslist.txt
 72 |      97% |   0% |      3% |     179 | https://secure.fanboy.co.nz/fanboy-annoyance.txt
 73 |      96% |   0% |      4% |     140 | https://secure.fanboy.co.nz/fanboy-cookiemonster.txt
 74 |     100% |   0% |      0% |       4 | https://secure.fanboy.co.nz/fanboy-social.txt
 75 |     100% |   0% |      0% |       4 | https://stanev.org/abp/adblock_bg.txt
 76 |      77% |  23% |      0% |      30 | https://www.void.gr/kargig/void-gr-filters.txt
 77 |      84% |  10% |      6% |     117 | https://www.zoso.ro/pages/rolist.txt
 78 |      66% |  34% |      0% |     261 | https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/src/advert/adservers.txt
 79 |      56% |  44% |      0% |      18 | https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/src/advert/thirdparty.txt
 80 |      98% |   2% |      0% |   21819 | https://raw.githubusercontent.com/easylist/easylist/master/easylist/easylist_adservers.txt
 81 |     100% |   0% |      0% |     714 | https://raw.githubusercontent.com/easylist/easylist/master/easylist/easylist_thirdparty.txt
 82 |      97% |   0% |      3% |    1267 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_thirdparty.txt
 83 |      98% |   0% |      2% |     480 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_thirdparty_international.txt
 84 |      96% |   0% |      4% |    4435 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_trackingservers.txt
 85 |      96% |   0% |      4% |     927 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_trackingservers_international.txt
 86 |      87% |   4% |      9% |      23 | https://raw.githubusercontent.com/easylist/easylistdutch/master/easylistdutch/block_third_party_server.txt
 87 |      93% |   6% |      1% |     282 | https://raw.githubusercontent.com/easylist/easylistgermany/master/easylistgermany/easylistgermany_adservers.txt
 88 |      95% |   5% |      0% |     134 | https://raw.githubusercontent.com/easylist/easylistitaly/master/easylistitaly/easylistitaly_adservers.txt
 89 |      86% |  10% |      4% |    1046 | https://raw.githubusercontent.com/lassekongo83/Frellwits-filter-lists/master/Frellwits-Swedish-Hosts-File.txt
 90 |      93% |   4% |      3% |      71 | https://raw.githubusercontent.com/realodix/AdBlockID/master/src/adservers.adfl
 91 |      95% |   3% |      2% |     314 | https://raw.githubusercontent.com/DandelionSprout/adfilt/master/NorwegianExperimentalList%20alternate%20versions/NordicFiltersAdGuardHome.txt
 92 |     100% |   0% |      0% |       7 | https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Other%20domains%20versions/BrowseWebsitesWithoutLoggingInAGH.txt
 93 |      99% |   1% |      0% |     819 | https://raw.githubusercontent.com/bigdargon/hostsVN/master/filters/adservers.txt
 94 |      96% |   4% |      0% |     217 | https://raw.githubusercontent.com/MasterKia/PersianBlocker/main/PersianBlockerHosts.txt
 95 |      46% |  51% |      3% |     744 | https://raw.githubusercontent.com/craiu/mobiletrackers/master/list.txt
 96 |     100% |   0% |      0% |       2 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/annoyances.txt
 97 |      96% |   4% |      0% |     893 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/badware.txt
 98 |      97% |   3% |      0% |      40 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2020.txt
 99 |      93% |   5% |      2% |      43 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2021.txt
100 |      92% |   6% |      2% |      49 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2022.txt
101 |     100% |   0% |      0% |      42 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2023.txt
102 |      96% |   4% |      0% |     137 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters.txt
103 |     100% |   0% |      0% |      36 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/privacy.txt
104 |     100% |   0% |      0% |       6 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/resource-abuse.txt
105 |      96% |   1% |      3% |     492 | https://gitlab.com/quidsup/notrack-annoyance-blocklist/-/raw/master/notrack-annoyance.txt
106 |      96% |   1% |      3% |   16565 | https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-blocklist.txt
107 |      81% |  10% |      9% |     252 | https://assets.windscribe.com/custom_blocklists/clickbait.txt
108 |     100% |   0% |      0% |      31 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-matomo.txt
109 |      97% |   2% |      1% |      92 | https://raw.githubusercontent.com/manic-code/Emerging-Malicious-Domain-Blocklist/main/hosts.txt
110 |      97% |   2% |      1% |    2224 | analytics-metrics-extension.txt
111 |     100% |   0% |      0% |      22 | native.apple.txt
112 |     100% |   0% |      0% |      66 | native.huawei.txt
113 |     100% |   0% |      0% |     104 | native.winoffice.txt
114 |     100% |   0% |      0% |     256 | native.tiktok.txt
115 |      95% |   5% |      0% |      66 | lg-webos.txt
116 |      88% |   1% |     11% |    2878 | black.list
117 |     100% |   0% |      0% |       1 | black.list.plus
118 |      84% |   0% |     16% |    4061 | black.list.size
119 |     100% |   0% |      0% |  100506 | personal.txt
120 |      73% |   1% |     26% |     141 | personal-wildcard-rules.txt
121 |     100% |   0% |      0% |    9825 | fake.txt
122 |     100% |   0% |      0% |  104911 | personal-tif.txt

For domain and host lists, additionally: matching/missing subdomains (see at the bottom)
```
#### ULTIMATE
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/ultimate-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/ultimate-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/ultimate-removed-dead.txt)
```
2785749 total unique domains | 2350768 (84%) included | 45093 (2%) removed | 389888 (14%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% | 1421033 | pro.plus.txt
  2 |      99% |   0% |      1% |   46402 | ultimate.extension.domains
  3 |      94% |   1% |      5% |  253006 | https://o0.pages.dev/Pro/hosts.txt
  4 |      54% |  34% |     12% |  184020 | https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts
  5 |      75% |  25% |      0% |  416323 | https://raw.githubusercontent.com/notracking/hosts-blocklists/master/dnscrypt-proxy/dnscrypt-proxy.blacklist.txt
  6 |      97% |   2% |      1% |  862812 | oisd.domains.txt
  7 |      92% |   8% |      0% |   49033 | https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt
  8 |      76% |  23% |      1% |     550 | https://raw.githubusercontent.com/AdguardTeam/AdGuardSDNSFilter/master/Filters/rules.txt
  9 |      90% |   9% |      1% |    1019 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_11_Mobile/filter.txt
 10 |      73% |  27% |      0% |     125 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_13_Turkish/filter.txt
 11 |      80% |  18% |      2% |     191 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt
 12 |      87% |  13% |      0% |    9307 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_16_French/filter.txt
 13 |      97% |   0% |      3% |      36 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_18_Annoyances_Cookies/filter.txt
 14 |      74% |  25% |      1% |     126 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_19_Annoyances_Popups/filter.txt
 15 |      76% |  24% |      0% |     564 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_1_Russian/filter.txt
 16 |     100% |   0% |      0% |       5 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_21_Annoyances_Other/filter.txt
 17 |      89% |  11% |      0% |    8043 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt
 18 |      88% |   8% |      4% |      24 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_22_Annoyances_Widgets/filter.txt
 19 |      98% |   2% |      0% |   25414 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt
 20 |      98% |   2% |      0% |   24337 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt
 21 |      50% |  50% |      0% |       2 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_4_Social/filter.txt
 22 |      86% |  14% |      0% |      56 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_6_German/filter.txt
 23 |      99% |   1% |      0% |     155 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_7_Japanese/filter.txt
 24 |      95% |   5% |      0% |      21 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_8_Dutch/filter.txt
 25 |      74% |  26% |      0% |      85 | https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_9_Spanish/filter.txt
 26 |      95% |   5% |      0% |    1430 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/adservers.txt
 27 |      97% |   3% |      0% |     196 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/adservers_firstparty.txt
 28 |      64% |  36% |      0% |     130 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/cryptominers.txt
 29 |     100% |   0% |      0% |      34 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/foreign.txt
 30 |      57% |  43% |      0% |     304 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/ChineseFilter/sections/adservers.txt
 31 |     100% |   0% |      0% |       2 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/DutchFilter/sections/adservers.txt
 32 |     100% |   0% |      0% |       5 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/DutchFilter/sections/adservers_firstparty.txt
 33 |      50% |  50% |      0% |      10 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/FrenchFilter/sections/adservers.txt
 34 |      94% |   3% |      3% |      33 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/GermanFilter/sections/adservers.txt
 35 |      97% |   1% |      2% |     321 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/JapaneseFilter/sections/adservers.txt
 36 |      89% |   9% |      2% |    1048 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/MobileFilter/sections/adservers.txt
 37 |      64% |  36% |      0% |    3707 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/adservers.txt
 38 |      69% |  31% |      0% |     161 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/adservers_firstparty.txt
 39 |      64% |  36% |      0% |      56 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/RussianFilter/sections/news_exchange.txt
 40 |      79% |  20% |      1% |     172 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpanishFilter/sections/adservers.txt
 41 |      89% |   9% |      2% |     646 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/mobile.txt
 42 |      95% |   3% |      2% |    4802 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers.txt
 43 |      84% |  14% |      2% |    2200 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers_firstparty.txt
 44 |      81% |  18% |      1% |     280 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/TurkishFilter/sections/adservers.txt
 45 |      62% |  38% |      0% |      61 | https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/TurkishFilter/sections/adservers_firstparty.txt
 46 |      98% |   2% |      0% |   21128 | https://easylist-downloads.adblockplus.org/easylist.txt
 47 |      94% |   1% |      5% |   15288 | https://easylist-downloads.adblockplus.org/easyprivacy.txt
 48 |      97% |   2% |      1% |      96 | https://easylist-downloads.adblockplus.org/antiadblockfilters.txt
 49 |      77% |  23% |      0% |      13 | https://easylist-downloads.adblockplus.org/Liste_AR.txt
 50 |      47% |  53% |      0% |    1928 | https://easylist-downloads.adblockplus.org/advblock.txt
 51 |      89% |  11% |      0% |    7987 | https://easylist-downloads.adblockplus.org/easylistchina.txt
 52 |      94% |   6% |      0% |      16 | https://easylist-downloads.adblockplus.org/easylistdutch.txt
 53 |      87% |  13% |      0% |      40 | https://easylist-downloads.adblockplus.org/easylistgermany.txt
 54 |      91% |   7% |      2% |      46 | https://easylist-downloads.adblockplus.org/easylistitaly.txt
 55 |     100% |   0% |      0% |       3 | https://easylist-downloads.adblockplus.org/easylistpolish.txt
 56 |     100% |   0% |      0% |      14 | https://easylist-downloads.adblockplus.org/easylistportuguese.txt
 57 |     100% |   0% |      0% |       7 | https://easylist-downloads.adblockplus.org/easylistspanish.txt
 58 |     100% |   0% |      0% |       3 | https://easylist-downloads.adblockplus.org/indianlist.txt
 59 |     100% |   0% |      0% |       3 | https://easylist-downloads.adblockplus.org/koreanlist.txt
 60 |      87% |  13% |      0% |    9302 | https://easylist-downloads.adblockplus.org/liste_fr.txt
 61 |      47% |  53% |      0% |    1928 | https://easylist-downloads.adblockplus.org/ruadlist.txt
 62 |      63% |  37% |      0% |      19 | https://fanboy.co.nz/enhancedstats.txt
 63 |      60% |  40% |      0% |      15 | https://notabug.org/latvian-list/adblock-latvian/raw/master/lists/latvian-list.txt
 64 |      92% |   8% |      0% |      24 | https://raw.github.com/tomasko126/easylistczechandslovak/master/filters.txt
 65 |      39% |  61% |      0% |      38 | https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo.txt
 66 |     100% |   0% |      0% |       9 | https://raw.githubusercontent.com/EasyList-Lithuania/easylist_lithuania/master/easylistlithuania.txt
 67 |     100% |   0% |      0% |      68 | https://raw.githubusercontent.com/abpvn/abpvn/master/filter/abpvn.txt
 68 |      89% |  10% |      1% |     617 | https://raw.githubusercontent.com/easylist-thailand/easylist-thailand/master/subscription/easylist-thailand.txt
 69 |      71% |  29% |      0% |      31 | https://raw.githubusercontent.com/easylist/EasyListHebrew/master/EasyListHebrew.txt
 70 |      89% |  11% |      0% |      53 | https://raw.githubusercontent.com/hufilter/hufilter/master/hufilter.txt
 71 |      94% |   5% |      1% |      98 | https://raw.githubusercontent.com/yous/YousList/master/youslist.txt
 72 |      97% |   0% |      3% |     179 | https://secure.fanboy.co.nz/fanboy-annoyance.txt
 73 |      96% |   0% |      4% |     140 | https://secure.fanboy.co.nz/fanboy-cookiemonster.txt
 74 |     100% |   0% |      0% |       4 | https://secure.fanboy.co.nz/fanboy-social.txt
 75 |     100% |   0% |      0% |       4 | https://stanev.org/abp/adblock_bg.txt
 76 |      77% |  23% |      0% |      30 | https://www.void.gr/kargig/void-gr-filters.txt
 77 |      87% |  10% |      3% |     117 | https://www.zoso.ro/pages/rolist.txt
 78 |      66% |  34% |      0% |     261 | https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/src/advert/adservers.txt
 79 |      56% |  44% |      0% |      18 | https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/src/advert/thirdparty.txt
 80 |      98% |   2% |      0% |   21819 | https://raw.githubusercontent.com/easylist/easylist/master/easylist/easylist_adservers.txt
 81 |     100% |   0% |      0% |     714 | https://raw.githubusercontent.com/easylist/easylist/master/easylist/easylist_thirdparty.txt
 82 |      98% |   0% |      2% |    1267 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_thirdparty.txt
 83 |      99% |   0% |      1% |     480 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_thirdparty_international.txt
 84 |      97% |   0% |      3% |    4435 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_trackingservers.txt
 85 |      96% |   0% |      4% |     927 | https://raw.githubusercontent.com/easylist/easylist/master/easyprivacy/easyprivacy_trackingservers_international.txt
 86 |      87% |   4% |      9% |      23 | https://raw.githubusercontent.com/easylist/easylistdutch/master/easylistdutch/block_third_party_server.txt
 87 |      93% |   6% |      1% |     282 | https://raw.githubusercontent.com/easylist/easylistgermany/master/easylistgermany/easylistgermany_adservers.txt
 88 |      95% |   5% |      0% |     134 | https://raw.githubusercontent.com/easylist/easylistitaly/master/easylistitaly/easylistitaly_adservers.txt
 89 |      87% |  10% |      3% |    1046 | https://raw.githubusercontent.com/lassekongo83/Frellwits-filter-lists/master/Frellwits-Swedish-Hosts-File.txt
 90 |      93% |   4% |      3% |      71 | https://raw.githubusercontent.com/realodix/AdBlockID/master/src/adservers.adfl
 91 |      97% |   3% |      0% |     314 | https://raw.githubusercontent.com/DandelionSprout/adfilt/master/NorwegianExperimentalList%20alternate%20versions/NordicFiltersAdGuardHome.txt
 92 |     100% |   0% |      0% |       7 | https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Other%20domains%20versions/BrowseWebsitesWithoutLoggingInAGH.txt
 93 |      99% |   1% |      0% |     819 | https://raw.githubusercontent.com/bigdargon/hostsVN/master/filters/adservers.txt
 94 |      96% |   4% |      0% |     217 | https://raw.githubusercontent.com/MasterKia/PersianBlocker/main/PersianBlockerHosts.txt
 95 |      46% |  51% |      3% |     744 | https://raw.githubusercontent.com/craiu/mobiletrackers/master/list.txt
 96 |     100% |   0% |      0% |       2 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/annoyances.txt
 97 |      96% |   4% |      0% |     893 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/badware.txt
 98 |      97% |   3% |      0% |      40 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2020.txt
 99 |      93% |   5% |      2% |      43 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2021.txt
100 |      92% |   6% |      2% |      49 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2022.txt
101 |     100% |   0% |      0% |      42 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2023.txt
102 |      96% |   4% |      0% |     137 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters.txt
103 |     100% |   0% |      0% |      36 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/privacy.txt
104 |     100% |   0% |      0% |       6 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/resource-abuse.txt
105 |      96% |   1% |      3% |     492 | https://gitlab.com/quidsup/notrack-annoyance-blocklist/-/raw/master/notrack-annoyance.txt
106 |      97% |   1% |      2% |   16565 | https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-blocklist.txt
107 |      81% |  10% |      9% |     252 | https://assets.windscribe.com/custom_blocklists/clickbait.txt
108 |      87% |  11% |      2% |     906 | https://raw.githubusercontent.com/AssoEchap/stalkerware-indicators/master/generated/hosts_full
109 |      57% |  29% |     14% |       7 | https://raw.githubusercontent.com/yourduskquibbles/webannoyances/master/ultralist.txt
110 |      66% |   8% |     26% |      91 | https://raw.githubusercontent.com/yokoffing/filterlists/main/privacy_essentials.txt
111 |      73% |   0% |     27% |      11 | https://raw.githubusercontent.com/yokoffing/filterlists/main/annoyance_list.txt
112 |      93% |   3% |      4% |    1027 | https://raw.githubusercontent.com/symbuzzer/Turkish-Ad-Hosts/main/hosts
113 |      94% |   4% |      2% |   16709 | https://raw.githubusercontent.com/migueldemoura/ublock-umatrix-rulesets/master/Hosts/ads-tracking
114 |      91% |   7% |      2% |   81250 | https://raw.githubusercontent.com/Cats-Team/AdRules/main/ad-domains.txt
115 |      90% |   8% |      2% |   57039 | https://anti-ad.net/easylist.txt
116 |      95% |   4% |      1% |   17495 | https://raw.githubusercontent.com/bigdargon/hostsVN/master/hosts
117 |      97% |   3% |      0% |    1784 | https://raw.githubusercontent.com/bigdargon/hostsVN/master/option/hosts-VN
118 |      82% |  16% |      2% |  148878 | https://raw.githubusercontent.com/bongochong/CombinedPrivacyBlockLists/master/newhosts-final.hosts
119 |      67% |  29% |      4% |     347 | https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt
120 |      83% |  11% |      6% |      35 | https://raw.githubusercontent.com/nextdns/cname-cloaking-blocklist/master/domains
121 |     100% |   0% |      0% |      31 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-matomo.txt
122 |      97% |   2% |      1% |      92 | https://raw.githubusercontent.com/manic-code/Emerging-Malicious-Domain-Blocklist/main/hosts.txt
123 |      96% |   1% |      3% |   15921 | ads-tracking-extension.txt
124 |      97% |   2% |      1% |    2224 | analytics-metrics-extension.txt
125 |     100% |   0% |      0% |      22 | native.apple.txt
126 |     100% |   0% |      0% |      66 | native.huawei.txt
127 |     100% |   0% |      0% |     104 | native.winoffice.txt
128 |     100% |   0% |      0% |     256 | native.tiktok.txt
129 |      95% |   5% |      0% |      66 | lg-webos.txt
130 |      88% |   1% |     11% |    2878 | black.list
131 |     100% |   0% |      0% |       1 | black.list.plus
132 |      86% |   0% |     14% |    4061 | black.list.size
133 |     100% |   0% |      0% |  100506 | personal.txt
134 |      81% |   1% |     18% |     141 | personal-wildcard-rules.txt
135 |     100% |   0% |      0% |    9825 | fake.txt
136 |      98% |   0% |      2% |      51 | hoster.txt
137 |     100% |   0% |      0% | 1343465 | tif.txt

For domain and host lists, additionally: matching/missing subdomains (see at the bottom)
```
#### FAKE
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/fake-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/fake-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/fake-removed-dead.txt)
```
11010 total unique domains | 9825 (89%) included | 325 (3%) removed | 860 (8%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |      93% |   4% |      3% |    1380 | fake.ts.txt
  2 |      77% |   6% |     17% |     363 | fake.vzni.txt
  3 |      88% |   6% |      6% |    4697 | fake.wli.txt
```
#### TIF
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/tif-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/tif-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/tif-removed-dead.txt)
```
2654297 total unique domains | 1343465 (51%) included | 15103 (1%) removed | 1295729 (49%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |      75% |  20% |      5% |     156 | https://gitlab.com/cmiksche/blacklists/-/raw/master/hosts
  2 |      33% |  66% |      1% |   96130 | https://hole.cert.pl/domains/domains_hosts.txt
  3 |      85% |  14% |      1% |   21706 | https://malware-filter.gitlab.io/malware-filter/phishing-filter-hosts.txt
  4 |      68% |  21% |     11% |     195 | https://malware-filter.gitlab.io/malware-filter/pup-filter-hosts.txt
  5 |      94% |   5% |      1% |   18039 | https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-hosts.txt
  6 |      68% |  30% |      2% |   15702 | https://malware-filter.gitlab.io/malware-filter/vn-badsite-filter-hosts.txt
  7 |      77% |  15% |      8% |     544 | https://paulgb.github.io/BarbBlock/blacklists/hosts-file.txt
  8 |      89% |   4% |      7% |   10085 | https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareHosts.txt
  9 |      29% |  70% |      1% |   22898 | https://raw.githubusercontent.com/Dogino/Discord-Phishing-URLs/main/pihole-phishing-adlist.txt
 10 |      82% |   9% |      9% |    2189 | https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts
 11 |      85% |   4% |     11% |      57 | https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts
 12 |      38% |  57% |      5% |    3319 | https://raw.githubusercontent.com/HexxiumCreations/threat-list/gh-pages/hosts.txt
 13 |      79% |  19% |      2% |    3381 | https://raw.githubusercontent.com/Th3M3/blocklists/master/malware.list
 14 |      59% |  38% |      3% |    3692 | https://raw.githubusercontent.com/bigdargon/hostsVN/master/extensions/threat/hosts
 15 |      84% |  16% |      0% |      38 | https://raw.githubusercontent.com/davidonzo/Threat-Intel/master/lists/latestdomains.piHole.txt
 16 |      97% |   0% |      3% |     962 | https://raw.githubusercontent.com/durablenapkin/scamblocklist/master/hosts.txt
 17 |      20% |  80% |      0% |    8624 | https://raw.githubusercontent.com/guardicore/labs_campaigns/master/Autodiscover/autodiscover-tlds.txt
 18 |      51% |  43% |      6% |     724 | https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt
 19 |      27% |  73% |      0% |    1071 | https://raw.githubusercontent.com/metamask/eth-phishing-detect/master/src/hosts.txt
 20 |      75% |  22% |      3% |    1384 | https://raw.githubusercontent.com/mitchellkrogza/Badd-Boyz-Hosts/master/hosts
 21 |      57% |  42% |      1% |   13464 | https://raw.githubusercontent.com/mitchellkrogza/The-Big-List-of-Hacked-Malware-Web-Sites/master/hosts
 22 |      86% |  13% |      1% |   26653 | https://threatfox.abuse.ch/downloads/hostfile
 23 |      98% |   1% |      1% |     467 | https://urlhaus.abuse.ch/downloads/hostfile
 24 |      97% |   3% |      0% |  104204 | https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/malware-domains.txt
 25 |      85% |  15% |      0% |      26 | https://raw.githubusercontent.com/iam-py-test/vxvault_filter/main/domains_file.txt
 26 |      46% |  51% |      3% |     879 | https://raw.githubusercontent.com/piperun/iploggerfilter/master/filterlist
 27 |      74% |   3% |     23% |     893 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/badware.txt
 28 |      43% |  57% |      0% |     983 | https://azorult-tracker.net/api/list/domain?format=plain
 29 |      11% |  87% |      2% |     898 | https://cert-agid.gov.it/download/log4shell-iocs-raw-domain.txt
 30 |      45% |  55% |      0% |   11942 | https://dl.red.flag.domains/red.flag.domains_fr.txt
 31 |      22% |  78% |      0% |    9781 | https://gitlab.com/KevinThomas0/cryptoscamdb-lists/-/raw/master/cryptoscamdb-blocklist.txt
 32 |      20% |  80% |      0% |    1055 | https://gitlab.com/nitrohorse/government-malware-domains-blocklist/-/raw/master/domains.txt
 33 |      36% |  55% |      9% |    1063 | https://gitlab.com/quidsup/notrack-blocklists/-/raw/master/notrack-malware.txt
 34 |      61% |  37% |      2% |    1100 | https://orca.pet/notonmyshift/domains.txt
 35 |      84% |  16% |      0% |      38 | https://osint.digitalside.it/Threat-Intel/lists/latestdomains.txt
 36 |      40% |  60% |      0% |  116197 | https://phishing.army/download/phishing_army_blocklist.txt
 37 |      41% |  59% |      0% |  120244 | https://phishing.army/download/phishing_army_blocklist_extended.txt
 38 |      24% |  76% |      0% |    1438 | https://raw.githubusercontent.com/AmnestyTech/investigations/master/2021-07-18_nso/domains.txt
 39 |      45% |  55% |      0% |      29 | https://raw.githubusercontent.com/AmnestyTech/investigations/master/2021-10-07_donot/domains.txt
 40 |      25% |  75% |      0% |     326 | https://raw.githubusercontent.com/AmnestyTech/investigations/master/2021-12-16_cytrox/domains.txt
 41 |      29% |  12% |     59% |      34 | https://raw.githubusercontent.com/DRSDavidSoft/additional-hosts/master/domains/blacklist/fake-domains.txt
 42 |      43% |  53% |      4% |  106070 | https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADomains.txt
 43 |      73% |  16% |     11% |   33850 | https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Malware
 44 |      37% |  46% |     17% |     909 | https://raw.githubusercontent.com/SystemJargon/blocklists/main/lists/threats/aggregated-threats-1.txt
 45 |      58% |  41% |      1% |    4044 | https://raw.githubusercontent.com/bongochong/CombinedPrivacyBlockLists/master/NoFormatting/MD-ID-Fork.txt
 46 |      59% |  15% |     26% |      39 | https://raw.githubusercontent.com/craiu/iocs/main/log4shell/log4j_blocklist.txt
 47 |      71% |  29% |      0% |    6423 | https://raw.githubusercontent.com/elliotwutingfeng/GlobalAntiScamOrg-blocklist/main/global-anti-scam-org-scam-urls-pihole.txt
 48 |      49% |  51% |      0% |  603122 | https://raw.githubusercontent.com/elliotwutingfeng/Inversion-DNSBL-Blocklists/main/Google_hostnames.txt
 49 |      78% |  22% |      0% |    6943 | https://raw.githubusercontent.com/elliotwutingfeng/Inversion-DNSBL-Blocklists/main/Google_hostnames_light.txt
 50 |      61% |  32% |      7% |   10395 | https://raw.githubusercontent.com/iam-py-test/my_filters_001/main/Alternative%20list%20formats/antimalware_domains.txt
 51 |      21% |  79% |      0% |   16413 | https://raw.githubusercontent.com/ihgalis/pihole_collection/master/Sinking_Yachts_Phishing
 52 |      57% |  37% |      6% |    7331 | https://raw.githubusercontent.com/infinitytec/blocklists/master/scams-and-phishing.txt
 53 |      53% |  44% |      3% |     619 | https://raw.githubusercontent.com/marco-acorte/antispam-it/main/antispam-it.txt
 54 |      69% |  26% |      5% |    2243 | https://raw.githubusercontent.com/matomo-org/referrer-spam-blacklist/master/spammers.txt
 55 |      56% |  42% |      2% |   71154 | https://raw.githubusercontent.com/mitchellkrogza/Phishing.Database/master/phishing-domains-ACTIVE.txt
 56 |      82% |  17% |      1% |   12886 | https://raw.githubusercontent.com/mitchellkrogza/Phishing.Database/master/phishing-domains-NEW-today.txt
 57 |      22% |  78% |      0% |    2143 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-amnenstytech.txt
 58 |      49% |  50% |      1% |     534 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-certagid.txt
 59 |      36% |  63% |      1% |     387 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-certego.txt
 60 |      23% |  77% |      0% |    1009 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-citizenlabs.txt
 61 |      64% |  35% |      1% |    1830 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-csirt.txt
 62 |      63% |  34% |      3% |     297 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-cyble.txt
 63 |      43% |  57% |      0% |     242 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-drweb.txt
 64 |      63% |  29% |      8% |     224 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-eset.txt
 65 |      69% |  30% |      1% |     139 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-kaspersky.txt
 66 |      48% |  51% |      1% |    9307 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-main.txt
 67 |      44% |  55% |      1% |    2083 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-malware-traffic.txt
 68 |      16% |  84% |      0% |    1238 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-orangecyber.txt
 69 |      51% |  31% |     18% |      39 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-orangelog4shell.txt
 70 |      45% |  54% |      1% |    5459 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-personal.txt
 71 |      18% |  82% |      0% |     864 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-sentinelone.txt
 72 |      21% |  75% |      4% |      67 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-sophos.txt
 73 |      39% |  56% |      5% |     241 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-tag.txt
 74 |      49% |  51% |      0% |     508 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-unit42-playbook.txt
 75 |      11% |  89% |      0% |   23220 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-unit42-silverterrier.txt
 76 |      54% |  46% |      0% |     903 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-yoroi.txt
 77 |      37% |  60% |      3% |    5845 | https://raw.githubusercontent.com/scafroglia93/blocklists/master/blocklists-zscaler.txt
 78 |      50% |  49% |      1% |  273761 | https://raw.githubusercontent.com/stamparm/aux/master/maltrail-malware-domains.txt
 79 |      37% |  63% |      0% |   17840 | https://raw.githubusercontent.com/stamparm/blackbook/master/blackbook.txt
 80 |      96% |   4% |      0% |     500 | https://rescure.me/covid.txt
 81 |      71% |  28% |      1% |     500 | https://rescure.me/rescure_domain_blacklist.txt
 82 |      38% |  60% |      2% |      63 | https://www.botvrij.eu/data/ioclist.domain.raw
 83 |      55% |  45% |      0% |      53 | https://www.botvrij.eu/data/ioclist.hostname.raw
 84 |      70% |  30% |      0% |   43534 | https://www.stopforumspam.com/downloads/toxic_domains_whole.txt
 85 |      81% |  18% |      1% |   10725 | https://threatview.io/Downloads/DOMAIN-High-Confidence-Feed.txt
 86 |      43% |  55% |      2% |    2339 | https://hosts.tweedge.net/malicious.txt
 87 |      58% |  40% |      2% |   15878 | https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/cryptojacking/domains
 88 |      44% |  56% |      0% |   36085 | https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/phishing/domains
 89 |      44% |  56% |      0% |   36007 | https://raw.githubusercontent.com/olbat/ut1-blacklists/master/blacklists/malware/domains
 90 |      92% |   6% |      2% |   23634 | black.list.threat-intelligence
 91 |      43% |   0% |     57% |      51 | black.list.hoster
 92 |     100% |   0% |      0% |  104911 | personal-tif.txt
```
#### DOH-VPN-PROXY-BYPASS
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/doh-vpn-proxy-bypass-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/doh-vpn-proxy-bypass-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/doh-vpn-proxy-bypass-removed-dead.txt)
```
2767 total unique domains | 1414 (51%) included | 3 (0%) removed | 1350 (49%) dead

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
388 total unique domains | 364 (94%) included | 0 (0%) removed | 24 (6%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |      92% |   8% |      0% |     302 | https://raw.githubusercontent.com/nextdns/dns-bypass-methods/main/encrypted-dns
  2 |     100% |   0% |      0% |     352 | black.list.dohdot
```
#### NOSAFESEARCH
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/nosafesearch-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/nosafesearch-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/nosafesearch-removed-dead.txt)
```
178 total unique domains | 148 (83%) included | 0 (0%) removed | 30 (17%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |      83% |  17% |      0% |     174 | https://raw.githubusercontent.com/nextdns/no-safesearch/main/domains
```
#### DYNDNS
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/dyndns-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/dyndns-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/dyndns-removed-dead.txt)
```
793 total unique domains | 793 (100%) included | 0 (0%) removed | 0 (0%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% |     790 | https://raw.githubusercontent.com/nextdns/ddns-domains/main/suffixes
  2 |     100% |   0% |      0% |       4 | black.list.dyndns
```
#### HOSTER
[whitelisted domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/hoster-removed-white.txt) | [whitelisted referral domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/hoster-removed-referral.txt) | [dead domains](https://raw.githubusercontent.com/hagezi/dns-data-collection/main/data/hoster-removed-dead.txt)
```
51 total unique domains | 51 (100%) included | 0 (0%) removed | 0 (0%) dead

 Nr | Included | Dead | Removed |   Count | URL/File
  1 |     100% |   0% |      0% |      51 | black.list.hoster
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
https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Free
https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Malware
https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Risk
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

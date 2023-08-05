Dataset link: [https://drive.google.com/file/d/1gRkdAUZm6lTWfAJ9byqlR2wd_DQ0_sYl/view?usp=sharing](https://drive.google.com/file/d/1mlAM1-lZ95zKKPxlUb4Ah9drMFLr7lRV/view?usp=sharing)

Directory prepare
1. Construct the data directory under the root directory

Dataset prepare
1. Download dataset from Dataset link
2. put the bugs.json into the data directory

Construct the SysKG-UTF
1. run 1_filter_bugs.py
2. run 2_split_section.py
3. run 3_get_sec_results_into_bugs.py
4. run 4_split_s2r.py
5. run 5_get_step_results_into_bugs.py
6. run 6_fast_clustering_by_transformer.py

Generate test scenarios
1. run 7_generate_scenario.py

Bugs found
1. Bug 1-22 found during the user study by the experimental group
2. Bug 23-35 found during the user study by the control group
3. Bug 36-59 found during the tool development and test scenario variation

| No.      | Bug ID | Period |
| -------- | ------ | ------ |
| 1  | https://bugzilla.mozilla.org/show_bug.cgi?id=1844283 | user study |
| 2  | https://bugzilla.mozilla.org/show_bug.cgi?id=1844289 | user study |
| 3  | https://bugzilla.mozilla.org/show_bug.cgi?id=1844980 | user study |
| 4  | https://bugzilla.mozilla.org/show_bug.cgi?id=1844891 | user study |
| 5  | https://bugzilla.mozilla.org/show_bug.cgi?id=1844893 | user study |
| 6  | https://bugzilla.mozilla.org/show_bug.cgi?id=1844902 | user study |
| 7  | https://bugzilla.mozilla.org/show_bug.cgi?id=1844931 | user study |
| 8  | https://bugzilla.mozilla.org/show_bug.cgi?id=1844933 | user study |
| 9  | https://bugzilla.mozilla.org/show_bug.cgi?id=1844374 | user study |
| 10 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844390 | user study |
| 11 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844972 | user study |
| 12 | https://bugzilla.mozilla.org/show_bug.cgi?id=1831455 | user study |
| 13 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844998 | user study |
| 14 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844999 | user study |
| 15 | https://bugzilla.mozilla.org/show_bug.cgi?id=1845000 | user study |
| 16 | https://bugzilla.mozilla.org/show_bug.cgi?id=1845002 | user study |
| 17 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844935 | user study |
| 18 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844936 | user study |
| 19 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844621 | user study |
| 20 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844715 | user study |
| 21 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844720 | user study |
| 22 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844339 | user study |
| 23 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844272 | user study |
| 24 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844276 | user study |
| 25 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844374 | user study |
| 26 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844973 | user study |
| 27 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844376 | user study |
| 28 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844378 | user study |
| 29 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844380 | user study |
| 30 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844383 | user study |
| 31 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844331 | user study |
| 32 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844384 | user study |
| 33 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844393 | user study |
| 34 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844975 | user study |
| 35 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844980 | user study |
| 36 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844934 | others |
| 37 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844790 | others |
| 38 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844808 | others |
| 39 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844316 | others |
| 40 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844322 | others |
| 41 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844984 | others |
| 42 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844985 | others |
| 43 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844987 | others |
| 44 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844988 | others |
| 45 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844937 | others |
| 46 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844938 | others |
| 47 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844778 | others |
| 48 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844898 | others |
| 49 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844899 | others |
| 50 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844903 | others |
| 51 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844932 | others |
| 52 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844940 | others |
| 53 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844969 | others |
| 54 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844971 | others |
| 55 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844399 | others |
| 56 | https://bugzilla.mozilla.org/show_bug.cgi?id=1844997 | others |
| 57 | https://bugzilla.mozilla.org/show_bug.cgi?id=1845136 | others |
| 58 | https://bugzilla.mozilla.org/show_bug.cgi?id=1846182 | others |
| 59 | https://bugzilla.mozilla.org/show_bug.cgi?id=1846184 | others |


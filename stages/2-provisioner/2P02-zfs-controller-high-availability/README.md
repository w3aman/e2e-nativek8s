### 2P02-zfs-controller-high-availability

#### Description

This test deploys the zfs-controller in high availability (more than one replica) and checks the behaviour of zfs-localpv when one of the replica is down.

#### steps involved

- First deploy the zfs-controller with single replica
- Then scale the replicas of zfs-controller statefulset and verify the provision of volume when other replica is down.
- For more detailed README for the test [click here](https://github.com/openebs/e2e-tests/tree/master/experiments/zfs-localpv/functional/zfs-controller-high-availability)

#### Test Results

| Job ID  |      Test Description         | Execution Time |   Test Result   |
|---------|-------------------------------|----------------|-----------------|
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/300967">300967</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sat Dec  5 10:53:05 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/300742">300742</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Dec  4 18:10:40 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/300708">300708</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Dec  4 16:43:35 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/300561">300561</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Dec  4 13:40:28 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/300527">300527</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Dec  4 11:20:28 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/299794">299794</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Dec  2 21:32:40 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/299760">299760</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Dec  2 16:59:13 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/299724">299724</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Dec  2 11:25:24 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/299289">299289</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Nov 30 21:35:26 IST 2020  | none |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/299062">299062</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Nov 30 11:45:20 IST 2020  | none |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/297874">297874</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Nov 25 19:22:25 IST 2020  | none |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/294383">294383</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sun Nov 15 14:18:52 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/292890">292890</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sat Nov 14 17:40:27 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/292610">292610</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sat Nov 14 15:56:33 IST 2020  | none |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/292530">292530</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sat Nov 14 13:40:41 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/292447">292447</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sat Nov 14 11:40:56 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/290280">290280</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Nov 13 13:11:51 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/290089">290089</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Nov 13 11:19:41 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/290053">290053</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Nov 13 09:21:19 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/289827">289827</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Thu Nov 12 20:28:54 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/289792">289792</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Thu Nov 12 17:59:29 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/289678">289678</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Thu Nov 12 16:46:36 IST 2020  | none |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/289339">289339</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Thu Nov 12 08:55:58 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/288878">288878</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Nov 11 16:06:33 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/288844">288844</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Nov 11 12:50:45 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/288809">288809</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Nov 11 10:50:51 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/288695">288695</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Nov 11 08:24:25 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/288469">288469</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Nov 10 22:05:23 IST 2020  | none |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/288244">288244</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Nov 10 18:23:51 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/281241">281241</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Thu Oct 15 14:31:19 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/280397">280397</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Oct 14 21:58:46 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/279623">279623</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Oct 14 14:57:03 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/279574">279574</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Oct 14 13:32:39 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/279278">279278</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Oct 14 11:32:04 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/279022">279022</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Oct 14 10:40:02 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/278908">278908</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Oct 13 20:42:11 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/278874">278874</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Oct 13 18:55:26 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/278840">278840</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Oct 13 16:42:13 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/277909">277909</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Oct 12 21:39:46 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/277095">277095</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Oct 12 17:22:46 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/276888">276888</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Oct 12 15:34:17 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/276438">276438</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sat Oct 10 23:27:30 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/276385">276385</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sat Oct 10 19:40:38 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/276351">276351</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sat Oct 10 17:53:18 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/276298">276298</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sat Oct 10 16:49:45 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/276245">276245</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sat Oct 10 15:25:49 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/274607">274607</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Oct  9 11:20:46 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/274548">274548</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Oct  9 10:16:02 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/271261">271261</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Thu Oct  1 17:16:18 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/268075">268075</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Sep 22 13:32:01 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/267962">267962</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Sep 22 11:38:02 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/266905">266905</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Sep 18 16:49:05 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/266877">266877</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Sep 18 16:31:19 IST 2020  | none |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/266566">266566</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Thu Sep 17 11:18:00 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/266423">266423</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Sep 16 20:08:00 IST 2020  | none |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/264778">264778</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Sep 15 20:18:41 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/264734">264734</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Sep 15 19:14:32 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/263010">263010</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Sep 14 12:44:20 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/260583">260583</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Sep 11 09:08:26 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/260170">260170</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Thu Sep 10 21:32:17 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/260141">260141</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Thu Sep 10 21:13:17 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/260050">260050</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Thu Sep 10 19:58:13 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/258056">258056</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Sep  8 11:35:55 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/257830">257830</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Sep  7 18:06:11 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/257552">257552</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Sep  4 15:53:54 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/257526">257526</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Sep  4 11:59:42 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/257332">257332</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Sep  2 16:11:15 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/257306">257306</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Sep  2 13:37:05 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/257280">257280</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Sep  2 10:17:43 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/257171">257171</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Sep  1 20:21:23 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/257145">257145</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Sep  1 19:09:58 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/257118">257118</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Sep  1 13:04:54 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/257093">257093</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Sep  1 11:59:52 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/256985">256985</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Aug 31 21:12:17 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/256963">256963</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Aug 31 13:25:45 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/256766">256766</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Aug 31 09:38:17 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/256743">256743</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Aug 31 06:57:10 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/254798">254798</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Aug 21 16:31:52 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/253788">253788</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Aug 19 16:00:03 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/253173">253173</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sun Aug 16 12:31:23 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/252954">252954</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sat Aug 15 23:45:35 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/252929">252929</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sat Aug 15 19:42:59 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/252558">252558</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Sat Aug 15 10:31:16 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/251939">251939</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Aug 14 21:15:18 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/251855">251855</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Aug 14 20:28:21 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/251833">251833</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Aug 14 19:40:19 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/251561">251561</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Aug 14 11:42:04 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/251537">251537</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Aug 14 10:48:14 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/250265">250265</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Thu Aug 13 10:37:40 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/249600">249600</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Aug 12 21:45:24 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/249485">249485</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Aug 12 19:35:41 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/249401">249401</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Aug 12 17:20:08 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/249119">249119</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Aug 12 11:54:30 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/249096">249096</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Wed Aug 12 10:37:17 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/248762">248762</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Aug 11 17:44:50 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/248256">248256</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Aug 11 10:21:24 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/248203">248203</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Tue Aug 11 09:30:33 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/247056">247056</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Aug 10 17:48:17 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/246951">246951</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Aug 10 17:03:48 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/246904">246904</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Aug 10 15:35:09 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/246882">246882</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Mon Aug 10 14:17:35 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/245459">245459</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Aug  7 21:20:31 IST 2020  | Pass |
|     <a href="https://gitlab.openebs.ci/openebs/e2e-nativek8s/-/jobs/245354">245354</a>           |  Deploy zfs-localpv controller statefulset in high availability           | Fri Aug  7 19:26:32 IST 2020  | Pass |

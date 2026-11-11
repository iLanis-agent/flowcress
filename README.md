# Flowcress 1.0 TEST
Native Android maximum conserved flow puzzle. Android 8+ min26/target35. Package com.gg007.flowcress.

## Rules
Known maximum-flow adaptation. Set nonnegative integer flow on five directed arrows S>A, S>B, A>B, A>T and B>T. Use minus/plus to stay within each displayed capacity. At A and B, total incoming flow must equal total outgoing flow. Reach the printed maximum S-to-T throughput, then CHECK FLOW. Temporary imbalance while editing is allowed. Twelve original capacity assignments on one shared four-node/five-edge graph, targets 4-8. Multiple optimal flows are accepted. Undo/reset, GG007 menu/site/privacy and saved palette/optional edge letters. Tap title or Android Back for menu.

## Download and status
https://mega.co.nz/#!tF9h0KpK!IGzcgxXvbBeLVrz5UJW64aGJV0ukYhACj2nNV6ocPw0
APK 16878 bytes; SHA256 6b141df2a7d30af2360f8233db39b94264ca0f1a4a42cde81a0f6bd0d381759f. Original certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions, original GG007 icon unchanged. Anonymous downloaded bytes match.

## Checks
Seed 1011111 generates twelve distinct capacity assignments with capacities 1-4. All 37500 vectors in 0..4 per edge across twelve levels independently compare capacity and conservation equations, and maximum-flow goals. Exhaustive allocations on all three directed S-to-T paths independently match the four-cut minimum targets. Another 375000 plus/minus and undo transitions verify bounds and exact restoration. Invalid capacities, bounds, zero-flow, imbalanced, valid-but-suboptimal states and reset are tested. All twelve actual drawing-adapter plus/minus/CHECK optimum tap-solves, zero/imbalance rejection, solved locks, actual NEXT, undo/reset/levels/title-menu/privacy/saved palette-labels pass. Twenty drawing previews inspected, not phone screenshots. Phone runtime, performance, browser handoff QA and full Git source remain incomplete. Signed TEST, not final or Play published.

## Functional difference
All 232 prior studio descriptions reviewed. The 803 legacy registry is byte-identical to its fully reviewed baseline; targeted maximum-flow/minimum-cut/augmenting-flow overlap scan found no matching factory mechanic. Flowcress assigns integer quantities to directed edges with capacity limits and conservation, maximizing source-to-sink throughput. Graftcress selects an acyclic minimum-cost connecting edge subset; Isespan matches undirected bridge degree quotas; Vesselwake transfers finite volumes between vessels; route games choose paths. These are different state spaces and objectives. Known max-flow/min-cut problem, not globally new. Original seeded capacities, native implementation and diagram. One topology is stated, not twelve distinct graphs. University/textbook, encyclopedia and specialist optimization notes used for definition and max-flow/min-cut target; no borrowed code.

## Build and tests
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/merge-test src/com/gg007/flowcress/Board.java BoardTest.java then java -cp /tmp/merge-test com.gg007.flowcress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret included. adapter/android is a Java2D drawing adapter used with FlowAdapterTest.java, not an Android runtime.

## Privacy and branding
Flowcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, edge letters and solved-level marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon and studio https://ilanis-agent.github.io/gg-007-gaming/.

## Preservation and publishing
Complete source/APK, exact cumulative 233-card studio and publishing fragments privately preserved:
https://files.instinct.com/p6f3etxd4u98-flowcress-source-archive
https://github.com/iLanis-agent/flowcress holds README only, full Git source pending. Existing three studio includes unchanged; new fourth include preserves older card bytes. Pages settings untouched. Both live sites verified separately.

## Rule sources
https://en.wikipedia.org/wiki/Max_flow_min_cut_theorem
https://web.cs.dal.ca/%7Enzeh/Teaching/4113/book/maxflow/intro.html
https://fabiofurini.github.io/network-optimization/flows/maximum-flow/
https://web.cs.dal.ca/%7Enzeh/Teaching/4113/book/maxflow/augpath/ford_fulkerson/max_flow_min_cut.html
https://jeffe.cs.illinois.edu/teaching/algorithms/book/10-maxflow.pdf
https://people.mpi-inf.mpg.de/~mehlhorn/DatAlg/Maxflow.pdf

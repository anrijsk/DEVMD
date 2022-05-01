16.
git log --relative-date --since=1.weeks
git log --since=2022.04.24

17.
c:\Users\anrijs.krasts\Documents\GitHub\git_repos\projektu>git log --author="Laura Pacilio"
commit 78f90a64b5d4f615efdcbdb92d88291012aba7c4
Merge: f19848bab 2928967b4
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Apr 29 11:58:17 2022 -0400

    Merge pull request #30956 from tigerblue77/patch-1

    Update apt.mdx

commit e68ad5ec463fbfa2a9c19abc54f60efb4b779141 (origin/update-TF-WORKSPACE-variable)
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:57:50 2022 -0400

    more edits

commit 912e6ff6de5d79bdd5e0ea3672817be3f12d9779
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:54:50 2022 -0400

    Apply suggestions from PR review

commit a0ebb94fb598a5822fdab6c6575fae55f3a8efff
Merge: 201c9168f 2f7aa2fcb
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:40:26 2022 -0400

    Merge branch 'main' into update-TF-WORKSPACE-variable

commit d3e660d91272c239350f0cf9a01ca94c7437f775
Merge: eb2724d37 b1d933936
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 12:25:43 2022 -0400

    Merge pull request #30772 from hashicorp/laura-update-pre-post-conditions

    [WIP] Preconditions and Postconditions Content Updates

commit b1d9339368563b3e76e0b71fd200cafb02870853 (origin/laura-update-pre-post-conditions)
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 12:19:29 2022 -0400

    Final formatting nits

commit 3c7c5bbd21dc32fa650c2b3505c77315838421aa
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 12:06:50 2022 -0400

    add links to function and expressions; move result types back to conditionals page (oops)

18.
c:\Users\anrijs.krasts\Documents\GitHub\git_repos\projektu>git log --author="Laura Pacilio" --since="2021.09.01" --before="2021.09.30"
commit 8f09e27597c9e792d7d9acea158429f10269572d
Merge: 5386d6c5b c8e2be76d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Sep 20 17:24:31 2021 -0400

    Merge pull request #29567 from drasko95/patch-1

    Fix a documentation typo

commit dfbef12a6ca4ba95531bef09ac6c7edc3cc2868b
Merge: 1bd5987a8 a8e5b6a4a
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 16 17:30:37 2021 -0400

    Merge pull request #29598 from hashicorp/laura-add-mrui-to-sidebar

    Add Machine-Readable UI to sidebar

commit a8e5b6a4ad1747d95a6f00acde01d68f3fc5b3b8
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 16 17:11:31 2021 -0400

    Fix alphabetical order of sidebar

commit 4d1baaceabaa968c1e5009536a70341b1657b7fe
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 16 17:06:52 2021 -0400

    Add Machine-Readable UI to sidebar and add hyphen :-)

commit dcf2d3c1efa2165cfe953794bcfcb8d074d2ed9b
Merge: 8ed9a270e f238e9395
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Sep 13 10:39:02 2021 -0400

    Merge pull request #29494 from magnetikonline/docs-s3-backend-dynamodb-partition-key

    S3 backend documentation update - DynamoDB uses Partition keys, not primary keys - redux

commit 43f960b19736cf6f7d6413a85b3d33f88a1e5a6c
Merge: 48768a003 a303a03f2
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 9 15:09:31 2021 -0400

    Merge pull request #28579 from ChadBailey/patch-2

    Added clarity: remote-exec connection requirement

commit 48768a0037c27dad8fd09de6383455ada77b9275
Merge: 64a95fc29 49b31d005
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 9 14:54:17 2021 -0400

    Merge pull request #29451 from kmadof/patch-1

    Added required paramter `resource_group_name` for MSI

commit a819d7db3ad489e91aff0f295f9d0d44b34ecc81
Merge: 1cd6c9fae b60f201ee
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 9 11:06:58 2021 -0400

    Merge pull request #29502 from hashicorp/alisdair/json-format-version

    json-output: Release format version 1.0

commit 3c518880d39b5d7abf118440241e3e26f4184a72
Merge: 1e1d47d16 e3b6c6403
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Sep 3 12:11:34 2021 -0400

    Merge pull request #29509 from drewmullen/d-module-source-revision-option

    documentation: commit sha can be passed to ref

commit 1e1d47d16d343e5bd917c24ce24d8675431435dd
Merge: 4f10de2ac fa4c590f5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Fri Sep 3 10:19:30 2021 -0400

    Merge pull request #28345 from yvespp/destroy_provisioners_doc

    document that destroy provisioners don't run with create_before_destroy

commit 73a3bb27029054a0c14f2aef8081900bf821c809
Merge: 05f21cdff b8a0929a5
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Thu Sep 2 14:47:38 2021 -0400

20.
git log --author="Laura Pacilio" --since="1 day ago"
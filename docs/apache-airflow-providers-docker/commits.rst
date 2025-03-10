
 .. Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

 ..   http://www.apache.org/licenses/LICENSE-2.0

 .. Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.


Package apache-airflow-providers-docker
------------------------------------------------------

`Docker <https://docs.docker.com/install/>`__


This is detailed commit list of changes for versions provider package: ``docker``.
For high-level changelog, see :doc:`package information including changelog <index>`.



2.4.1
.....

Latest change: 2022-02-01

================================================================================================  ===========  =======================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =======================================================================
`2f4a3d4d4 <https://github.com/apache/airflow/commit/2f4a3d4d4008a95fc36971802c514fef68e8a5d4>`_  2022-02-01   ``Fixes Docker xcom functionality (#21175)``
`cb7305321 <https://github.com/apache/airflow/commit/cb73053211367e2c2dd76d5279cdc7dc7b190124>`_  2022-01-27   ``Add optional features in providers. (#21074)``
`602abe839 <https://github.com/apache/airflow/commit/602abe8394fafe7de54df7e73af56de848cdf617>`_  2022-01-20   ``Remove ':type' lines now sphinx-autoapi supports typehints (#20951)``
`2c840670c <https://github.com/apache/airflow/commit/2c840670c03e6b4a3913454e5d5e9523e85b28e9>`_  2022-01-18   ``Rewrite the task decorator as a composition (#20868)``
================================================================================================  ===========  =======================================================================

2.4.0
.....

Latest change: 2021-12-31

================================================================================================  ===========  =========================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =========================================================================
`f77417eb0 <https://github.com/apache/airflow/commit/f77417eb0d3f12e4849d80645325c02a48829278>`_  2021-12-31   ``Fix K8S changelog to be PyPI-compatible (#20614)``
`97496ba2b <https://github.com/apache/airflow/commit/97496ba2b41063fa24393c58c5c648a0cdb5a7f8>`_  2021-12-31   ``Update documentation for provider December 2021 release (#20523)``
`83f8e178b <https://github.com/apache/airflow/commit/83f8e178ba7a3d4ca012c831a5bfc2cade9e812d>`_  2021-12-31   ``Even more typing in operators (template_fields/ext) (#20608)``
`d56e7b56b <https://github.com/apache/airflow/commit/d56e7b56bb9827daaf8890557147fd10bdf72a7e>`_  2021-12-30   ``Fix template_fields type to have MyPy friendly Sequence type (#20571)``
`a0821235f <https://github.com/apache/airflow/commit/a0821235fb6877a471973295fe42283ef452abf6>`_  2021-12-30   ``Use typed Context EVERYWHERE (#20565)``
`59e4b78da <https://github.com/apache/airflow/commit/59e4b78daa3496cb0358ce34aeb5ebf6f5565ce0>`_  2021-12-29   ``Fix MyPy errors for Airflow decorators (#20034)``
`b20e6d3f0 <https://github.com/apache/airflow/commit/b20e6d3f060bc385e350433070d5707ae6d6d0b0>`_  2021-12-14   ``Fix mypy docker provider (#20235)``
`1924e29fa <https://github.com/apache/airflow/commit/1924e29fa2ca5bdf61daec81639b9b247f1bd004>`_  2021-12-03   ``Allow DockerOperator's image to be templated (#19997)``
`853576d90 <https://github.com/apache/airflow/commit/853576d9019d2aca8de1d9c587c883dcbe95b46a>`_  2021-11-30   ``Update documentation for November 2021 provider's release (#19882)``
`aa2cb5545 <https://github.com/apache/airflow/commit/aa2cb5545f09d694b9143b323efcd4f6b6c66e60>`_  2021-11-12   ``Remove remaining 'pylint: disable' comments (#19541)``
================================================================================================  ===========  =========================================================================

2.3.0
.....

Latest change: 2021-10-29

================================================================================================  ===========  =================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =================================================================
`d9567eb10 <https://github.com/apache/airflow/commit/d9567eb106929b21329c01171fd398fbef2dc6c6>`_  2021-10-29   ``Prepare documentation for October Provider's release (#19321)``
`45c70f397 <https://github.com/apache/airflow/commit/45c70f397afc54a931bf40ceb843c7b9a9cd75e3>`_  2021-10-29   ``Add support of placement in the DockerSwarmOperator (#18990)``
`f5ad26dcd <https://github.com/apache/airflow/commit/f5ad26dcdd7bcb724992528dce71056965b94d26>`_  2021-10-21   ``Fixup string concatenations (#19099)``
`315493513 <https://github.com/apache/airflow/commit/3154935138748a8ac89aa4c8fde848e31610941b>`_  2021-10-12   ``Remove the docker timeout workaround (#18872)``
`43f334f4b <https://github.com/apache/airflow/commit/43f334f4bdedbb39f72cb28585e9500a506480e1>`_  2021-10-06   ``Move docker decorator example dag to docker provider (#18739)``
================================================================================================  ===========  =================================================================

2.2.0
.....

Latest change: 2021-09-30

================================================================================================  ===========  ======================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ======================================================================================
`840ea3efb <https://github.com/apache/airflow/commit/840ea3efb9533837e9f36b75fa527a0fbafeb23a>`_  2021-09-30   ``Update documentation for September providers release (#18613)``
`ef037e702 <https://github.com/apache/airflow/commit/ef037e702182e4370cb00c853c4fb0e246a0479c>`_  2021-09-29   ``Static start_date and default arg cleanup for misc. provider example DAGs (#18597)``
`2a3cbabbf <https://github.com/apache/airflow/commit/2a3cbabbf8a21123e0b9c35866226087c3cebc4c>`_  2021-09-23   ``Cope with '@task.docker' decorated function not returning anything (#18463)``
`a9772cf28 <https://github.com/apache/airflow/commit/a9772cf287111a63eac8c2deb1190f7054d7580f>`_  2021-09-20   ``Add a Docker Taskflow decorator (#15330)``
================================================================================================  ===========  ======================================================================================

2.1.1
.....

Latest change: 2021-08-30

================================================================================================  ===========  ============================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ============================================================================================
`0a6858847 <https://github.com/apache/airflow/commit/0a68588479e34cf175d744ea77b283d9d78ea71a>`_  2021-08-30   ``Add August 2021 Provider's documentation (#17890)``
`be75dcd39 <https://github.com/apache/airflow/commit/be75dcd39cd10264048c86e74110365bd5daf8b7>`_  2021-08-23   ``Update description about the new ''connection-types'' provider meta-data``
`76ed2a49c <https://github.com/apache/airflow/commit/76ed2a49c6cd285bf59706cf04f39a7444c382c9>`_  2021-08-19   ``Import Hooks lazily individually in providers manager (#17682)``
`4da4c186e <https://github.com/apache/airflow/commit/4da4c186ecdcdae308fe8b4a7994c21faf42bc96>`_  2021-08-19   ``Add support for configs, secrets, networks and replicas for DockerSwarmOperator (#17474)``
================================================================================================  ===========  ============================================================================================

2.1.0
.....

Latest change: 2021-07-26

================================================================================================  ===========  ===============================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ===============================================================================
`87f408b1e <https://github.com/apache/airflow/commit/87f408b1e78968580c760acb275ae5bb042161db>`_  2021-07-26   ``Prepares docs for Rc2 release of July providers (#17116)``
`b10ed95a2 <https://github.com/apache/airflow/commit/b10ed95a2aded01eb5580120ab2abbde1bac633b>`_  2021-07-26   ``Updating Docker example DAGs to use XComArgs (#16871)``
`cd3307ff2 <https://github.com/apache/airflow/commit/cd3307ff2147b170dc3feb5999edf5c8eebed4ba>`_  2021-07-26   ``fix string encoding when using xcom / json (#13536)``
`24d02bfa8 <https://github.com/apache/airflow/commit/24d02bfa840ae2a315af4280b2c185122e3c30e1>`_  2021-07-19   ``Prepares documentation for RC2 release of Docker Provider (#17066)``
`b076ac592 <https://github.com/apache/airflow/commit/b076ac5925e1a316dd6e9ad8ee4d1a2223e376ca>`_  2021-07-18   ``[FIX] Docker provider - retry docker in docker (#17061)``
`d02ded65e <https://github.com/apache/airflow/commit/d02ded65eaa7d2281e249b3fa028605d1b4c52fb>`_  2021-07-15   ``Fixed wrongly escaped characters in amazon's changelog (#17020)``
`b916b7507 <https://github.com/apache/airflow/commit/b916b7507921129dc48d6add1bdc4b923b60c9b9>`_  2021-07-15   ``Prepare documentation for July release of providers. (#17015)``
`bc004151e <https://github.com/apache/airflow/commit/bc004151ed6924ee7bec5d9d047aedb4873806da>`_  2021-07-15   ``Adds option to disable mounting temporary folder in DockerOperator (#16932)``
`866a601b7 <https://github.com/apache/airflow/commit/866a601b76e219b3c043e1dbbc8fb22300866351>`_  2021-06-28   ``Removes pylint from our toolchain (#16682)``
================================================================================================  ===========  ===============================================================================

2.0.0
.....

Latest change: 2021-06-18

================================================================================================  ===========  =================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =================================================================
`bbc627a3d <https://github.com/apache/airflow/commit/bbc627a3dab17ba4cf920dd1a26dbed6f5cebfd1>`_  2021-06-18   ``Prepares documentation for rc2 release of Providers (#16501)``
`cbf8001d7 <https://github.com/apache/airflow/commit/cbf8001d7630530773f623a786f9eb319783b33c>`_  2021-06-16   ``Synchronizes updated changelog after buggfix release (#16464)``
`8a9c33783 <https://github.com/apache/airflow/commit/8a9c3378385454f16560d82e885ebc00c5ec069c>`_  2021-06-15   ``Remove class references in changelogs (#16454)``
`1fba5402b <https://github.com/apache/airflow/commit/1fba5402bb14b3ffa6429fdc683121935f88472f>`_  2021-06-15   ``More documentation update for June providers release (#16405)``
`9c94b72d4 <https://github.com/apache/airflow/commit/9c94b72d440b18a9e42123d20d48b951712038f9>`_  2021-06-07   ``Updated documentation for June 2021 provider release (#16294)``
`12995cfb9 <https://github.com/apache/airflow/commit/12995cfb9a90d1f93511a4a4ab692323e62cc318>`_  2021-05-17   ``Replace DockerOperator's 'volumes' arg for 'mounts' (#15843)``
`37681bca0 <https://github.com/apache/airflow/commit/37681bca0081dd228ac4047c17631867bba7a66f>`_  2021-05-07   ``Auto-apply apply_default decorator (#15667)``
================================================================================================  ===========  =================================================================

1.2.0
.....

Latest change: 2021-05-01

================================================================================================  ===========  ======================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ======================================================================
`807ad32ce <https://github.com/apache/airflow/commit/807ad32ce59e001cb3532d98a05fa7d0d7fabb95>`_  2021-05-01   ``Prepares provider release after PIP 21 compatibility (#15576)``
`5b2fe0e74 <https://github.com/apache/airflow/commit/5b2fe0e74013cd08d1f76f5c115f2c8f990ff9bc>`_  2021-04-27   ``Add Connection Documentation for Popular Providers (#15393)``
`594d93d3b <https://github.com/apache/airflow/commit/594d93d3b0882132615ec26770ea77ff6aac5dff>`_  2021-04-09   ``Entrypoint support in docker operator (#14642)``
`566127308 <https://github.com/apache/airflow/commit/566127308f283e2eff29e8a7fbfb01f17a1cd18a>`_  2021-04-08   ``Add PythonVirtualenvDecorator to Taskflow API (#14761)``
`ab4771769 <https://github.com/apache/airflow/commit/ab477176998090e8fb94d6f0e6bf056bad2da441>`_  2021-04-07   ``Support all terminus task states in Docker Swarm Operator (#14960)``
================================================================================================  ===========  ======================================================================

1.1.0
.....

Latest change: 2021-04-06

================================================================================================  ===========  =============================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =============================================================================
`042be2e4e <https://github.com/apache/airflow/commit/042be2e4e06b988f5ba2dc146f53774dabc8b76b>`_  2021-04-06   ``Updated documentation for provider packages before April release (#15236)``
`68e4c4dcb <https://github.com/apache/airflow/commit/68e4c4dcb0416eb51a7011a3bb040f1e23d7bba8>`_  2021-03-20   ``Remove Backport Providers (#14886)``
`3064bf044 <https://github.com/apache/airflow/commit/3064bf04429f86ff2b527704603ef3ca9b9fe22f>`_  2021-03-02   ``Add privileged option in DockerOperator (#14157)``
================================================================================================  ===========  =============================================================================

1.0.2
.....

Latest change: 2021-02-27

================================================================================================  ===========  =======================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =======================================================================
`589d6dec9 <https://github.com/apache/airflow/commit/589d6dec922565897785bcbc5ac6bb3b973d7f5d>`_  2021-02-27   ``Prepare to release the next wave of providers: (#14487)``
`10343ec29 <https://github.com/apache/airflow/commit/10343ec29f8f0abc5b932ba26faf49bc63c6bcda>`_  2021-02-05   ``Corrections in docs and tools after releasing provider RCs (#14082)``
================================================================================================  ===========  =======================================================================

1.0.1
.....

Latest change: 2021-02-04

================================================================================================  ===========  ==============================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ==============================================================================
`88bdcfa0d <https://github.com/apache/airflow/commit/88bdcfa0df5bcb4c489486e05826544b428c8f43>`_  2021-02-04   ``Prepare to release a new wave of providers. (#14013)``
`ac2f72c98 <https://github.com/apache/airflow/commit/ac2f72c98dc0821b33721054588adbf2bb53bb0b>`_  2021-02-01   ``Implement provider versioning tools (#13767)``
`ba54afe58 <https://github.com/apache/airflow/commit/ba54afe58b7cbd3711aca23252027fbd034cca41>`_  2021-01-31   ``Remove failed DockerOperator tasks with auto_remove=True (#13532) (#13993)``
`25d68a7a9 <https://github.com/apache/airflow/commit/25d68a7a9e0b4481486552ece9e77bcaabfa4de2>`_  2021-01-30   ``Fix error on DockerSwarmOperator with auto_remove True (#13532) (#13852)``
`a9ac2b040 <https://github.com/apache/airflow/commit/a9ac2b040b64de1aa5d9c2b9def33334e36a8d22>`_  2021-01-23   ``Switch to f-strings using flynt. (#13732)``
`3fd5ef355 <https://github.com/apache/airflow/commit/3fd5ef355556cf0ad7896bb570bbe4b2eabbf46e>`_  2021-01-21   ``Add missing logos for integrations (#13717)``
`295d66f91 <https://github.com/apache/airflow/commit/295d66f91446a69610576d040ba687b38f1c5d0a>`_  2020-12-30   ``Fix Grammar in PIP warning (#13380)``
`6cf76d7ac <https://github.com/apache/airflow/commit/6cf76d7ac01270930de7f105fb26428763ee1d4e>`_  2020-12-18   ``Fix typo in pip upgrade command :( (#13148)``
================================================================================================  ===========  ==============================================================================

1.0.0
.....

Latest change: 2020-12-09

================================================================================================  ===========  ======================================================================================================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ======================================================================================================================================================================
`32971a1a2 <https://github.com/apache/airflow/commit/32971a1a2de1db0b4f7442ed26facdf8d3b7a36f>`_  2020-12-09   ``Updates providers versions to 1.0.0 (#12955)``
`b40dffa08 <https://github.com/apache/airflow/commit/b40dffa08547b610162f8cacfa75847f3c4ca364>`_  2020-12-08   ``Rename remaing modules to match AIP-21 (#12917)``
`9b39f2478 <https://github.com/apache/airflow/commit/9b39f24780e85f859236672e9060b2fbeee81b36>`_  2020-12-08   ``Add support for dynamic connection form fields per provider (#12558)``
`6b339c70c <https://github.com/apache/airflow/commit/6b339c70c45a2bad0e1e2c3f6638f4c59475569e>`_  2020-12-03   ``Avoid log spam & have more meaningful log when pull image in DockerOperator (#12763)``
`2037303ee <https://github.com/apache/airflow/commit/2037303eef93fd36ab13746b045d1c1fee6aa143>`_  2020-11-29   ``Adds support for Connection/Hook discovery from providers (#12466)``
`c34ef853c <https://github.com/apache/airflow/commit/c34ef853c890e08f5468183c03dc8f3f3ce84af2>`_  2020-11-20   ``Separate out documentation building per provider  (#12444)``
`008035450 <https://github.com/apache/airflow/commit/00803545023b096b8db4fbd6eb473843096d7ce4>`_  2020-11-18   ``Update provider READMEs for 1.0.0b2 batch release (#12449)``
`ae7cb4a1e <https://github.com/apache/airflow/commit/ae7cb4a1e2a96351f1976cf5832615e24863e05d>`_  2020-11-17   ``Update wrong commit hash in backport provider changes (#12390)``
`6889a333c <https://github.com/apache/airflow/commit/6889a333cff001727eb0a66e375544a28c9a5f03>`_  2020-11-15   ``Improvements for operators and hooks ref docs (#12366)``
`7825e8f59 <https://github.com/apache/airflow/commit/7825e8f59034645ab3247229be83a3aa90baece1>`_  2020-11-13   ``Docs installation improvements (#12304)``
`85a18e13d <https://github.com/apache/airflow/commit/85a18e13d9dec84275283ff69e34704b60d54a75>`_  2020-11-09   ``Point at pypi project pages for cross-dependency of provider packages (#12212)``
`59eb5de78 <https://github.com/apache/airflow/commit/59eb5de78c70ee9c7ae6e4cba5c7a2babb8103ca>`_  2020-11-09   ``Update provider READMEs for up-coming 1.0.0beta1 releases (#12206)``
`b2a28d159 <https://github.com/apache/airflow/commit/b2a28d1590410630d66966aa1f2b2a049a8c3b32>`_  2020-11-09   ``Moves provider packages scripts to dev (#12082)``
`4e8f9cc8d <https://github.com/apache/airflow/commit/4e8f9cc8d02b29c325b8a5a76b4837671bdf5f68>`_  2020-11-03   ``Enable Black - Python Auto Formmatter (#9550)``
`8c42cf1b0 <https://github.com/apache/airflow/commit/8c42cf1b00c90f0d7f11b8a3a455381de8e003c5>`_  2020-11-03   ``Use PyUpgrade to use Python 3.6 features (#11447)``
`0314a3a21 <https://github.com/apache/airflow/commit/0314a3a218f864f78ec260cc66134e7acae34bc5>`_  2020-11-01   ``Allow airflow.providers to be installed in multiple python folders (#10806)``
`5a439e84e <https://github.com/apache/airflow/commit/5a439e84eb6c0544dc6c3d6a9f4ceeb2172cd5d0>`_  2020-10-26   ``Prepare providers release 0.0.2a1 (#11855)``
`872b1566a <https://github.com/apache/airflow/commit/872b1566a11cb73297e657ff325161721b296574>`_  2020-10-25   ``Generated backport providers readmes/setup for 2020.10.29 (#11826)``
`349b0811c <https://github.com/apache/airflow/commit/349b0811c3022605426ba57d30936240a7c2848a>`_  2020-10-20   ``Add D200 pydocstyle check (#11688)``
`16e712971 <https://github.com/apache/airflow/commit/16e7129719f1c0940aef2a93bed81368e997a746>`_  2020-10-13   ``Added support for provider packages for Airflow 2.0 (#11487)``
`0a0e1af80 <https://github.com/apache/airflow/commit/0a0e1af80038ef89974c3c8444461fe867945daa>`_  2020-10-03   ``Fix Broken Markdown links in Providers README TOC (#11249)``
`ca4238eb4 <https://github.com/apache/airflow/commit/ca4238eb4d9a2aef70eb641343f59ee706d27d13>`_  2020-10-02   ``Fixed month in backport packages to October (#11242)``
`5220e4c38 <https://github.com/apache/airflow/commit/5220e4c3848a2d2c81c266ef939709df9ce581c5>`_  2020-10-02   ``Prepare Backport release 2020.09.07 (#11238)``
`e3f96ce7a <https://github.com/apache/airflow/commit/e3f96ce7a8ac098aeef5e9930e6de6c428274d57>`_  2020-09-24   ``Fix incorrect Usage of Optional[bool] (#11138)``
`2e56ee7b2 <https://github.com/apache/airflow/commit/2e56ee7b2283d9413cab6939ffbe241c154b39e2>`_  2020-08-27   ``DockerOperator extra_hosts argument support added (#10546)``
`fdd9b6f65 <https://github.com/apache/airflow/commit/fdd9b6f65b608c516b8a062b058972d9a45ec9e3>`_  2020-08-25   ``Enable Black on Providers Packages (#10543)``
`3696c34c2 <https://github.com/apache/airflow/commit/3696c34c28c6bc7b442deab999d9ecba24ed0e34>`_  2020-08-24   ``Fix typo in the word "release" (#10528)``
`2f2d8dbfa <https://github.com/apache/airflow/commit/2f2d8dbfafefb4be3dd80f22f31c649c8498f148>`_  2020-08-25   ``Remove all "noinspection" comments native to IntelliJ (#10525)``
`ee7ca128a <https://github.com/apache/airflow/commit/ee7ca128a17937313566f2badb6cc569c614db94>`_  2020-08-22   ``Fix broken Markdown refernces in Providers README (#10483)``
`cdec30125 <https://github.com/apache/airflow/commit/cdec3012542b45d23a05f62d69110944ba542e2a>`_  2020-08-07   ``Add correct signature to all operators and sensors (#10205)``
`d79e7221d <https://github.com/apache/airflow/commit/d79e7221de76f01b5cd36c15224b59e8bb451c90>`_  2020-08-06   ``Type annotation for Docker operator (#9733)``
`aeea71274 <https://github.com/apache/airflow/commit/aeea71274d4527ff2351102e94aa38bda6099e7f>`_  2020-08-02   ``Remove 'args' parameter from provider operator constructors (#10097)``
`7d24b088c <https://github.com/apache/airflow/commit/7d24b088cd736cfa18f9214e4c9d6ce2d5865f3d>`_  2020-07-25   ``Stop using start_date in default_args in example_dags (2) (#9985)``
`c2db0dfeb <https://github.com/apache/airflow/commit/c2db0dfeb13ee679bf4d7b57874f0fcb39c0f0ed>`_  2020-07-22   ``More strict rules in mypy (#9705) (#9906)``
`5d61580c5 <https://github.com/apache/airflow/commit/5d61580c572118ed97b9ff32d7e3684be1fcb755>`_  2020-06-21   ``Enable 'Public function Missing Docstrings' PyDocStyle Check (#9463)``
`d0e7db402 <https://github.com/apache/airflow/commit/d0e7db4024806af35e3c9a2cae460fdeedd4d2ec>`_  2020-06-19   ``Fixed release number for fresh release (#9408)``
`12af6a080 <https://github.com/apache/airflow/commit/12af6a08009b8776e00d8a0aab92363eb8c4e8b1>`_  2020-06-19   ``Final cleanup for 2020.6.23rc1 release preparation (#9404)``
`c7e5bce57 <https://github.com/apache/airflow/commit/c7e5bce57fe7f51cefce4f8a41ce408ac5675d13>`_  2020-06-19   ``Prepare backport release candidate for 2020.6.23rc1 (#9370)``
`f6bd817a3 <https://github.com/apache/airflow/commit/f6bd817a3aac0a16430fc2e3d59c1f17a69a15ac>`_  2020-06-16   ``Introduce 'transfers' packages (#9320)``
`4a74cf1a3 <https://github.com/apache/airflow/commit/4a74cf1a34cf20e49383f27e7cdc3ae80b9b0cde>`_  2020-06-08   ``Fix xcom in DockerOperator when auto_remove is used (#9173)``
`b4b84a193 <https://github.com/apache/airflow/commit/b4b84a1933d055a2803b80b990482a7257a203ff>`_  2020-06-07   ``Add kernel capabilities in DockerOperator(#9142)``
`0b0e4f7a4 <https://github.com/apache/airflow/commit/0b0e4f7a4cceff3efe15161fb40b984782760a34>`_  2020-05-26   ``Preparing for RC3 relase of backports (#9026)``
`00642a46d <https://github.com/apache/airflow/commit/00642a46d019870c4decb3d0e47c01d6a25cb88c>`_  2020-05-26   ``Fixed name of 20 remaining wrongly named operators. (#8994)``
`375d1ca22 <https://github.com/apache/airflow/commit/375d1ca229464617780623c61c6e8a1bf570c87f>`_  2020-05-19   ``Release candidate 2 for backport packages 2020.05.20 (#8898)``
`12c5e5d8a <https://github.com/apache/airflow/commit/12c5e5d8ae25fa633efe63ccf4db389e2b796d79>`_  2020-05-17   ``Prepare release candidate for backport packages (#8891)``
`f3521fb0e <https://github.com/apache/airflow/commit/f3521fb0e36733d8bd356123e56a453fd37a6dca>`_  2020-05-16   ``Regenerate readme files for backport package release (#8886)``
`92585ca4c <https://github.com/apache/airflow/commit/92585ca4cb375ac879f4ab331b3a063106eb7b92>`_  2020-05-15   ``Added automated release notes generation for backport operators (#8807)``
`511d98e30 <https://github.com/apache/airflow/commit/511d98e30ded2bcce9d246b358f806cea45ebcb7>`_  2020-05-01   ``[AIRFLOW-4363] Fix JSON encoding error (#8287)``
`0a1de1668 <https://github.com/apache/airflow/commit/0a1de16682da1d0a3fac668437434a72b3149fda>`_  2020-04-27   ``Stop DockerSwarmOperator from pulling Docker images (#8533)``
`3237c7e31 <https://github.com/apache/airflow/commit/3237c7e31d008f73e6ba0ecc1f2331c7c80f0e17>`_  2020-04-26   ``[AIRFLOW-5850] Capture task logs in DockerSwarmOperator (#6552)``
`9626b03d1 <https://github.com/apache/airflow/commit/9626b03d19905c6d1bfbd53064f85ffd3c39f0bf>`_  2020-03-30   ``[AIRFLOW-6574] Adding private_environment to docker operator. (#7671)``
`733d3d3c3 <https://github.com/apache/airflow/commit/733d3d3c32e0305691f82102cfc346e8e85478b0>`_  2020-03-25   ``[AIRFLOW-4363] Fix JSON encoding error (#7628)``
`4bde99f13 <https://github.com/apache/airflow/commit/4bde99f1323d72f6c84c1548079d5e98fc0a2a9a>`_  2020-03-23   ``Make airflow/providers pylint compatible (#7802)``
`cd546b664 <https://github.com/apache/airflow/commit/cd546b664fa35a2bf85acd77af578c909a327d92>`_  2020-03-23   ``Add missing call to Super class in 'cncf' & 'docker' providers (#7825)``
`3320e432a <https://github.com/apache/airflow/commit/3320e432a129476dbc1c55be3b3faa3326a635bc>`_  2020-02-24   ``[AIRFLOW-6817] Lazy-load 'airflow.DAG' to keep user-facing API untouched (#7517)``
`4d03e33c1 <https://github.com/apache/airflow/commit/4d03e33c115018e30fa413c42b16212481ad25cc>`_  2020-02-22   ``[AIRFLOW-6817] remove imports from 'airflow/__init__.py', replaced implicit imports with explicit imports, added entry to 'UPDATING.MD' - squashed/rebased (#7456)``
`dbcd3d878 <https://github.com/apache/airflow/commit/dbcd3d8787741fd8203b6d9bdbc5d1da4b10a15b>`_  2020-02-18   ``[AIRFLOW-6804] Add the basic test for all example DAGs (#7419)``
`9cbd7de6d <https://github.com/apache/airflow/commit/9cbd7de6d115795aba8bfb8addb060bfdfbdf87b>`_  2020-02-18   ``[AIRFLOW-6792] Remove _operator/_hook/_sensor in providers package and add tests (#7412)``
`97a429f9d <https://github.com/apache/airflow/commit/97a429f9d0cf740c5698060ad55f11e93cb57b55>`_  2020-02-02   ``[AIRFLOW-6714] Remove magic comments about UTF-8 (#7338)``
`83c037873 <https://github.com/apache/airflow/commit/83c037873ff694eed67ba8b30f2d9c88b2c7c6f2>`_  2020-01-30   ``[AIRFLOW-6674] Move example_dags in accordance with AIP-21 (#7287)``
`059eda05f <https://github.com/apache/airflow/commit/059eda05f82fefce4410f44f761f945a27d83daf>`_  2020-01-21   ``[AIRFLOW-6610] Move software classes to providers package (#7231)``
================================================================================================  ===========  ======================================================================================================================================================================

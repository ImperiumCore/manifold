---
id: IMP_TRI-FREE_ARCHIVE_MANIFEST
type: free_layer
formal_title: "Tribunals Determination Engine — Archive Manifest"
section: Tribunals
data_control: PUBLIC
version: "1.0.0"
snapshot: "2026-07-24T00:00:00Z"
lightning_cost_sats: 0
---
<!--
<JSON-LD>
{
  "@context": "https://schema.org",
  "@type": [
    "SoftwareSourceCode",
    "Legislation",
    "Agent"
  ],
  "name": "tribunals-archive-manifest",
  "version": "IMP-COH-100-1.0.0",
  "headline": "Tribunals Determination Engine \u2014 Archive Manifest",
  "description": "SHA-256 manifest of the Tribunals Determination Engine distribution, for independent recomputation and integrity verification.",
  "programmingLanguage": {
    "@type": "ComputerLanguage",
    "name": "Lean 4",
    "alternateName": "Axiomatic Logic"
  },
  "legislationLegalValue": "Definitive",
  "legislationJurisdiction": "Cohereon Imperium (Autonomic Namespace)",
  "author": {
    "@type": "Organization",
    "name": "Cohereon Imperium",
    "legalName": "Throne Dynamics"
  },
  "review": {
    "@type": "Review",
    "reviewAspect": "Safety Criticality",
    "reviewRating": {
      "@type": "Rating",
      "ratingValue": "1",
      "bestRating": "1",
      "description": "DO-178C Level A (Catastrophic Failure Condition Prevention)"
    }
  },
  "complianceStandards": [
    "IMP-COH-100",
    "DO-178C",
    "ISO 14971",
    "NIST-800-53"
  ],
  "dataControl": "PUBLIC",
  "license": "NO LICENSE GRANTED. ALL RIGHTS RESERVED.",
  "status": "OFFICIAL RELEASE",
  "snapshot": "2026-07-24T00:00:00Z"
}
</JSON-LD>
-->

# The Tribunals Determination Engine — Archive Manifest

The distribution comprises 239 files, all listed in the manifest and hash-verified under SHA-256. Every hash below may be recomputed independently against the distribution.

> All 239 files are listed in `MANIFEST.json` and hash-verified (`verified=true`); the manifest declares `file_count == len(files) == 239` with no exclusions.

| File | Size (bytes) | SHA-256 | In manifest | Verified |
|---|---:|---|:---:|:---:|
| `.env.example` | 376 | `da9da1efaa15531c646f5d6b1ec1d2fa49491395e7852b3b96577df600fe6ed5` | yes | yes |
| `.gitignore` | 139 | `89d82a8c7b63bda39877ccc857db50b588332f3f41ffcaa83d9e500c375e29ff` | yes | yes |
| `CONTRIBUTING.md` | 1207 | `9b2bfa236b8c4694f5fd123ccb8c1d333117801de90fb41045d9313b34b054ad` | yes | yes |
| `Dockerfile` | 644 | `59cddf7602b49217adf14558a3737e348eb3fd3f5fb4cc9bc3d245d099f850b8` | yes | yes |
| `MODEL_NEUTRALITY_AUDIT.json` | 358 | `9536757731de2e0d78b25296dbba14a35066cc0126f83ce835f24bb07e6e3bca` | yes | yes |
| `MODEL_NEUTRALITY_AUDIT.md` | 684 | `bd655e8a60ea73a8a3fa00231ac50722cadea2006f0a1f7c7fd708f30934542e` | yes | yes |
| `Makefile` | 388 | `6c40850bc8c20df71a53ec1581a2fda4d12fb2a03f91e778e43816697ea87d4c` | yes | yes |
| `README.md` | 10562 | `90f17e632bca25c1370853133e0f4dfcd9b0d395d41abbc0e7817545197c400e` | yes | yes |
| `RELEASE_NOTES_v0_9_4.md` | 1796 | `0659b80f4e809637b6e9cb2d1f1c885187c1b9884a15555d5b2f7662ec1915b6` | yes | yes |
| `START_HERE.md` | 3152 | `8a086b0a52832f54450b672751faff5d20ea25a2aa0fc528c895d26fee134f99` | yes | yes |
| `bridge_rules/accountability_package_bridge_rules.json` | 5018 | `a97eb3c6dd2890894d7d2b38531312f7a1ee0605798b5a2a0f14f2e1cc6924a0` | yes | yes |
| `bridge_rules/command_responsibility_bridge_rules.json` | 3546 | `caae8d5346ed35bd7e172f7ea48e9dbfb7990bea72b8a8906bd30dd0746e3574` | yes | yes |
| `bridge_rules/predicate_bridge_rules.json` | 3205 | `9fb4c0e139c0e8d1d2550084a3c1140a2f82d4d172089eb399f65e7acdf53e0c` | yes | yes |
| `bridge_rules/reprisal_bridge_rules.json` | 6986 | `72a19dfe4e7484e2dfb12de764d4a824eb097aae90da43a42355b2825ea280cb` | yes | yes |
| `bridge_rules/rome_offence_bridge_rules.json` | 5316 | `0592d86138f17b91ed97b204f9ca6053d8df09e1af56e9636fd45556022505ed` | yes | yes |
| `data/cases/.gitkeep` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | yes | yes |
| `docker-compose.yml` | 269 | `18462b6ec4e5ed58aeed058cefb26e7347bf6c769db8d2e30c53a5821a4d7c36` | yes | yes |
| `docs/ACCOUNTABILITY_PACKAGE_ENGINE.md` | 6854 | `8be684b28a623de2d4871cefd15be3e55de528bfa66b917a0f33bcbf26e48a5d` | yes | yes |
| `docs/ARCHITECTURE.md` | 3717 | `e09cd59c3a39617e751486d46ce5784cdfd0cce4978e9047dabccd738862d2d4` | yes | yes |
| `docs/COMMAND_RESPONSIBILITY_ENGINE.md` | 12942 | `1f54ed00fc77116222e7516b02f8bfbb3d6dab4582cf0c26a1253bb1c206807b` | yes | yes |
| `docs/DEVELOPMENT.md` | 1503 | `44ca1eedd8aa9fd286f5f9751087a30d1b2745a1b96d3024f84d8e746bcb9928` | yes | yes |
| `docs/LEGAL_INTEGRITY.md` | 3320 | `b594058520d608bcfdca566c5a18fe0499fadb7a3ecf4103eade5e11ad579450` | yes | yes |
| `docs/NOFO_REQUIREMENTS_STABILIZATION.md` | 1885 | `3f98be9b850354835381af435132e72b21fdcca67a2dc994c7f0bf06288b0bf4` | yes | yes |
| `docs/REPRISALS_ENGINE.md` | 3226 | `78023274e1d458a68d8ec77a7436c13a2ac3a08e535675cb38b5fbd8dbd624e7` | yes | yes |
| `docs/SECURITY.md` | 891 | `e6dabf1ed390251c5b306f8529b2d82fe215aa955ac1d2db32e25e9a75a7e62b` | yes | yes |
| `engine/README.md` | 1176 | `2f1f086a44db712978689dcd7e7db072d6c5c2d82e9c49351466ea7cb18991f5` | yes | yes |
| `engine/__init__.py` | 57 | `6926c413dd3316514a6122cce4b1c9059739cb8e94c4970e809488c0c6b625cc` | yes | yes |
| `engine/accountability_engine.py` | 54006 | `99cf35119243e0af14470941d8a80d3b8e23d4d3595abef22bf76cb3274e5493` | yes | yes |
| `engine/command_responsibility_engine.py` | 41444 | `1c2c074f9f73df2978d35fd9822a71e851d5bf75b0280e2d84a68590c099af41` | yes | yes |
| `engine/engine_core.py` | 7363 | `e45409a53f812b81b74e06da7292777febe1dfb679c77d072794409c4fbd69f0` | yes | yes |
| `engine/niac_engine.py` | 11295 | `1bdb94ab1e47abad74bd87096e2d6222690fe93bde21c091a5b5a5440c12a5ca` | yes | yes |
| `engine/reprisal_engine.py` | 16258 | `00f43bec96c7798edee9f4e4f9544243db96617904b06e2eafdcd57f16e48eed` | yes | yes |
| `engine/rome_engine.py` | 10984 | `1a90848dd764a383c9077ea80b2e069b6c357c0b25f591bb9e04e558606931e5` | yes | yes |
| `launch_operator.bat` | 68 | `7327ab462b80174838c8d508f7b7fa319aa8b502d942690c94057e7554617656` | yes | yes |
| `launch_operator.sh` | 125 | `081d3b27f5e3d5e099e4c50dc204047610cb1494bd98dfb7863a867c3bcce448` | yes | yes |
| `operator/OPERATOR_GUIDE.md` | 1794 | `7d85a0c13d4d439b105a725da8b625e86f387870c07c90c8ec10d3342f56ce3a` | yes | yes |
| `operator/checklists/COLLECTOR_CHECKLIST.md` | 405 | `2e7bb8866f284dc96169eafe1eb7254c8a3c8c4360b6aeb50e92409f54847b22` | yes | yes |
| `operator/checklists/LEGAL_REVIEW_CHECKLIST.md` | 476 | `233598f7e47a05d65f161a0e6524c7637311bac894c5d01d52736d18c03fa81b` | yes | yes |
| `operator/checklists/RELEASE_CHECKLIST.md` | 575 | `d953dd81ab46a84e2e39419557e12c1f9a9427d5fa8dc642320ff3ea80fe3295` | yes | yes |
| `operator/niac_operator.py` | 126785 | `4f65d5b38b6083ba66e105c1fe931ede9e96f283215dd2fd969e906cd3ff3990` | yes | yes |
| `policy/accountability_package_policy.json` | 1515 | `2156ee68633b2e7780506f6e93ffa98f5d3d9f4df4078d1f5e6eb5c91c9bfd4b` | yes | yes |
| `policy/actor_identity_policy.json` | 1293 | `ee433120c645d02a1b4cf8c8fe80aa4bd79a96f117025ebb60e6d4db38ba5f2a` | yes | yes |
| `policy/command_responsibility_policy.json` | 1537 | `28f2d77dffad46609e3856dc78042c94fa39587e4859420a5d943191b36595b8` | yes | yes |
| `policy/credential_policy.json` | 2040 | `2daab479c19b03a1f636b651129f0f31823c8834c1a99f1bcffd89f28faca587` | yes | yes |
| `policy/dyad_aggregation_policy.json` | 1003 | `63705c07d14a721a23216a12c708a7a3cab6f853321de480d392d4426b134a25` | yes | yes |
| `policy/factual_adjudication_policy.json` | 1492 | `6106283380c893534bb052dab8ac60594aae687a5fbef9128b7eede6e0fc1485` | yes | yes |
| `policy/operator_role_policy.json` | 1388 | `edf04fe44d69e2eb63dfa8b7bb9ffb2a9743b35b6cbd5320fcf4313ca6b7d6db` | yes | yes |
| `policy/predicate_adjudication_policy.json` | 1048 | `84ff5735e1dc949d192b796a6bc52437b298fe3d117dfd960a59bb969a651b9c` | yes | yes |
| `policy/reprisal_classification_policy.json` | 1601 | `a36ffbae4b9bfeecfdeee7f1a62c04e3558b319c866e477e78390f7c61294281` | yes | yes |
| `policy/result_states.json` | 914 | `a140e3e27562121a6eea82d0696493056735630cd02f91eabddb7ae2781d2644` | yes | yes |
| `policy/rome_offence_classification_policy.json` | 1247 | `a6f1d59b427a2ffb3fc5e22f99cf9aabe2987883e536fee320a7c44a4f92a545` | yes | yes |
| `policy/source_independence_policy.json` | 1151 | `2a3b7434db15892ee09b5b5ff22c38bcc2d574577923a1c75c5ee42e506efa24` | yes | yes |
| `policy/temporal_slicing_policy.json` | 1313 | `af11cbfd1442018a99f3cf31da506f4fa36a2fb1e09d9d2ea3b5755d625c52a2` | yes | yes |
| `proposals/.gitkeep` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | yes | yes |
| `proposals/PROP_DV1_7031C_AUTHORITY_NAME_CORRECTION_v0_8_4.json` | 4109 | `1b99911f90c7052f9f00b4753bb9eed68fbac7ac36bfbb5cc52f27519e09bff7` | yes | yes |
| `pyproject.toml` | 1257 | `200b1c487236733a3f6f310765ff7a7604ead162fd92ca7a2cc36b7ed584d07d` | yes | yes |
| `release_artifacts/ACCOUNTABILITY_CORRECTION_REPORT_v0_9_4.md` | 2265 | `ade0f297f6cf97e05d62e9d0da56cea0128cf448ee274da6e54a3e7c82202fcb` | yes | yes |
| `release_artifacts/ACCOUNTABILITY_PRIMARY_INSTRUMENT_MATRIX_v0_9_4.md` | 6621 | `9ff8b4190bbb3ca090c41051efb8d779d6228c247de70aef4ddf50718a51fc53` | yes | yes |
| `release_artifacts/ACCOUNTABILITY_ROOT_CAUSE_AND_BLAST_RADIUS_v0_9_4.md` | 9120 | `7a6cdfdf6952cfaab109075d0fbb2fcc63a9756db508980b4cd047b5391b03c4` | yes | yes |
| `release_artifacts/RELEASE_NOTES_v0_9_4.md` | 1796 | `0659b80f4e809637b6e9cb2d1f1c885187c1b9884a15555d5b2f7662ec1915b6` | yes | yes |
| `release_artifacts/accountability_mutation_fuzz_v0_9_4.json` | 970 | `254c23063cf32a6a76d94aa7e6f8405d5dc88c4834da134aabd522c2bcdae84f` | yes | yes |
| `release_artifacts/accountability_registry_correction_equivalence_by_sha_v0_9_4.json` | 4200 | `1698ba9224100642845765518ac0d3af31ed5c96cfb90bf56a254847bc99c9b1` | yes | yes |
| `release_artifacts/command_accountability_bridge_mutation_fuzz_v0_9_4.json` | 938 | `9d123267f81f8586b60636ceae72f5932cb541c75277f18480786754ec66847c` | yes | yes |
| `release_artifacts/command_engine_integrity_audit_v0_9_4.json` | 19481 | `f36b0d595a042ac7ffc4668ff49a597d2723651f6641d509320cbc9a27e8f66a` | yes | yes |
| `release_artifacts/command_engine_mutation_fuzz_v0_9_4.json` | 932 | `0f4257c763da12581fcfeb9a9a6e6218b480bb8dab43bb2d80d1dc061ff4e0d5` | yes | yes |
| `release_artifacts/conformance_replay_v0_9_4.json` | 40597 | `2c499a051410f6a7006f3c5df36e25ed99bc167eedf495ba90c28fadbb5a0875` | yes | yes |
| `release_artifacts/family_authority_grounding_audit_v0_9_4.json` | 14049 | `6e66e0b429beb2fecdd9ba16969435e5ff21392446b95a3c3d978da141406153` | yes | yes |
| `release_artifacts/javascript_syntax_v0_9_4.json` | 219 | `a7720164983df628452a951e81ac165065083ad87fc854a99680c7c92cda9a9f` | yes | yes |
| `release_artifacts/legal_citation_audit_v0_9_4.json` | 54406 | `e11e4093cb77ac70c6a7a8e000630baff2b10c875ec153e2ceb65c0367140df3` | yes | yes |
| `release_artifacts/package_hygiene_v0_9_4.json` | 115 | `37f886bd1f519b39b34770982741de033717405ac8b4d96e576dd6e103ab2e6b` | yes | yes |
| `release_artifacts/pytest_collection_v0_9_4.txt` | 760 | `e1f98ae17f9a2b99ef6c8d6d87acc2579dbce6c0c8c7d0cb50c3d46fd22573d6` | yes | yes |
| `release_artifacts/pytest_v0_9_4.txt` | 201 | `490b63ce94fb5a8b35cb58b2f9f3356b9a426bd9e27d4e78faf8d8c8014a7ff8` | yes | yes |
| `release_artifacts/python_compilation_v0_9_4.json` | 212 | `7c4674ebefce6a51c8746d8480e919f41b394736ab7a347ebc150262bde7ea90` | yes | yes |
| `release_artifacts/registry_provenance_audit_v0_9_4.json` | 9528 | `4e6a75bbf449656f0395790b2931f5eea53d0a75fd1d6ffa0c3f2c180b4ec13b` | yes | yes |
| `release_artifacts/retired_accountability_family_removal_audit_v0_9_4.json` | 383 | `4da69f1ea721ec2e80286cc7446055c20b889776179af43ae82fe6eef351fc34` | yes | yes |
| `release_artifacts/ruff_availability_v0_9_4.json` | 229 | `a5b88be4912f4fb2ba7d9c35441ceac5d8ec7e57756ded11790380be4322c411` | yes | yes |
| `release_artifacts/unaffected_five_engine_compatibility_v0_9_4.json` | 44263 | `fb92fba906e11a41d8914658ea1708428f6044605b8126181fa487781252fcb4` | yes | yes |
| `release_artifacts/v0_8_4_non_accountability_compatibility_replay_v0_9_4.json` | 31316 | `a8bddac045970305639a2016e5cff93e1161305bc262ca73eebf698f7f5b0da0` | yes | yes |
| `release_artifacts/v0_9_3_unaffected_engines_compatibility_replay_v0_9_4.json` | 37189 | `40b53d56706df13b4027ab8f7e6bc9392f5bd1250638bf833f2802c918a8e859` | yes | yes |
| `release_artifacts/validation_summary_v0_9_4.json` | 224368 | `be818ba233aa49f9c007427fa3beb18a75b8aa360c27d005335f240026199a0f` | yes | yes |
| `requirements-dev.txt` | 62 | `a989ffc4dca35d761007b71226783f536a9cb19096f51cede10f2999a3e49098` | yes | yes |
| `requirements.txt` | 73 | `3a8efb5f6971daf264861cf9979b882f0cb847518d33b3702c8c92da6fc4fff1` | yes | yes |
| `rule_families/README.md` | 1072 | `4d3708253c4a8b998d04199e8c60840bed42e700fdde92f4e4f86da64977d604` | yes | yes |
| `rule_families/REGISTRY_CHANGELOG.json` | 3783 | `e9e21e961f7839ebb716cb21382a9184e8c9f3d57f68bb0df1bb243ca5992fa5` | yes | yes |
| `rule_families/REGISTRY_INDEX.json` | 3089 | `fe995552cb44ba6e0a977c18bb4cae4d47e1e6eaa493f358459e076b4a911fb4` | yes | yes |
| `rule_families/REGISTRY_VERSION_HISTORY.json` | 2674 | `3e247230c28a7f9338cffe2b5baa394b332516f3bf374119066213cf98d866c9` | yes | yes |
| `rule_families/accountability_package_rule_families.json` | 84408 | `a54ca1101d9c6995d373e6ccef6fce70f294bc01739ed1613790b989236a94e8` | yes | yes |
| `rule_families/accountability_package_rule_families.json.sha256` | 108 | `ac63a23da80a3ba3bdc07e591907676d78db5878c7caeef3ec0d4a7fa70223a8` | yes | yes |
| `rule_families/article6_rule_families.json` | 29529 | `24e44c4b8eae29f1b40e754200ce898ded8025d01e356761bd08933e0ddda503` | yes | yes |
| `rule_families/article6_rule_families.json.sha256` | 94 | `801eee53b5560f03eea4767db181252c91f2cea69f5c454b7d9d6fec268f07f6` | yes | yes |
| `rule_families/article7_rule_families.json` | 129594 | `4abc06c83385598f59dba6c7809f9c4b38344d20c3dbb92109a347b19c198126` | yes | yes |
| `rule_families/article7_rule_families.json.sha256` | 94 | `52c4c93da8b4f3ce6e5c5274f1768533e2ddb0cf5ff418df077fa00895f9f377` | yes | yes |
| `rule_families/command_responsibility_rule_families.json` | 132788 | `3374e54b13f3678e469b67c8cae5e3bdf1042f60a69532640f9ddd392bbf1383` | yes | yes |
| `rule_families/command_responsibility_rule_families.json.sha256` | 108 | `24fb35a0d4f7777f592c12daf9a98a5d424924eb3c7ec878f7f2fa3d0f3d2b8a` | yes | yes |
| `rule_families/identities/accountability_package_rule_families.identity.json` | 473 | `74937624c269e9f7f6ecc51e2080150de67cbd4514eecf8184bf507ed92eb2f2` | yes | yes |
| `rule_families/identities/article6_rule_families.identity.json` | 414 | `e2394b6d10dbc6189494cdc030cc163d45eac17edd6d0257c599fddc100e96ce` | yes | yes |
| `rule_families/identities/article7_rule_families.identity.json` | 414 | `f1a9a9b0bc3772495010b15af414f4906c44e0c6e14d9cd9d0be3aaf8c01e4e4` | yes | yes |
| `rule_families/identities/command_responsibility_rule_families.identity.json` | 458 | `6e82d911afc3f6f9f2d2e5d9f8437f7588e7379065ef2007450601ad8dbd285c` | yes | yes |
| `rule_families/identities/niac_rule_families.identity.json` | 400 | `c96fecf49e35dca46b45a338b9eb72ea579397f14e5df4de1789180738e7ee61` | yes | yes |
| `rule_families/identities/reprisal_rule_families.identity.json` | 412 | `853dbce7d264b2296fa904cb6ff60456f2584f6b729f154de6d1e8172fb27e99` | yes | yes |
| `rule_families/niac_rule_families.json` | 31012 | `116e2684a8f86046dd85c5c1850c5c7e3a3bc9ce9f94a871d044898e367182b9` | yes | yes |
| `rule_families/niac_rule_families.json.sha256` | 90 | `ef4e260281ad5b10d071f4a634d8ad8a5773ab931d85aacbb8cdabbae8c7ecba` | yes | yes |
| `rule_families/reprisal_rule_families.json` | 101718 | `c15058204699cce20f261e9cb9d71cb57d16b93b2b8bee05a9eae86fc1da24ca` | yes | yes |
| `rule_families/reprisal_rule_families.json.sha256` | 94 | `db588e32158245cf0a5a0cb2960bf6f92fadce5538e30c4f3b7d50eb37c29344` | yes | yes |
| `run_web.bat` | 64 | `ba420422292e7407c6c86a8a601afc32fa1ac900e51132936e71d1b22bd23526` | yes | yes |
| `run_web.sh` | 120 | `3ee103acdf75a21d8796732ca476b28679bdac3cc3e8dfdbe04943e8c0df2e04` | yes | yes |
| `samples/core_records.json` | 4697 | `8213f6876b797681b159834fc08157d725a7099d5a1567297c1f49def4b52214` | yes | yes |
| `samples/synthetic_factual_scenario.json` | 15940 | `bbf49bac355c52820f408fbbd2c6a28a67e1cb81c405120810e4c7605db52089` | yes | yes |
| `samples/synthetic_factual_scenario_output.json` | 3223 | `0e033058282fd828826bb4d08110d8ba1822264eab4d106bada44213dba577e5` | yes | yes |
| `schemas/accountability_package_unit.schema.json` | 1887 | `33868767c8c4e6145096c3b9debf329f54674abab4b85bfc080b1e1cfb032f25` | yes | yes |
| `schemas/accountability_predicate_adjudication.schema.json` | 1201 | `20aaf5a71f4f914500f8fc90a9628da733371a0ea983a0290ada5017034ad786` | yes | yes |
| `schemas/accountability_target.schema.json` | 904 | `f8a445eded8d28c4ef4707d8d13b6413ad5e3ed6fe384a9a5ac28c26e7315f78` | yes | yes |
| `schemas/actor_entity.schema.json` | 3400 | `e4bff05c4dfdc4b44127b8c30cc7f4d5b9ebfdacc1a6eadb79119bb6a94165ed` | yes | yes |
| `schemas/actor_relation.schema.json` | 1800 | `cd9b2679113de087295571f5f80f8d58bc8ab9f708ac022cb969b5fcafb3067d` | yes | yes |
| `schemas/authority_record.schema.json` | 5402 | `5dc037eabf40a8463ea12f3720fad9fa72a3bac17293e5bb11dfd647aa65b33c` | yes | yes |
| `schemas/challenge.schema.json` | 1721 | `1588c140e36cfbd790c897f9264daf62f8714190db157d501d1228c62e255c1f` | yes | yes |
| `schemas/command_responsibility_predicate_adjudication.schema.json` | 2019 | `1c7670486ab83e8798375e8c74ae11edb69e402bd6f8fbe49f17bb855a778883` | yes | yes |
| `schemas/command_responsibility_unit.schema.json` | 3409 | `35492fca2e65e1871611644052938b0bebbc43fa8cadff535aae784c9d58a00f` | yes | yes |
| `schemas/determination.schema.json` | 2923 | `838f30a49e2286330b1282f2691ce8e6ee0a481741b3415efd6020d31026a4b0` | yes | yes |
| `schemas/dyad_record.schema.json` | 1670 | `8fa55b00fe3b577212df59752f7e8a9f67fb5f3926bc11cd5a90a632434ba5ce` | yes | yes |
| `schemas/evaluation_run.schema.json` | 1277 | `a02e4d00e957808d32afc55e4d61306073f5f9eb5032e8b3f313e2f8c146f72a` | yes | yes |
| `schemas/event_record.schema.json` | 6460 | `089149c087cec082e17ed6029741cd8c7718e0320c4b95fb450574d8c94c4754` | yes | yes |
| `schemas/evidence_item.schema.json` | 2995 | `74ec2cf095a53dd6f5a7e83b1f21c718f825c1b2af66712a9bacd73dd57a6cbd` | yes | yes |
| `schemas/indicator_finding.schema.json` | 2032 | `4fee8bdb2d74f4859a514e55c27c19e66435704ec75a0563cdca70e9532ceb3b` | yes | yes |
| `schemas/interval_record.schema.json` | 1506 | `6935cf4fc474b2f5fd385353f98dd908ab61c736208fcbc8ba85a465c1c5bfc7` | yes | yes |
| `schemas/legal_rule.schema.json` | 2453 | `c8f43aea3ae1fcf1dfe1d55dbcdf188672cd36f27c2beaa87da944dc9d5ed8cd` | yes | yes |
| `schemas/niac_rule_family.schema.json` | 3350 | `ed1b9d6474bd65d08bd2ffb0c4f41cd80dc8a2e92cca74f318322e1f5b61b3a3` | yes | yes |
| `schemas/predicate_adjudication.schema.json` | 2051 | `fe02640e28bdd89bbc8de56907902ac8ec927952e5dae4473ca1ab8e3d7cf173` | yes | yes |
| `schemas/proposition_record.schema.json` | 2279 | `cb356d9740c47391633da9739e1e6ddb65250af1bf8a65e84ffaf6ebbc5492e9` | yes | yes |
| `schemas/release_manifest.schema.json` | 2234 | `6b587458fb2b38715c703e3bbd9f3d6d04516896faaaada16f4142d48de5f8cd` | yes | yes |
| `schemas/reprisal_predicate_adjudication.schema.json` | 1330 | `8837dfb9d0425459c7b527026eb6f4bfd06de0e2c5ce7b08cf9b53349d97227a` | yes | yes |
| `schemas/reprisal_unit.schema.json` | 1761 | `17501efa46d52239619f353338641966405dbb8d0894b1d75902404de6367c07` | yes | yes |
| `schemas/rome_element_adjudication.schema.json` | 1656 | `35dd828682ddd14eb3417346202cbec0f5540a3504274aa6053d2b3ce2e2afdf` | yes | yes |
| `schemas/rome_offence_unit.schema.json` | 1172 | `d67c3a3a01fd6fb75adb40743e6dfe72cad271da21df5a70aa773c25ee053148` | yes | yes |
| `schemas/source_lineage.schema.json` | 873 | `da336fdd8bb3a68e397cbcab17bcc58819bc609c797e505c8e09296769f8cbf8` | yes | yes |
| `sources/capture_policy.json` | 1731 | `eadead1bbefed4ce59872348d8a362208732ebf2ff1b0d89cc0d087ba6dee42d` | yes | yes |
| `sources/captures/CAP_API_1977_REPRISAL_PROHIBITIONS.json` | 1482 | `e80262c17bf7614628608cf6a6347bedf22f1405132a0127ce16c3991520f8e7` | yes | yes |
| `sources/captures/CAP_API_ARTICLES_86_87.json` | 1941 | `f32db2d5326fcf23f97e959a33c0cc6024a1c2855e6c3f979a4644a0c55f72dc` | yes | yes |
| `sources/captures/CAP_APIi_ARTICLE_1.json` | 1840 | `0b7fe699bdea513e4b31c93c2880ebad52bed5d10598faa7522e52f83b541a1e` | yes | yes |
| `sources/captures/CAP_AUSTRALIA_AUTONOMOUS_SANCTIONS_REG_6A.json` | 1773 | `69ce5e45bf7647e64e16227b4d8cd1f9111a6445e1b540df6858acb4c0ba2dc0` | yes | yes |
| `sources/captures/CAP_AUSTRALIA_CRIMINAL_CODE_268_115.json` | 1966 | `413d61c066703cccafc1a39d5bf728368dcdc0342e9c2e10580a4fedc3941fb0` | yes | yes |
| `sources/captures/CAP_AUTHORITY_SANCTIONS_PUBLIC_BASELINES.json` | 1750 | `c3f4c72c09a328f5c47be379f714e8a01db56b94946e799b93b7e76837c9bfd1` | yes | yes |
| `sources/captures/CAP_BERKELEY_PROTOCOL_FACT_METHOD.json` | 2132 | `6c792719c2449ff20c530fa3d42656508fc8429ea48be201ea9c4e8595f7c83e` | yes | yes |
| `sources/captures/CAP_BERKELEY_PROTOCOL_OSINT_DOCUMENTATION.json` | 1363 | `52397b6a3363d2740e41a8bf85b85cd39d3aea4dc34c0c2ef82a3c617828e9dc` | yes | yes |
| `sources/captures/CAP_BOSKOSKI_APPEAL_FACTORS.json` | 2188 | `635685b205815e04c5a7321029340230ec4686438967b6a0aad51c1d998d3cb7` | yes | yes |
| `sources/captures/CAP_CANADA_CAHWCA_SECTIONS_5_7.json` | 2017 | `78cca3525ac154d32c2fb88ffaaa3f7998aa854e7d5bb99951ea511218a24d89` | yes | yes |
| `sources/captures/CAP_CANADA_JVCFOA_SECTION_4.json` | 1711 | `f46fbc0ebb8d3b2ce6b8ef846811e87ce38d8a4a4bf7c546a87b2027c9772bbf` | yes | yes |
| `sources/captures/CAP_COMMAND_RESPONSIBILITY_EFFECTIVE_CONTROL_JURISPRUDENCE.json` | 1964 | `0329c61bf24682b148a9a6b9c92933e99d2b9c1a7a0979eaed2559f9bac38c7b` | yes | yes |
| `sources/captures/CAP_DRL_GLOBAL_DOCUMENTATION_ACCOUNTABILITY_NOFO_2026.json` | 1513 | `53c4ef7ad5e7ad95311aac6aa503a635ef27a4d9258998f3eca4fe3eb382486b` | yes | yes |
| `sources/captures/CAP_EU_REGULATION_2020_1998_ARTS_2_3.json` | 1666 | `7424948a60e1ad1e22501649c9d66a176248f3c9b4d9158abc1b16458b307d8c` | yes | yes |
| `sources/captures/CAP_GC_1949_REPRISAL_PROHIBITIONS.json` | 1295 | `d1fe1759e4edd8e0e23b54cf9b840799bf48b08c3a782262ecf1e9d8c9e90053` | yes | yes |
| `sources/captures/CAP_GC_COMMON_ARTICLE_3.json` | 1460 | `f90f17e6bcb2ab6b249b5b148de83ab7a50a6224f439347375a6ddee34b9944c` | yes | yes |
| `sources/captures/CAP_GERMANY_VSTGB_SECTION_4.json` | 2001 | `23edd20b0d9616a82cb5cfbc005c5366c3dbace98e8a439575f271534ee57a64` | yes | yes |
| `sources/captures/CAP_HARADINAJ_392_395.json` | 2080 | `358afa0fffd84307380b688dbd72abea59b0288e1fe34bbeb7d22463a1aed068` | yes | yes |
| `sources/captures/CAP_ICC_BEMBA_ARTICLE_28_APPEAL.json` | 2120 | `3d910de55acedc35db190c8a82a3806bf3e4a29382c9e1a1a258aa952a9a7fa0` | yes | yes |
| `sources/captures/CAP_ICC_ELEMENTS_ARTICLE_6.json` | 1844 | `38fbc5210f7b455ea11b3481680c8b59a4a77a15ca38ddca7bad79e9fc1989b4` | yes | yes |
| `sources/captures/CAP_ICC_ELEMENTS_ARTICLE_7.json` | 1960 | `525a48faf9cfb683291a075aa2d9aab82a022ee3fe97462e317f6b698824df5c` | yes | yes |
| `sources/captures/CAP_ICJ_STATUTE_38_59.json` | 1452 | `25987482028b68e8c8fb1491ae411cc445d815829b68b45c3efc59677024842a` | yes | yes |
| `sources/captures/CAP_ICRC_CUSTOMARY_IHL_RULE_153.json` | 1894 | `505c566e7d6eecf46f81985440ed7c42a3707dc46abaa99f7c7ce8532c3cfc15` | yes | yes |
| `sources/captures/CAP_ICRC_OPINION_2024_NIAC.json` | 1932 | `7855fefa8728b4c48620733827d0957d822f97dfc5b6f76a686cfb2921f7499c` | yes | yes |
| `sources/captures/CAP_ICRC_RULE_145_CONDITIONS.json` | 1480 | `46e47dcc2afda715e99fbc58e611d60281f3840647acac06551dc14a0e238c9a` | yes | yes |
| `sources/captures/CAP_ICRC_RULE_146_PROTECTED_PERSONS.json` | 1229 | `9ab847608a61545670b6d65bbf6e0b19d6a31df2cdb777e73ec8627020a15d61` | yes | yes |
| `sources/captures/CAP_ICRC_RULE_147_PROTECTED_OBJECTS.json` | 1240 | `db1c134f07aa84ddfa8fcfababb357403bbba91a1924b072cc49baf1cce82783` | yes | yes |
| `sources/captures/CAP_ICRC_RULE_148_NIAC.json` | 1251 | `391c66494e9d9b0869c20baeeca5cadd77c35a1fcdbf2ec5245d38f852f309e2` | yes | yes |
| `sources/captures/CAP_ICTY_KUPRESKIC_CIVILIAN_REPRISALS.json` | 1334 | `fa3284bb4a5e60c1c03ec5012780789a9081714211c4cb39013d4d5b836e5e42` | yes | yes |
| `sources/captures/CAP_ILC_COUNTERMEASURES_EXCLUSION.json` | 1436 | `d2e1d474d3e4b65ab849d2dda2edd3a0e9e96f7a877f50e8a55cfee87df4572b` | yes | yes |
| `sources/captures/CAP_ILC_CUSTOM_2018_STATUS.json` | 1657 | `35966594e12d49a7587ac14723148c6552de12981d6ed265268212bec24dcfef` | yes | yes |
| `sources/captures/CAP_ROME_ARTICLES_9_21_22_30.json` | 1765 | `d9273aa521d6b1628a73e2fdead7e9b329a5621a6dd80122bf1a491b9ee9d73f` | yes | yes |
| `sources/captures/CAP_ROME_ARTICLE_28.json` | 2088 | `dcc380861f05edad2ddfcdb6622c33d3559a5acb42139c50cb7127fb180150fc` | yes | yes |
| `sources/captures/CAP_ROME_ARTICLE_6.json` | 1646 | `76105ee11a4ee1332ef858438ede3024005651cf467eafc0f98e0f46562ef1d5` | yes | yes |
| `sources/captures/CAP_ROME_ARTICLE_7.json` | 1830 | `fd982ed82e5fea32d68cc8017c93f636947409384548b54ef96d994c8cf9e4af` | yes | yes |
| `sources/captures/CAP_ROME_ARTICLE_8_2_D_F.json` | 2085 | `6b46e51c78f5703ccab0243c287dabbc261823d2bf41d1763a75f364f74ca5ff` | yes | yes |
| `sources/captures/CAP_UK_API_REPRISAL_DECLARATION.json` | 1593 | `9345b216ca36a60a288763ddfd4fd144d91759f2305baf7cd9cb1d5437f596e4` | yes | yes |
| `sources/captures/CAP_UK_GHRS_REGULATIONS_2020_REGS_4_6.json` | 1843 | `a22e5ed428e3c0d2e82bc08399454348f85fa32389a41f8d75d7eb121c71c2af` | yes | yes |
| `sources/captures/CAP_UK_ICC_ACT_2001_SECTION_65.json` | 1863 | `6e8efe335ae6cb0bacda8f42e6fe9829684eda96a09763dfe25f66d97353a95e` | yes | yes |
| `sources/captures/CAP_UK_JSP383_REPRISAL_CONDITIONS.json` | 1499 | `99b9e42d70abc3d975d332ebc5e77b9eb8d6eab87297ab7074ee77cc5e598590` | yes | yes |
| `sources/captures/CAP_US_EO_13818_SECTION_1.json` | 1714 | `05043cf48c7822b805ae2ea6a2ee7ac71a5372dd12c7891c918867ff024bc3c1` | yes | yes |
| `sources/captures/CAP_US_PUBL_119_75_SECTION_7031C.json` | 1697 | `53831a237ed42bb92fb2b7f8582d419903d781f545561a5bc83a5ed852897bca` | yes | yes |
| `sources/captures/CAP_VCLT_SCOPE_INTERPRETATION.json` | 1530 | `f7bdca32ee7858eae69babaabb4a225d8bd8a332bb65c1245830138e9b98b93d` | yes | yes |
| `sources/foundational_source_registry.json` | 21404 | `14099579c9c13c4fba1bcd33dc87ce3ac6c263c9f1c7a05aa484e86a7e7b14ab` | yes | yes |
| `templates/actors.csv` | 71 | `5e99648e90887c66fb8ae469d87743ae93905af7c8d665f00c205e9719e96a74` | yes | yes |
| `templates/events.csv` | 154 | `0b16dca7882e942d15f1423a9d6138daeeba1ee09dceff3bce28c8ddaf1d457b` | yes | yes |
| `templates/evidence.csv` | 106 | `9be82995b7733949291353c5c8a1dcdb79c3ce33c4f4eb6935acd294bd8caddf` | yes | yes |
| `templates/scenario_template.json` | 434 | `a702d3e275a0084ae2996a175576135cf5fa2f9014faaddfa7b6eb153856f9de` | yes | yes |
| `tests/adversarial_cases.json` | 9352 | `60c422bbfa49b51d02e2df8ddec6f1751d3242008d027897157e6772f310627b` | yes | yes |
| `tests/conftest.py` | 180 | `d0a5179e44e0206108b1fd09e2ecc8c792aae09903c85a3cd4cbf4aaf2335bd9` | yes | yes |
| `tests/test_accountability_content_correction_v0_9_4.py` | 2252 | `c7095584ada0a95446bd20219836710b66362e83c0a54b74ee4b66efee2134d5` | yes | yes |
| `tests/test_accountability_engine.py` | 7051 | `23323cf954b644a7dcc96a831eec54e976400e9f573b479b540a42a394f8d3a0` | yes | yes |
| `tests/test_accountability_red_team_v0_9_2.py` | 3106 | `d33168026918fd86031095623f1a5f99945149d061bbab05c201a90f53e1c89b` | yes | yes |
| `tests/test_accountability_webapp.py` | 5079 | `c1ee382e5a9ad1b334af48c4ea79c46876d1d684848175dc37c99c9caaa099e9` | yes | yes |
| `tests/test_command_accountability_bridge_red_team_v0_9_2.py` | 20038 | `5b2ca740c15198f4ab73f887f60f1b797c3b8fe448e936324a3701a2176cbadd` | yes | yes |
| `tests/test_command_engine_integrity_audit.py` | 417 | `93ba62ed08b1baff7a9c4d281c00369b8458baa09c754d45f825792fbd40d850` | yes | yes |
| `tests/test_command_red_team_v0_9_2.py` | 21594 | `735480b6e1d54bbd5af69433dae2d0552048cc49128dc205baa934b8796bc1cb` | yes | yes |
| `tests/test_command_responsibility_engine.py` | 13848 | `186a4b1d48c3088922e2c2af5e4a2e0a64d6215181a138ac69712b8dfb670344` | yes | yes |
| `tests/test_command_responsibility_webapp.py` | 14687 | `9a40076556d0483d964daf06045610864474c3c92f15fcfe252621e7104f0b70` | yes | yes |
| `tests/test_cross_engine_bindings.py` | 3130 | `2172e34431695ca621a4c5fd7a9db22a758c183f790b6de9a31a9839894ea7bc` | yes | yes |
| `tests/test_engine_core_validation.py` | 9845 | `28b2a703cb920049121aadbd2f3418d81a39f6c9839b8ca662ec9f03efedb7e0` | yes | yes |
| `tests/test_factual_engine.py` | 4397 | `fe27c9f70ef31f489947829161180c2d831b17c247b780f6b586226153aeb373` | yes | yes |
| `tests/test_family_authority_grounding_v0_9_4.py` | 2969 | `0ecb4c652c6e192b46178f27a2717ff5bb8e33535d5826cb4f416a1c5c5067e5` | yes | yes |
| `tests/test_operator_workflow.py` | 6051 | `abd11204650a047624b15f72931a7f28e7c479eaeeb085d57688a95294161f10` | yes | yes |
| `tests/test_registry_provenance_v0_9_4.py` | 1114 | `fc7011ec707cbaee65927ce09d958b44f29e7f02560fd08df930341dd300c6f3` | yes | yes |
| `tests/test_reprisal_engine.py` | 9421 | `27b295d1d77cb728f1d44cd56657e437c109e75bbf11de71e7c850f51fdc5c6b` | yes | yes |
| `tests/test_reprisal_webapp.py` | 7519 | `073da356d812f51709118b3762129e60de79d7aefa7e4278cf6d7457038f8add` | yes | yes |
| `tests/test_rome_engines.py` | 8111 | `7303168b184c0936d4cf62ba3fd7f6de3ed12b9789d0ee766991693e36e36f0e` | yes | yes |
| `tests/test_rome_webapp.py` | 7702 | `55d2e6d70c38b801570a940cfe568983a018e0aa04558929a5be2a695643ef10` | yes | yes |
| `tests/test_webapp.py` | 8861 | `db40789a67a85ad245580dd05ff7e88227be5c498b951dcee6c13261e367ab38` | yes | yes |
| `tools/__init__.py` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` | yes | yes |
| `tools/build_conformance.py` | 3514 | `c38fec7f94fe12229d9081347c2b1229270514e181b1728c45a3e028b03df1f2` | yes | yes |
| `tools/command_accountability_bridge_mutation_fuzz.py` | 16157 | `c22981fb5feb233aace4a34dc030467d6e49e1e993a0e31bd2fd3fd0758fd3cf` | yes | yes |
| `tools/command_engine_integrity_audit.py` | 36107 | `d892822b6c5456a47269df7d3a8f980592c7f6b737c30cb572823bb67520146f` | yes | yes |
| `tools/command_engine_mutation_fuzz.py` | 12322 | `1f9ff467a903ea3ef17f6ffe5c118964565ae60f025663c6039d2af2be698e64` | yes | yes |
| `tools/conformance/README.md` | 887 | `99b5aafb81eec31e8955e6d8eff30e5eb8e95cc316718e6a1decb63458f97dd7` | yes | yes |
| `tools/conformance/compatibility/v0_8_4_non_accountability_vectors.json` | 344853 | `db4d767689b540b519a1e02a16aef64c876f5b372b6fde2cb9b3dbe97a1bf189` | yes | yes |
| `tools/conformance/compatibility/v0_9_3_unaffected_engines_vectors.json` | 507698 | `489708407e056f842cfade8ce83d994c483c935f3548ccc493524e09d7abfac3` | yes | yes |
| `tools/conformance/v0_9_4/conformance_vectors.json` | 567850 | `dc222f6995fb87cf5e0520c6bdb810eb132fc0dbece8439201b80a3caefff226` | yes | yes |
| `tools/conformance_lib.py` | 19362 | `5efcef70f10705c2838becf697934a54930b95bfd647f10bcda84fd208dc8cf2` | yes | yes |
| `tools/family_authority_grounding_audit.py` | 4511 | `7ca4b64388faf506e29a55df46ca317309548b80431e0274293bed349f2da700` | yes | yes |
| `tools/hygiene_check.py` | 1746 | `74070d28a283f3dbcbea21e92b66288c75a39e88118ec466bc3994094081f154` | yes | yes |
| `tools/legal_citation_audit.py` | 15152 | `360769c747a73bde2133396085c8cacf7119b925ec20836a6a0194f5f4d7e61d` | yes | yes |
| `tools/registry_provenance_audit.py` | 6012 | `474fba83a46ad1a18b321b464a5803b48ef58a86f3ab10b881c58cae313d6953` | yes | yes |
| `tools/replay_conformance.py` | 3328 | `81be0f4afbcabf3f27de7fa670ddcef7af35c07acab2ec6249ac8f3fa9da664e` | yes | yes |
| `tools/semantic_equivalence.py` | 3121 | `637cbf10396a2d0d64e7b7806171de92e05bb4ea26038e1214dc335cc6109f2c` | yes | yes |
| `tools/verify_release_scope.py` | 5238 | `c592763dbab4b7ca05203feaa0144f8368e4552f6a311db81b3b884ddcfe94b9` | yes | yes |
| `validator.py` | 3859 | `45e8c8994c575600966c9db727a77a05884c88bc5f01f9d1bf0de67468da5248` | yes | yes |
| `validator_core_v0_2.py` | 9147 | `6b5d2327357479230501d736e9fb2c0ba202d6c782b91c73e29d8c59de5e1b88` | yes | yes |
| `validator_core_v0_3.py` | 1319 | `b8b1b0bea8de877a19a6e5908312d561e7b6eb0d74099723c198acbf8351ac90` | yes | yes |
| `validator_core_v0_4.py` | 1068 | `876f60205b1f8e571bdcd6f23e36bc0bb5775cc84f02f7ec06c93fbd2ab985b2` | yes | yes |
| `webapp/README.md` | 1198 | `670111b90907fb3571cb5cb44fa5cfba1ab0c0570ae825a9416f6741ab033520` | yes | yes |
| `webapp/__init__.py` | 89 | `a20e44714bc6df67a184c56f8aeba30618dc90f1a9253426dcf2d67caeb449c6` | yes | yes |
| `webapp/accountability_service.py` | 17014 | `1f6eb1b9222de0b893001654947df793b821484104b24e1c2e7aaac3e76ce1e3` | yes | yes |
| `webapp/cli.py` | 648 | `591a43cceef9a4623d33b40b18c0f7896ede4151e4cda4fe0de5284781278e35` | yes | yes |
| `webapp/command_service.py` | 30631 | `4ce6971cfc83dabd0ffd53f3d4b51c271e66ec288c800ce578efe826f792f21c` | yes | yes |
| `webapp/main.py` | 24289 | `493585f2322a9de8e88e9e219ebe023ce44a3342340a9018789b7c541619581f` | yes | yes |
| `webapp/reprisal_service.py` | 19654 | `59a984a65134e8663c4f32fcc4794c7e6581992d5823d3d127d3e12723f7f3b4` | yes | yes |
| `webapp/rome_service.py` | 19895 | `4de5d3b65f76cbeafe38a80473b528cfd533ee8839670f26dabb984cdfa6ad12` | yes | yes |
| `webapp/service.py` | 35337 | `821b4cec63218d159dfdf57943b2017fa8f43216b3dad3be5b166e2aa3291f72` | yes | yes |
| `webapp/static/app.js` | 65048 | `03eb26ecae88b6764c12c18ea62e5a7015ca842f99c245abf1297282f0faaaa0` | yes | yes |
| `webapp/static/index.html` | 29943 | `4f87a330624d1661ac5fed42df4d97932985b2d94b94ba3870b4d42b8c74f204` | yes | yes |
| `webapp/static/styles.css` | 8513 | `248fe604c758f97bc231e883f1fdfbafa10400637a4be963f0840ac270408d91` | yes | yes |

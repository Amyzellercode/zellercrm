# Changelog

All notable changes to NextCRM are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.23.0](https://github.com/Amyzellercode/zellercrm/compare/v0.22.0...v0.23.0) (2026-09-23)


### Added

* add CSV/Excel export to campaign targets table ([6ba529c](https://github.com/Amyzellercode/zellercrm/commit/6ba529c723bae89af4acaa06d8699406fdb5e345))
* add CSV/Excel export to target list detail page ([24fae10](https://github.com/Amyzellercode/zellercrm/commit/24fae10a55f1ca69d05b7a7e35876f817507f9a2))
* add CSV/XLSX export utility for targets ([3a02ba8](https://github.com/Amyzellercode/zellercrm/commit/3a02ba86925e1b53df8ce1512fce2b2772f7ce62))
* add Docker entrypoint script for auto-initialization ([7a25fe1](https://github.com/Amyzellercode/zellercrm/commit/7a25fe155f0cabb3110dee178a135c90998ac467))
* add docker-compose.yml with all services ([4b7c73b](https://github.com/Amyzellercode/zellercrm/commit/4b7c73bf75fc25c7846212f878d265d2b2fb8e3d))
* add Mailtrap email provider helper ([74847d7](https://github.com/Amyzellercode/zellercrm/commit/74847d7e691eb917022d91cfb8556ea7a92011bd))
* add Mailtrap sandbox email testing provider ([569b46c](https://github.com/Amyzellercode/zellercrm/commit/569b46cfe138630bcfd2bbae97ebb0c6d5736f95))
* add multi-stage Dockerfile for NextCRM ([8a363d9](https://github.com/Amyzellercode/zellercrm/commit/8a363d99e7675faa1ae607f8b7390fa381ea211b))
* add real sending capability to Mailtrap helper ([5a7d9ed](https://github.com/Amyzellercode/zellercrm/commit/5a7d9ed2fa16a450d7a6afd5aed4a81995ad9d70))
* **admin:** connect automation trigger kinds to sales stages in CRM settings ([166c0d4](https://github.com/Amyzellercode/zellercrm/commit/166c0d424a7f80d5c07b16511aa6dff4fccaa1f9))
* **admin:** instance-grade funnel timing settings page ([9b39cba](https://github.com/Amyzellercode/zellercrm/commit/9b39cbafd3819ca47096982c04b7a6deadc79afa))
* **admin:** mount Resend service card at /admin/services ([9f235e2](https://github.com/Amyzellercode/zellercrm/commit/9f235e2412ea38b2149d49db0c84ed2b3db15e65))
* AQUNAMA Phase 1 — global email opt-out, target-to-deal conversion, delivery deadline, XLSX import ([f97b13c](https://github.com/Amyzellercode/zellercrm/commit/f97b13c1fd71fefc6b3371ccc4ffe46847ffa276))
* AQUNAMA Phase 2 — funnel timer & task engine (kill rule, cadence, care, recycle, renewals) ([75b8ae8](https://github.com/Amyzellercode/zellercrm/commit/75b8ae81d0f15b8ee9fffe2dffa7d20d448efb7e))
* AQUNAMA Phase 3 — SOW/quote approval workflow + case-study flags ([a136e2c](https://github.com/Amyzellercode/zellercrm/commit/a136e2c96312ef32fb2a29ffdb4dd5ae65d3831e))
* **authz:** add account read-scope helpers ([f37477d](https://github.com/Amyzellercode/zellercrm/commit/f37477df8ec08eef8770f6738f2db6a409320260))
* **authz:** add account write-scope assertion helper ([d9e2a2a](https://github.com/Amyzellercode/zellercrm/commit/d9e2a2a1b7a2bb7decdbfab76bda4c454a9931a4))
* **authz:** add account/lead/opportunity id-filter helpers (similarity post-filter) ([00cb5b6](https://github.com/Amyzellercode/zellercrm/commit/00cb5b600fe3da0318586986c6c3a00adf2347c2))
* **authz:** add activity-for-entity scope dispatch helper ([f667bfe](https://github.com/Amyzellercode/zellercrm/commit/f667bfe5e55500591012733001939bf4ab029f19))
* **authz:** add AuthenticationError and AuthorizationError ([297c84b](https://github.com/Amyzellercode/zellercrm/commit/297c84bed16b518ea80f890d4e104997579fa8f1))
* **authz:** add barrel export ([86c99bc](https://github.com/Amyzellercode/zellercrm/commit/86c99bc7f63132f93072453cfaff210c71bb49a3))
* **authz:** add board and task read/write scope helpers ([bea821b](https://github.com/Amyzellercode/zellercrm/commit/bea821b5ca94cccc2a1fffd809140277b0b836f8))
* **authz:** add bulk-id authorization filters for contacts and targets ([54ab855](https://github.com/Amyzellercode/zellercrm/commit/54ab8556d2a9fff4923b1d6f1441d926b6baacda))
* **authz:** add campaign and template read/write scope helpers ([a9816fb](https://github.com/Amyzellercode/zellercrm/commit/a9816fbccb48a3d1707f2a6d57be1259558ed5ee))
* **authz:** add canonical AppRole type and legacy role mapper ([510db15](https://github.com/Amyzellercode/zellercrm/commit/510db15067c48970fc061e55c4646f820a375586))
* **authz:** add document read/write scope helpers (linked-entity aware) ([359b51d](https://github.com/Amyzellercode/zellercrm/commit/359b51d3aa0e3654369d2a3817d427ebb3726422))
* **authz:** add enrichment cancel permission helpers ([e233e75](https://github.com/Amyzellercode/zellercrm/commit/e233e7501ef9066aff11f21efeb0a938d4be3678))
* **authz:** add lead/contact/opportunity/contract read-scope helpers (linked-account aware) ([d908032](https://github.com/Amyzellercode/zellercrm/commit/d908032362530f7e526b6eff70006c9781e64f3d))
* **authz:** add read/write assertion helpers for contacts and targets ([bd7e22f](https://github.com/Amyzellercode/zellercrm/commit/bd7e22fdb8cccf83e00cb06c854629ef1725bd6c))
* **authz:** add ReportScope builder for per-role report data filtering ([1d5448c](https://github.com/Amyzellercode/zellercrm/commit/1d5448c8c55919a9f1dc60c18100dae658bd7ac4))
* **authz:** add requireAuthenticated, requireRole, role predicates ([9347167](https://github.com/Amyzellercode/zellercrm/commit/93471673738ac470c11dbe44e995776e90756719))
* **authz:** add route response helpers (401/403/404) ([d413d97](https://github.com/Amyzellercode/zellercrm/commit/d413d97be9e5bc2fb6fe759296336430dffd593d))
* **authz:** add scoped contact and target update helpers ([5efc084](https://github.com/Amyzellercode/zellercrm/commit/5efc084000dc87cd4493cb7439ab0887652f9615))
* **authz:** add target and target-list read-scope helpers ([1cfe1cf](https://github.com/Amyzellercode/zellercrm/commit/1cfe1cf72ec05b7fc3251e3c74f8c8caf80ca3c5))
* **authz:** align UI/action callers to canonical role names ([8935ba4](https://github.com/Amyzellercode/zellercrm/commit/8935ba41e7333632c5b3e4249bb87988b404d656))
* **authz:** object-level authorization on account write actions ([031cf38](https://github.com/Amyzellercode/zellercrm/commit/031cf389a58f688c47e7cb48122f1ca8a333e844))
* **authz:** object-level authorization on contact write actions ([5701424](https://github.com/Amyzellercode/zellercrm/commit/5701424a63f456909e517d2a87d79cbf54f31bc4))
* **authz:** object-level authorization on contract write actions ([d9ca30b](https://github.com/Amyzellercode/zellercrm/commit/d9ca30bdf2ad8f97ac50f93ca2b766172eabc434))
* **authz:** object-level authorization on CRM task write actions ([83b4bd1](https://github.com/Amyzellercode/zellercrm/commit/83b4bd13b011df1d84da8c283a2c1e65a22f4bbf))
* **authz:** object-level authorization on lead write actions ([ae86243](https://github.com/Amyzellercode/zellercrm/commit/ae86243d162567f499de58ff011a569a056b9b61))
* **authz:** object-level authorization on opportunity write actions ([f81074b](https://github.com/Amyzellercode/zellercrm/commit/f81074bdfc124c6028d0d8ddc71ddf628a000a9c))
* **authz:** object-level authorization on target write actions ([6d3fb79](https://github.com/Amyzellercode/zellercrm/commit/6d3fb79ba57b919de56e3d6cd38c79d0a3fa0f96))
* **authz:** object-level authorization on target-list write actions ([7031de7](https://github.com/Amyzellercode/zellercrm/commit/7031de7dbd91cb48b282f977a8d5f4af74d23baf))
* **authz:** parent-scoped authorization on contract line-items ([98b81b9](https://github.com/Amyzellercode/zellercrm/commit/98b81b98ad424d5227db2f43024b2c5295985a6f))
* **authz:** parent-scoped authorization on opportunity line-items ([12f8895](https://github.com/Amyzellercode/zellercrm/commit/12f889513a97448994a53002f860ae74d025f399))
* **authz:** switch Users.role to Prisma enum AppRole ([078916b](https://github.com/Amyzellercode/zellercrm/commit/078916b75b8ab0d1952835df7d605068bc6ebd67))
* **authz:** validate setUserRole against canonical AppRole ([0c923b6](https://github.com/Amyzellercode/zellercrm/commit/0c923b6a3590eb7c7fbe2a8ddc77e4a7bd3ffcb8))
* **authz:** write-scope asserts for lead, opportunity, contract, target-list, crm-task, line-items ([cef3bc6](https://github.com/Amyzellercode/zellercrm/commit/cef3bc6fc9bf736321c6068a63394551b47e8bcb))
* **calendar:** CalendarConnection + crm_CalendarEvents models for Phase 4 sync ([c0c0a86](https://github.com/Amyzellercode/zellercrm/commit/c0c0a869d791229613bf969eaf24caf2010f6233))
* **calendar:** Calendly admin settings page + org webhook subscription ([36b51f9](https://github.com/Amyzellercode/zellercrm/commit/36b51f9bea00995b92484e73e67701c8d70dd69c))
* **calendar:** Calendly settings storage + signed webhook endpoint ([fa24df0](https://github.com/Amyzellercode/zellercrm/commit/fa24df050e87aab1f6abe42b22fdfe2904e6fd43))
* **calendar:** Calendly webhook HMAC signature verification ([584c2d2](https://github.com/Amyzellercode/zellercrm/commit/584c2d2ba7230c0e4e2d981f7354aaf3fdb50482))
* **calendar:** counterparty email matcher (contact &gt; target &gt; lead) ([2b32a0d](https://github.com/Amyzellercode/zellercrm/commit/2b32a0dfad172ba343e8fd9223c811e373978d8a))
* **calendar:** dedicated Calendar tab on profile + OAuth result banner ([aaafbba](https://github.com/Amyzellercode/zellercrm/commit/aaafbbaa2a23f5560ac507ab640a0388b5a75531))
* **calendar:** emit outbound sync events from activity writers ([151c960](https://github.com/Amyzellercode/zellercrm/commit/151c9602d3f2bcea60a25bd1f8a84a1c9e81a607))
* **calendar:** Google Calendar incremental polling sync via Inngest ([8121f21](https://github.com/Amyzellercode/zellercrm/commit/8121f216ee74f5e4b325fa554206c533462fd88b))
* **calendar:** Google Calendar OAuth connect flow (readonly scope) ([39d6fad](https://github.com/Amyzellercode/zellercrm/commit/39d6fad97a24166e13a605785e153bcbee9942cd))
* **calendar:** inngest outbound push to Google Calendar with invites ([57818d6](https://github.com/Amyzellercode/zellercrm/commit/57818d6511709c232183bef31d92c0fa990a3adf))
* **calendar:** inngest processor for crm/calendar.event.received ([f1abeb0](https://github.com/Amyzellercode/zellercrm/commit/f1abeb0d01193dc936d57651795807fc233875a5))
* **calendar:** outbound decision, event builder, counterparty resolver ([5206517](https://github.com/Amyzellercode/zellercrm/commit/520651797e7f374558b1b5f8fe5a58e3066ed28a))
* **calendar:** profile UI for Google Calendar connections ([befef45](https://github.com/Amyzellercode/zellercrm/commit/befef451cdd7515789a4bd8d4d74d7de56f5f8e2))
* **calendar:** register calendar settings in admin sidebar ([7b45570](https://github.com/Amyzellercode/zellercrm/commit/7b4557022f0f18b119aca4c0e6e29636e677933e))
* **calendar:** scopeLevel on CalendarConnection for write-scope upgrade ([3901dfa](https://github.com/Amyzellercode/zellercrm/commit/3901dfae31abc9b1eea32dfe2e501c4c762588a3))
* **calendar:** shared idempotent calendar-event processor ([d144a9f](https://github.com/Amyzellercode/zellercrm/commit/d144a9f5a5aa328452835e577398e8c092c3a272))
* **calendar:** two-way sync upgrade button + scope level in profile UI ([0e88de1](https://github.com/Amyzellercode/zellercrm/commit/0e88de18389d5a85082524c0c03a20a76e080869))
* **calendar:** write-scope OAuth upgrade with granted-scope detection ([23c7dbd](https://github.com/Amyzellercode/zellercrm/commit/23c7dbd5763db52e27204951942100e49e06f58b))
* **campaigns:** add rendered email preview to template editor ([0c12518](https://github.com/Amyzellercode/zellercrm/commit/0c1251815ec8ba0d16d76a7c842da4bae1d4759e))
* **campaigns:** enforce global do_not_email across send pipeline and import ([dce5149](https://github.com/Amyzellercode/zellercrm/commit/dce5149fc1bcc0f39f19ce0b31e7d06d0e6bf242))
* **campaigns:** react.email layout for campaign emails + editor preview ([b98291d](https://github.com/Amyzellercode/zellercrm/commit/b98291d64354e7640e36849985ff6c2cb02ec672))
* **campaigns:** unsubscribe sets global do_not_email suppression on targets ([c47d9c3](https://github.com/Amyzellercode/zellercrm/commit/c47d9c3c5e7358364ac291aacb55610bb2bf828b))
* **campaigns:** wrap campaign emails in react.email layout ([797c834](https://github.com/Amyzellercode/zellercrm/commit/797c8343599a44a9484ab5e7464effb303d51156))
* **crm:** 45-day kill rule cron with inbound-email/activity clock ([cb514b0](https://github.com/Amyzellercode/zellercrm/commit/cb514b0eddc23f689267da1d8fa2b5ec54fde141))
* **crm:** add assign/disconnect document server actions for CRM tasks ([236e7ac](https://github.com/Amyzellercode/zellercrm/commit/236e7ac8a9def4224c21461386adf7b199e0e0c9))
* **crm:** add delivery_deadline field to opportunities (PO-stage requirement) ([3378909](https://github.com/Amyzellercode/zellercrm/commit/337890951921a0d3ecae3e6facc6990b754f2660))
* **crm:** add global do_not_email flag on targets and delivery_deadline on opportunities ([a534dc1](https://github.com/Amyzellercode/zellercrm/commit/a534dc136f65e056eda51e763b11ed2c3631c5c5))
* **crm:** approval-status fields on opportunities, case-study flags on accounts ([5cd5c27](https://github.com/Amyzellercode/zellercrm/commit/5cd5c27e8d492e4b45bd01b8401c020a37c61809))
* **crm:** approvals queue page and deal-page approval UI ([dc12725](https://github.com/Amyzellercode/zellercrm/commit/dc12725bde4348c02922d6e6903ff480df9171d2))
* **crm:** AQUNAMA Phase 4 — calendar sync (Calendly + Google Calendar inbound) ([be95ad7](https://github.com/Amyzellercode/zellercrm/commit/be95ad71f8739337b4ab3387bad2f867a1838247))
* **crm:** auto-task helper and 5-touch qualified follow-up cadence ([476f952](https://github.com/Amyzellercode/zellercrm/commit/476f9524a6bad6a1494decc8b23bc9bc3e4a41f4))
* **crm:** care touchpoint engine (check-in, referral, quarterly) ([2daac7b](https://github.com/Amyzellercode/zellercrm/commit/2daac7b50dd5f6af4961ca3679ba59d578a73bdd))
* **crm:** case-study candidate/approval flags on accounts ([0311bd8](https://github.com/Amyzellercode/zellercrm/commit/0311bd8130d28245f66bd67a7634e8f17dcf78d1))
* **crm:** configurable timer logic — business days, cadence/care schedules, kill predicate, settings loader ([da378f2](https://github.com/Amyzellercode/zellercrm/commit/da378f24648686fa9889316593e40c836622d718))
* **crm:** convert target to deal with campaign attribution and entry stage ([aab8920](https://github.com/Amyzellercode/zellercrm/commit/aab8920b7d41cc8d92e6c58e25a27c24259ce5c2))
* **crm:** emit crm/opportunity.stage-changed from all stage-writing actions ([b734e0e](https://github.com/Amyzellercode/zellercrm/commit/b734e0e11aebdf550ad8d5ebe49b2a72856f052c))
* **crm:** hard-block unapproved deals from entering the qualified stage ([008ed9d](https://github.com/Amyzellercode/zellercrm/commit/008ed9d419835b9ed8a494f3198e1eaf7dead9c0))
* **crm:** quote approval request/decide actions with notifications ([80dd5a1](https://github.com/Amyzellercode/zellercrm/commit/80dd5a1c5eec8ab3b52330ca6f9220e16d279228))
* **crm:** show invoices on account detail page ([39456a1](https://github.com/Amyzellercode/zellercrm/commit/39456a15fbb5f07e8569d424ce505ae4ad7e4386))
* **crm:** show invoices on account detail page ([78d3928](https://github.com/Amyzellercode/zellercrm/commit/78d3928e55c2dfc5548153748bc7889a050797ba))
* **crm:** stage_kind on sales stages, task-opportunity link, stage_entered_at ([9f0e8fc](https://github.com/Amyzellercode/zellercrm/commit/9f0e8fcc1d30971fb8a2262b372934007e73adb9))
* **crm:** support XLSX target imports via shared spreadsheet parser ([67e91b9](https://github.com/Amyzellercode/zellercrm/commit/67e91b9fc0ed3274df4d1262da3f94657c0a9dcd))
* **crm:** target recycle cron with Recycled list and admin digest ([42904b0](https://github.com/Amyzellercode/zellercrm/commit/42904b0bede16ad1ebad228b7172575b2afb8e3c))
* **crm:** weekly renewal reminder sweep for contracts and account products ([4b31528](https://github.com/Amyzellercode/zellercrm/commit/4b315283a895881001ad046b8a856140d3fc73cb))
* CSV/Excel export for campaign targets and target lists ([21d16fc](https://github.com/Amyzellercode/zellercrm/commit/21d16fc347c623f397a936d3191c70fa6e8118e5))
* **dashboard:** add Invoices, Campaigns, Targets cards; remove Employee card ([f190074](https://github.com/Amyzellercode/zellercrm/commit/f190074e3e6a894a8757c40104be99a433ffbe30))
* **db:** backfill canonical roles (admin/manager/user) and sync is_admin ([d21a7bd](https://github.com/Amyzellercode/zellercrm/commit/d21a7bd2c45aab3d0ab22d0f4cbde83bf63ca561))
* **dev:** Inngest dev server via docker-compose.dev.yml for host development ([a4bdda1](https://github.com/Amyzellercode/zellercrm/commit/a4bdda1baa04cf02b305b8f45515d131c5e6745b))
* **dev:** local pgvector Postgres service for host development ([0553bcd](https://github.com/Amyzellercode/zellercrm/commit/0553bcdf8d3f09e55aa8832d612c1c43619804bd))
* **dev:** point DATABASE_URL at local Postgres, add db:migrate ([9def669](https://github.com/Amyzellercode/zellercrm/commit/9def669c917ca10fbb4e984e64762127fa42a65d))
* **dev:** seed local database, add db:seed and db:reset ([b010838](https://github.com/Amyzellercode/zellercrm/commit/b010838037ba1c6ba491f6def7929ed2481fd3e8))
* Docker self-hosting setup with full automation ([cbe567a](https://github.com/Amyzellercode/zellercrm/commit/cbe567a76eeb7d5c4458a681668bfbccd1d4336c))
* enable Next.js standalone output for Docker ([755f8ee](https://github.com/Amyzellercode/zellercrm/commit/755f8eeba651decaa01657244f5cb6cbe96166fd))
* **invoices:** add FKs, indexes, line-item trigger, money CHECK ([399fe25](https://github.com/Amyzellercode/zellercrm/commit/399fe25a3c9c0874a6f3e415b8f234017747e623))
* **invoices:** add numbering format template + counter consumer ([e3586ce](https://github.com/Amyzellercode/zellercrm/commit/e3586ce3d921cb5240a155b5d9d16fb180b1dc13))
* **invoices:** add PDF i18n string bundles (EN/CZ) ([d300354](https://github.com/Amyzellercode/zellercrm/commit/d300354ccab6199d7b2761dcf0e0116ed02271e2))
* **invoices:** add permission guards ([d77394b](https://github.com/Amyzellercode/zellercrm/commit/d77394b81a17686b77b777baecebf188e1b1c3c3))
* **invoices:** add Prisma schema, migration, tsvector trigger ([0adc8ca](https://github.com/Amyzellercode/zellercrm/commit/0adc8ca7adb24c5c073fc8cc5709e9ac113a0501))
* **invoices:** add search filter builder ([677947d](https://github.com/Amyzellercode/zellercrm/commit/677947d063a1526cd41c6bd5b965e5d36dec556e))
* **invoices:** add totals computation with mixed VAT support ([8261ab6](https://github.com/Amyzellercode/zellercrm/commit/8261ab6348d65a8303a008d8192eea2552db9767))
* **invoices:** admin pages — tax rates, series, currencies, settings ([b6a7a3e](https://github.com/Amyzellercode/zellercrm/commit/b6a7a3ef34d536b1eb7e9c3bb9d958ab968ddadf))
* **invoices:** API routes for invoices CRUD, lifecycle, payments, search, admin config ([6bf8a8f](https://github.com/Amyzellercode/zellercrm/commit/6bf8a8fdd94dad038b61feeac5bf771ff8624478))
* **invoices:** fetch FX rates via frankfurter.app ([64ee37c](https://github.com/Amyzellercode/zellercrm/commit/64ee37c69deddb060fe67374a6f750e25b590277))
* **invoices:** full invoicing module ([10c388d](https://github.com/Amyzellercode/zellercrm/commit/10c388dc36f889772625c2c1d3f06e3f945eee9e))
* **invoices:** invoice email template ([2ca2c2d](https://github.com/Amyzellercode/zellercrm/commit/2ca2c2d117a58fd1dbe432ec5384d182a6ef801c))
* **invoices:** invoice UI — list, new, detail, edit pages ([41eac81](https://github.com/Amyzellercode/zellercrm/commit/41eac81072de702ab35d3702f6a1c3970224b88b))
* **invoices:** MinIO storage wrapper for invoice PDFs ([94ebfc3](https://github.com/Amyzellercode/zellercrm/commit/94ebfc39b769a606a49fd0ecdfa35145f9150be3))
* **invoices:** PDF render entry ([9abd77b](https://github.com/Amyzellercode/zellercrm/commit/9abd77be7c47aa87ad5e9c19622ec712a2739e91))
* **invoices:** PDF template (@react-pdf/renderer) ([8d146e8](https://github.com/Amyzellercode/zellercrm/commit/8d146e843827023f106be061e9300ff1a849f877))
* **invoices:** seed currencies, default series, tax rates, settings ([d21264e](https://github.com/Amyzellercode/zellercrm/commit/d21264eec310a674084ec29377aee67ce26d4b8e))
* **invoices:** server actions for invoice lifecycle ([bc2f1ef](https://github.com/Amyzellercode/zellercrm/commit/bc2f1efe3692e64d2b46b30cdb038120a22b5fe8))
* **invoices:** sidebar nav entry + i18n (EN/CZ) ([2451a49](https://github.com/Amyzellercode/zellercrm/commit/2451a4975a2d311a9dcf0a055ab0098e9e9f2756))
* **invoices:** Zod schemas + shared types ([5793ca6](https://github.com/Amyzellercode/zellercrm/commit/5793ca6e5d7f0030382d7c0457cc3ae7aab73e03))
* **mcp:** add crm_list_users and opportunity reassignment ([6ba1d4a](https://github.com/Amyzellercode/zellercrm/commit/6ba1d4a2f344e3027878e402bcf30a5736c82c13))
* **mcp:** assertScopeOrNotFound adapter for object-level tool authorization ([b2d2eea](https://github.com/Amyzellercode/zellercrm/commit/b2d2eea2a9077ac5968d77a375192aab9d12c790))
* **mcp:** object-level authorization on project board tools ([4f8f1ea](https://github.com/Amyzellercode/zellercrm/commit/4f8f1eaca5c7992eeaa4dbb710ed255824c7a936))
* **mcp:** object-level authorization on project comment + document-link tools ([41d2791](https://github.com/Amyzellercode/zellercrm/commit/41d279163a73e9b31a73ad80784e55c9db9ba9d8))
* **mcp:** object-level authorization on project section tools ([557a0f2](https://github.com/Amyzellercode/zellercrm/commit/557a0f2daefa22e942908bc27484b3208ef072a9))
* **mcp:** object-level authorization on project task tools; drop userBoardWhere ([9c28219](https://github.com/Amyzellercode/zellercrm/commit/9c28219cc30c7b3053469d7582e06a4615118765))
* **mcp:** read-scoped authorization on project watch_board (escalation fix) ([3a07897](https://github.com/Amyzellercode/zellercrm/commit/3a07897b126d7180e7010baef08712c2a652ab7d))
* **mcp:** reassignment on accounts, contacts and leads; scope CRM lead tools ([0585c1d](https://github.com/Amyzellercode/zellercrm/commit/0585c1d8eafc8f693a51299ba2656cd0dbf7a78f))
* **mcp:** reassignment on accounts, contacts and leads; scope CRM lead tools ([c775674](https://github.com/Amyzellercode/zellercrm/commit/c775674fdbf000d1fa89c88b7dd0f5cb14ae601c))
* **net:** assertPublicHost — resolve-validate-pin guard against SSRF/DNS-rebinding ([de55dcb](https://github.com/Amyzellercode/zellercrm/commit/de55dcbc6e7de160d76218b604450bfb4d804f71))
* **net:** ip-rules — refuse non-public-unicast addresses (SSRF) ([c1e0915](https://github.com/Amyzellercode/zellercrm/commit/c1e0915f8d17d86171b7fbdea3ab2d2ee2a6f779))
* **reports:** per-category functions accept ReportScope to filter data by role ([a8deacf](https://github.com/Amyzellercode/zellercrm/commit/a8deacfe73d76c1a5ef34bfe2663eef3925510d5))
* **security:** permission-driven authorization migration (Phases A → F.1) ([b5bc66b](https://github.com/Amyzellercode/zellercrm/commit/b5bc66bc6f62f3830d9876c5245028b85c2c091e))
* **security:** SSRF host-guard on IMAP test/discover/create sinks ([e28894a](https://github.com/Amyzellercode/zellercrm/commit/e28894a544b0a0fab42897aadaa1bd81bb710ff8))
* **security:** SSRF host-guard on SMTP send and background IMAP connect ([c7ad9ca](https://github.com/Amyzellercode/zellercrm/commit/c7ad9ca36d08102d76927d7114d06657a824e71e))


### Fixed

* **account-products:** require account read scope on get-account-products ([1358325](https://github.com/Amyzellercode/zellercrm/commit/135832593c74bd4745bb5adb33a920110ec69cb1))
* **account-products:** require account write scope on assignment mutations ([4235ecc](https://github.com/Amyzellercode/zellercrm/commit/4235eccece8adef7745936ece825892bb7a88816))
* add calendar connection feedback ([4f09a08](https://github.com/Amyzellercode/zellercrm/commit/4f09a08b0bf4c783ab1c497368d821eeb150e465))
* add calendar connection feedback ([b9b21f9](https://github.com/Amyzellercode/zellercrm/commit/b9b21f94a537f425aa63a5a2f3faa5b8884c45e4))
* **admin:** require admin role on activate/deactivate user (close audit gap) ([e60330e](https://github.com/Amyzellercode/zellercrm/commit/e60330e6f29e75fdb1b618c7205473f3b5373a48))
* **admin:** require admin role on CRM-settings server actions ([95b5a77](https://github.com/Amyzellercode/zellercrm/commit/95b5a775b568b9251809390b2797088cc23bed63))
* **admin:** require admin role on currency server actions ([2689aad](https://github.com/Amyzellercode/zellercrm/commit/2689aadb26e6dd93a829ce310c6b1cf9dd93208b))
* **api:** filter contact bulk enrichment ids by user scope ([d2458b0](https://github.com/Amyzellercode/zellercrm/commit/d2458b0dbaa95cf888375476837160f802dd08a4))
* **api:** filter target bulk enrichment ids by user scope ([5285e28](https://github.com/Amyzellercode/zellercrm/commit/5285e281a9d02f4640054d6c97cd9b12a94067e7))
* **api:** require contact write scope on enrich POST/DELETE ([2db1220](https://github.com/Amyzellercode/zellercrm/commit/2db12204b7fc4e2060162d120e3bf0afa50ff67a))
* **api:** require invoice read scope on PDF route ([4d3472c](https://github.com/Amyzellercode/zellercrm/commit/4d3472c144d965c9407e3fbae448903ed23af916))
* **api:** require parent target write scope on target-contact create ([0250e39](https://github.com/Amyzellercode/zellercrm/commit/0250e390f7cf7c8135b358719942a00aa7c76e78))
* **api:** require target write scope and contact linkage on per-target-contact enrich ([705b084](https://github.com/Amyzellercode/zellercrm/commit/705b084c896ed9e9f97fa7aaec2ee4bd4583d1df))
* **api:** require target write scope on enrich POST/DELETE (auto-fixes campaign re-export) ([6c467a2](https://github.com/Amyzellercode/zellercrm/commit/6c467a28b9f8dc6f89a179f5f32eff9816aeb032))
* **api:** require target write scope on per-target enrich (auto-fixes campaign re-export) ([9f448c9](https://github.com/Amyzellercode/zellercrm/commit/9f448c983ef6d19f50467f2bea71431527f3175e))
* **api:** scope reports/export by role; gate users-directory report ([82d8de8](https://github.com/Amyzellercode/zellercrm/commit/82d8de897997ce5aaee2e75677ffb7663ddff984))
* **api:** scoped contact PATCH closes BOLA/IDOR (GHSA-mg5f-m89f-4gmc) ([dba262f](https://github.com/Amyzellercode/zellercrm/commit/dba262f560715ca04d4343389a6a8759b6ec259f))
* **api:** scoped target PATCH closes BOLA/IDOR (auto-fixes campaign re-export) ([62c3496](https://github.com/Amyzellercode/zellercrm/commit/62c3496662b743ba59f9556554fa32d06836dc99))
* **auth:** align auth-client roles with renamed manager/user ([b04821d](https://github.com/Amyzellercode/zellercrm/commit/b04821dacdf45f5dee3eab939c94d04185aa7905))
* **authz:** drop readonly tuple from accountUserScopeOR for Prisma compat ([912f01b](https://github.com/Amyzellercode/zellercrm/commit/912f01b7637943cb0cc4ad4bbd62f156c517a815))
* **authz:** guard directly-callable convertTarget action ([02dfac1](https://github.com/Amyzellercode/zellercrm/commit/02dfac118a1f2f8c5775d340356d78d125606fef))
* **authz:** include deletedAt:null in target read scope (crm_Targets has soft-delete) ([022b574](https://github.com/Amyzellercode/zellercrm/commit/022b574778e959000bab09e3c689fe4b882f70bc))
* **authz:** replace is_admin checks with requireRole on admin invoice routes ([0ccb9fc](https://github.com/Amyzellercode/zellercrm/commit/0ccb9fc3d92a2868345962fb38b3589668ba7497))
* **authz:** use lowercase prismadb.documents accessor ([aed66e5](https://github.com/Amyzellercode/zellercrm/commit/aed66e5231e244a5ddd68fc0fd8cb23499b10d86))
* **authz:** use shared opportunity write-scope in setInactiveOpportunity ([9cfcac4](https://github.com/Amyzellercode/zellercrm/commit/9cfcac4f64854913de35982217696839d7e28383))
* **calendar:** classify Google auth-revocation vs rate-limit/token errors ([2436427](https://github.com/Amyzellercode/zellercrm/commit/24364270abb9fc5dfd85149608dbde8cd75e3f06))
* **calendar:** close unrelated-connection guard gap for disconnected accounts ([4149ed0](https://github.com/Amyzellercode/zellercrm/commit/4149ed06e875c63bf7b408db41cc1f8f88a0ead6))
* **calendar:** exception-safe Calendly subscription + shared authz in admin settings ([d516239](https://github.com/Amyzellercode/zellercrm/commit/d51623943c463996a12d7e8a869cb7715b3ab322))
* **calendar:** filter soft-deleted contacts/leads in matcher ([1308464](https://github.com/Amyzellercode/zellercrm/commit/1308464ccb6be6ef6172212e22cb547b424941e5))
* **calendar:** harden outbound push against guest-list wipes, false revocations, and unauthorized writes ([e5787d8](https://github.com/Amyzellercode/zellercrm/commit/e5787d868c679929e828d291841c8c72e6255e05))
* **calendar:** harden outbound sync against duplicate inserts and reschedule 404s ([6707bb4](https://github.com/Amyzellercode/zellercrm/commit/6707bb43a4cc835cbbc2ff93c24b185f5857a5b9))
* **calendar:** harden outbound sync emit against slow sends and fix write/emit ordering ([c877135](https://github.com/Amyzellercode/zellercrm/commit/c877135dbf04e4f7b1d5cf8537b61c68daebf401))
* **calendar:** keep stored scopeLevel truthful, kill race duplicates, patch back-dated meetings ([23d9d47](https://github.com/Amyzellercode/zellercrm/commit/23d9d4788c10bd774a03eb81edbfe49ad53b157e))
* **calendar:** log dropped Calendly webhook events missing uri/start_time ([7abb6d3](https://github.com/Amyzellercode/zellercrm/commit/7abb6d3d1e01efaf8872ceaa07907e5a5beadebe))
* **calendar:** OAuth state (CSRF) validation + narrowed error logging ([4687a18](https://github.com/Amyzellercode/zellercrm/commit/4687a1873d066fbc7ed0aad47b54fc46b19d6a4c))
* **calendar:** record lastSyncError for upsert-loop failures in google sync ([e09be98](https://github.com/Amyzellercode/zellercrm/commit/e09be9813950fe3149e83e8ac544fda40d450258))
* **calendar:** scope outbound mapping lookups/updates per-row, not per-activity ([46c7a28](https://github.com/Amyzellercode/zellercrm/commit/46c7a2890ed51e760049128d18d5b400825e7fd4))
* **calendar:** stop notes edits on past meetings from emailing customers ([0cf7d01](https://github.com/Amyzellercode/zellercrm/commit/0cf7d018c6731f0e9ead20d8ae84388367c6d1b8))
* **calendar:** transactional upsert + P2002 race handling in calendar processor ([af717f2](https://github.com/Amyzellercode/zellercrm/commit/af717f2126ce00f1294ceb6d8eb980e1d127f59f))
* **campaign-templates:** scope template reads/mutations by role and ownership ([bafde30](https://github.com/Amyzellercode/zellercrm/commit/bafde3078e696d95363af84935c4e18caba8b58f))
* **campaigns:** case-insensitive suppression matching and send-step last-gate guard ([bc03bc1](https://github.com/Amyzellercode/zellercrm/commit/bc03bc116a22eeba2b25884a430022890a4c9f51))
* **campaigns:** keep unsubscribe confirmation on suppression write failure ([6f24cfc](https://github.com/Amyzellercode/zellercrm/commit/6f24cfc8d343f4e640e02a9c69eb6062d5736a20))
* **campaigns:** narrow createCampaign result before using campaign.id ([0c4647a](https://github.com/Amyzellercode/zellercrm/commit/0c4647a3ce87c309231f0fce53d567eca6967f20))
* **campaigns:** require auth + ownership on create/update/delete/pause ([595060c](https://github.com/Amyzellercode/zellercrm/commit/595060cb8fda5ba6d5f2507b1ba67c460ec0f6d8))
* **campaigns:** require manager/admin role on schedule and send-now ([787b446](https://github.com/Amyzellercode/zellercrm/commit/787b446e5f109a216ffbc201ef27be5aac752287))
* **campaigns:** sanitize template HTML and escape merge-tag values ([c2bdcbb](https://github.com/Amyzellercode/zellercrm/commit/c2bdcbb07fc961d1fc2890d35d4b736f7bdf13c1))
* **campaigns:** scope campaign reads by role ([7dd70b9](https://github.com/Amyzellercode/zellercrm/commit/7dd70b931f70c11a2c59ff79a16eae8a57d5c2c2))
* **ci:** make migration chain replayable on a fresh database ([718ed51](https://github.com/Amyzellercode/zellercrm/commit/718ed51dcb8e011a2fc0ffeb7e7aaf42fc620cc1))
* **crm-settings:** allow creating industry, opportunity type, and sales stage values ([6c96569](https://github.com/Amyzellercode/zellercrm/commit/6c96569ec9dd54118300e94e2f7349d810612a8e))
* **crm:** align lead/contract table display schemas with DB nullability ([7e7e81b](https://github.com/Amyzellercode/zellercrm/commit/7e7e81b1fe25e7a1c8b18a3ce1fd356302039cd4))
* **crm:** align table display schemas with DB nullability (close_date, leads, contracts) ([4c9e7c7](https://github.com/Amyzellercode/zellercrm/commit/4c9e7c7c748d5b0a3b7c9ac9e4e32338029f9df0))
* **crm:** allow null close_date in opportunities table schema ([5139f08](https://github.com/Amyzellercode/zellercrm/commit/5139f08a554ac7b598cb16c3c018f3e9e1318037))
* **crm:** blank-UUID + create-in-context UX; ci(e2e): pin inngest-cli ([c7fdab4](https://github.com/Amyzellercode/zellercrm/commit/c7fdab4e46483b3ec9d1416e3ea8db7a05a3c97d))
* **crm:** drop empty currency on opportunity update; e2e round 2 ([1234c83](https://github.com/Amyzellercode/zellercrm/commit/1234c8321ea9a2f25bf4569fe91dcf6aacf2487c))
* **crm:** exclude cancelled activities from the Phase 2 kill-clock query ([62f5fdb](https://github.com/Amyzellercode/zellercrm/commit/62f5fdbd7d1db6590742763f57bde03f100bb9bc))
* **crm:** expand getCrMTask document select and clean up junction on delete ([785a3c5](https://github.com/Amyzellercode/zellercrm/commit/785a3c5c6fd926eb20fbbec874683233e71348f3))
* **crm:** final-review fixes — protect re-engaged targets and completed renewals ([b1ca483](https://github.com/Amyzellercode/zellercrm/commit/b1ca48316360b1e30e74a239c6dd36021723cad0))
* **crm:** make target-to-deal conversion idempotent and honor error contract ([6c3b617](https://github.com/Amyzellercode/zellercrm/commit/6c3b617bda46ae25c373beb1ae4fe43f2a789b7e))
* **crm:** normalize blank UUID fields in createAccount ([8d30d33](https://github.com/Amyzellercode/zellercrm/commit/8d30d332473c102db23e3056dceeef91592d820a))
* **crm:** normalize blank UUID inputs and auto-fill account/assignee on create ([9a6232f](https://github.com/Amyzellercode/zellercrm/commit/9a6232f956054f3552d4ca5336397eb2f0eef258))
* **crm:** remove task-specific filters from document table toolbar ([85c3df2](https://github.com/Amyzellercode/zellercrm/commit/85c3df252a55993377cdba7418c1ed5656ea85b6))
* **crm:** require account read scope on getAccountById ([98bc13a](https://github.com/Amyzellercode/zellercrm/commit/98bc13a3a08ba1c8b2206ee5ef22e2517ce881b6))
* **crm:** require entity-scoped read access on activity feed ([7e272a0](https://github.com/Amyzellercode/zellercrm/commit/7e272a0a3ad22d3619c1f8db41369735765edbfe))
* **crm:** scope account list by user/manager/admin role ([f339200](https://github.com/Amyzellercode/zellercrm/commit/f339200d260d461cb957bab96f8321b5d94188c4))
* **crm:** scope account search by user/manager/admin role ([fe6402a](https://github.com/Amyzellercode/zellercrm/commit/fe6402a82658412f98ef27dcc82c78b0dafcea87))
* **crm:** scope audit-log-by-entity and normalize audit-log-admin to canonical helper ([4cfc237](https://github.com/Amyzellercode/zellercrm/commit/4cfc237742b5b6731a4a8c26c24f57d76d9aa000))
* **crm:** scope contact reads by role and linked-account/opportunity access ([4e53b18](https://github.com/Amyzellercode/zellercrm/commit/4e53b1882e23e28d4f8efbdf64036482985e54e2))
* **crm:** scope contract reads by role and linked-account access ([29a7492](https://github.com/Amyzellercode/zellercrm/commit/29a74920a928873299943ac04d00ff53b36cca46))
* **crm:** scope lead reads by role and linked-account access ([24f58fc](https://github.com/Amyzellercode/zellercrm/commit/24f58fcb0cc6c3adf7b0860a1d8b725d7502d6cb))
* **crm:** scope opportunity reads by role; cache key respects user scope ([7062851](https://github.com/Amyzellercode/zellercrm/commit/706285194be29da67b9c1a4bda043f72ee83525a))
* **crm:** scope pgvector similarity results by user/manager/admin ([1b54d19](https://github.com/Amyzellercode/zellercrm/commit/1b54d197e5a683e9d6140911d46bc629b795dab8))
* **crm:** scope remaining opportunity read actions (by-account, by-contact, user-opps) ([aaa58de](https://github.com/Amyzellercode/zellercrm/commit/aaa58de6da53176bcfb3a059e989dfbcd5ea2612))
* **crm:** scope target and target-list reads by role ([7702b4f](https://github.com/Amyzellercode/zellercrm/commit/7702b4f7321ece2e2d30205a12c8642a28e67141))
* **crm:** serialize Prisma Decimals in opportunities/contracts fetches (RSC boundary error) ([e8e636f](https://github.com/Amyzellercode/zellercrm/commit/e8e636f7632520a740c32cc83b7443bb619f89ea))
* **crm:** serialize Prisma Decimals in opportunities/contracts list fetches ([639b188](https://github.com/Amyzellercode/zellercrm/commit/639b1880c2acbbb38108c8644c4880156b9bd1b3))
* **crm:** switch CRM task document actions from broken axios calls to server actions ([5707bb7](https://github.com/Amyzellercode/zellercrm/commit/5707bb7436ec25a5f59e9f89438d0868d8fbf403))
* **crm:** uncomment assigned_to_user in task document schema and remove ts-ignore ([ca1a740](https://github.com/Amyzellercode/zellercrm/commit/ca1a7401e0d0b8b90c3ac127a045bc1e49360ed7))
* **crm:** wire CRM task documents to correct junction table + cleanup ([431a722](https://github.com/Amyzellercode/zellercrm/commit/431a722e73a63495bea91020c24726442881d359))
* **crm:** wire task comments to correct FK column (assigned_crm_account_task) ([4b5c0ea](https://github.com/Amyzellercode/zellercrm/commit/4b5c0ea5f84f1bbf139aaff93250af2c374c2a18))
* **db-guard:** block empty/unresolvable host instead of passing it ([8d1f254](https://github.com/Amyzellercode/zellercrm/commit/8d1f254487aa66b48a1c488271d7851550626623))
* **db-guard:** close query-string [@localhost](https://github.com/localhost) bypass, fix bracketed IPv6 ([90df5b0](https://github.com/Amyzellercode/zellercrm/commit/90df5b06e9d408e9c8abd48804fb983694594f19))
* **deploy:** pin pnpm 11 via packageManager so nixpacks doesn't build with pnpm 9 ([6f3bfa5](https://github.com/Amyzellercode/zellercrm/commit/6f3bfa5c8599d825a54053ef782d71af69f53f8d))
* **deploy:** use current corepack in nixpacks and migrate to pnpm 11 allowBuilds ([f7dd355](https://github.com/Amyzellercode/zellercrm/commit/f7dd3559af4342dfb3df5bbe00a60a436931cb73))
* **deps:** patch 2 Dependabot vulnerabilities ([f26bb9c](https://github.com/Amyzellercode/zellercrm/commit/f26bb9c4902c8c9f0a963126b9425518be8ef19b))
* **deps:** patch Dependabot advisories via pnpm overrides ([5b4646a](https://github.com/Amyzellercode/zellercrm/commit/5b4646af983b9c3f3f0dd0c9f4b704dff48fd5d1))
* **deps:** patch Dependabot security advisories ([448dfa4](https://github.com/Amyzellercode/zellercrm/commit/448dfa46aa140cb235b93943afa51018cb47e14b))
* **deps:** patch Dependabot security advisories via pnpm overrides ([76db140](https://github.com/Amyzellercode/zellercrm/commit/76db14069eb260e2fec08d3d8f99681e9805a274))
* **deps:** pin kysely 0.28 — restore main deployability (better-auth 1.6.13 adapter breakage) ([9d719f2](https://github.com/Amyzellercode/zellercrm/commit/9d719f246b5c7864cea3212b6f208305bb6cc3be))
* **deps:** pin kysely to 0.28 line — better-auth 1.6.13 adapter incompatible with kysely 0.29 ([7f62f01](https://github.com/Amyzellercode/zellercrm/commit/7f62f017cc70495266bcbb418814de6df3588ff5))
* **deps:** resolve all 65 Dependabot security alerts ([790dc5b](https://github.com/Amyzellercode/zellercrm/commit/790dc5bf14f319bf02f794a9674a1cf643330346))
* **deps:** resolve all 65 Dependabot security alerts (one PR) ([81ff788](https://github.com/Amyzellercode/zellercrm/commit/81ff7882d401de70f5d08b0c25d2e578e30f1d7a))
* **deps:** resolve all 65 Dependabot security alerts via pnpm overrides ([1bd9224](https://github.com/Amyzellercode/zellercrm/commit/1bd9224bc9430cb77eb75b9cb7c4d25660434f22))
* **dev:** bind local Postgres to loopback and bound db:wait retries ([f9b3996](https://github.com/Amyzellercode/zellercrm/commit/f9b3996aa99b64d66930ddef1ad83ae3d569f66c))
* **dev:** guard db scripts against remote DB and correct local Postgres docs ([d929c39](https://github.com/Amyzellercode/zellercrm/commit/d929c397de7fd4b2693b61dd6260ecff2a343cd0))
* Docker e2e verification fixes ([ffe7d5c](https://github.com/Amyzellercode/zellercrm/commit/ffe7d5c1e6f633f0b544335f0bfe82fe1a0eb461))
* **docker:** make admin email configurable via ADMIN_EMAIL ([d5b506d](https://github.com/Amyzellercode/zellercrm/commit/d5b506d1f739bcf4bd1bf1cb83ef7ae8144c5811))
* **docker:** replace hardcoded credentials with env-driven placeholders ([c3be610](https://github.com/Amyzellercode/zellercrm/commit/c3be6107c55fe8facaeb5025fb31b5f0e7159e08))
* **documents:** filter bulk document operations by user scope (fail-closed) ([0577b28](https://github.com/Amyzellercode/zellercrm/commit/0577b2826599bb44541accd19e56d9e86b6c1fd6))
* **documents:** require ownership/account scope on document mutations ([240a59d](https://github.com/Amyzellercode/zellercrm/commit/240a59d3c05cf342d1b1a12e10410c1f4e49bd2f))
* **documents:** scope document reads by role and linked-entity access ([acf51ae](https://github.com/Amyzellercode/zellercrm/commit/acf51aed7ace9151c3224759fc3c61ec19bb680d))
* **invoices:** add PROFORMA to Zod invoice type enum ([d80413a](https://github.com/Amyzellercode/zellercrm/commit/d80413a697680e8ddb0555c75e9c7db0fc84874b))
* **invoices:** add supplier company details, PDF regeneration, admin route guard ([253d9a3](https://github.com/Amyzellercode/zellercrm/commit/253d9a37f1527ea96c502842b99d56747b200b3c))
* **invoices:** consolidate Invoice_Currencies into shared Currency table ([e75f15a](https://github.com/Amyzellercode/zellercrm/commit/e75f15aaafc9f093fc7a82f7fdd77a9cf9b8a8f4))
* **invoices:** consolidate Invoice_Currencies into shared Currency table ([6273dbe](https://github.com/Amyzellercode/zellercrm/commit/6273dbeb1f1182e1e4c6c7278317c9c7657b7cc9))
* **invoices:** fix Set type annotation in permissions for strict tsc ([2bd71ef](https://github.com/Amyzellercode/zellercrm/commit/2bd71ef44b787ca9244b055feccb7626b17a2a24))
* **invoices:** hydration mismatches, decimal serialization, server action refactor ([ac1154b](https://github.com/Amyzellercode/zellercrm/commit/ac1154bfb9593510ba13535253e16ff3f81e51c6))
* **invoices:** redirect to /invoices after creating new invoice ([5c79689](https://github.com/Amyzellercode/zellercrm/commit/5c7968936cfbcf7f9155af4375399a05c47e2825))
* **invoices:** redirect to invoice detail page after create/edit ([a6e5929](https://github.com/Amyzellercode/zellercrm/commit/a6e5929ec91f74f49201eee8a546679b94d93da8))
* **invoices:** remove unused imports and prefix unused params ([9099e8a](https://github.com/Amyzellercode/zellercrm/commit/9099e8af979b4eb56013a660efe8b2f89123873e))
* **invoices:** remove unused React import from PDF template ([2e5cae1](https://github.com/Amyzellercode/zellercrm/commit/2e5cae19d250dc97936a04e1f0b357dc46f05f1d))
* **invoices:** replace Account select with searchable combobox ([0673c59](https://github.com/Amyzellercode/zellercrm/commit/0673c59e829bdb26cb82062e5bc9ad51ae6df46e))
* **invoices:** require account read scope on get-invoices-by-accountId ([c31f247](https://github.com/Amyzellercode/zellercrm/commit/c31f247f697e9c08f9398712f54a2a043ca40c6c))
* **invoices:** require account write scope on create and on accountId reassignment ([2cd584e](https://github.com/Amyzellercode/zellercrm/commit/2cd584e701d930fbe9f1f28b367acbca66051e67))
* **invoices:** require read scope on source and write scope on accountId for duplicateInvoice ([c72d6ee](https://github.com/Amyzellercode/zellercrm/commit/c72d6eeefcc6b68b317779fb4d9679aab9b1cef0))
* **invoices:** review fixes — balanceDue, FX outside tx, permissions, search column, email template ([2471b35](https://github.com/Amyzellercode/zellercrm/commit/2471b35a97c1bcd8bb76a93c47c83ee7042b75cb))
* **invoices:** supplier company details, PDF regeneration, admin route guard ([993de8a](https://github.com/Amyzellercode/zellercrm/commit/993de8ab1ccb4895296e2954756b0af32780cb60))
* map exported 'X / Twitter' header back to social_x in import suggestions ([afad0b3](https://github.com/Amyzellercode/zellercrm/commit/afad0b3bebd8c170b03f241380abdcd243ea874f))
* **mcp:** role-aware read scoping and account/contact linking in CRM tools ([6d6355a](https://github.com/Amyzellercode/zellercrm/commit/6d6355ae3a857a8d64609cd4a9bdea92f5e44c91))
* **mcp:** role-aware read scoping, FK linking, and user lookup for CRM tools ([5212f65](https://github.com/Amyzellercode/zellercrm/commit/5212f656d544bde30a5afcc39b17d82e5a5c97b6))
* **mcp:** set basePath so /api/mcp/{mcp,sse} actually route ([b8f74ab](https://github.com/Amyzellercode/zellercrm/commit/b8f74abe5d9e63a5eb72d5ba9ec606afa96daefd))
* **mcp:** set basePath so /api/mcp/{mcp,sse} actually route ([c05a042](https://github.com/Amyzellercode/zellercrm/commit/c05a0426f7faf292a2df9ee23b45dc0f62fdbcbd))
* merge dependabot vulnerability patches to main ([ac4d388](https://github.com/Amyzellercode/zellercrm/commit/ac4d388fd318b46abe25fd394abfed6a8be5c869))
* **migration:** scrub orphan creator FK refs before adding new FK constraint ([6610e5f](https://github.com/Amyzellercode/zellercrm/commit/6610e5f85a92df890e0765b12624921c3806492c))
* patch 9 open dependabot vulnerabilities ([87942dc](https://github.com/Amyzellercode/zellercrm/commit/87942dc05c05f3361dff523f015a632e722319d1))
* patch 9 open dependabot vulnerabilities via pnpm overrides ([e464ac8](https://github.com/Amyzellercode/zellercrm/commit/e464ac87993b41d3beff29ec149cc1070c7ec725))
* **prisma:** add missing crm_Target_Contact migration ([3a2da80](https://github.com/Amyzellercode/zellercrm/commit/3a2da80f277e6a5e5e79409f8840f90ad9706b8e))
* **prisma:** add missing migration for crm_Target_Contact table ([c6393ed](https://github.com/Amyzellercode/zellercrm/commit/c6393ed73e6278289cef0434de8d8532344e959c))
* **products:** require authentication on product read actions ([38e3645](https://github.com/Amyzellercode/zellercrm/commit/38e3645f46ddea7807171916289e69f2cc8824d4))
* **products:** require manager/admin role on product mutations ([8ae9a6b](https://github.com/Amyzellercode/zellercrm/commit/8ae9a6b1f3c184e35e0c69396f4c60e45311465d))
* **projects:** require board write/read scope on board mutations ([3971f1c](https://github.com/Amyzellercode/zellercrm/commit/3971f1c7614960a105f337cc595bedef523ed845))
* **projects:** require parent board write scope on section mutations ([3ee16e8](https://github.com/Amyzellercode/zellercrm/commit/3ee16e8da735de5665c90d8eea8195183d2b7d33))
* **projects:** scope project read actions by board access ([90f7e7d](https://github.com/Amyzellercode/zellercrm/commit/90f7e7de49eb1554f365ba6f3d44115826b7411d))
* **projects:** scope task mutations (board strict + assignee soft) ([8a67a42](https://github.com/Amyzellercode/zellercrm/commit/8a67a424e394965334b69e258b9b8fdd87913b79))
* **reports:** gate users-directory report behind manager/admin ([4125183](https://github.com/Amyzellercode/zellercrm/commit/4125183bfb68d2d1bc2f8df2cc7b4a2d3b870381))
* **reports:** scope config and schedule reads/mutations by role and ownership ([f3cd3f2](https://github.com/Amyzellercode/zellercrm/commit/f3cd3f2afb71e543b2aa8e02a83f43ac473aeec4))
* **reports:** scope dashboard tasks count and unified search by role ([c1a055e](https://github.com/Amyzellercode/zellercrm/commit/c1a055e7cd085555761683fa1c18aad33666be3a))
* **reports:** scope scheduled-report data by schedule owner role ([3c3af95](https://github.com/Amyzellercode/zellercrm/commit/3c3af95885df4d5c55a6931a8806929816e9250e))
* **security:** admin server action lockdown (Phase C) ([30e21a7](https://github.com/Amyzellercode/zellercrm/commit/30e21a739145cd54f957c36e6e5f6bcdaa59e6e0))
* **security:** authorize Resend key action, harden IMAP/SMTP connect surface ([758b2e9](https://github.com/Amyzellercode/zellercrm/commit/758b2e978d6606dc8e189632c629e6cc89498c6c))
* **security:** authz cleanup — drop is_admin, role enum (Phase F) ([54e38ef](https://github.com/Amyzellercode/zellercrm/commit/54e38ef119abdb2eaaf5f3976bbfaba13abbe114))
* **security:** close enrichment BOLA/IDOR (Phase B1) ([58d63c5](https://github.com/Amyzellercode/zellercrm/commit/58d63c5a4e29efcd46fe80e3ac09c080416de016))
* **security:** close GHSA-mg5f-m89f-4gmc + permission-driven authz foundation ([14ff6b5](https://github.com/Amyzellercode/zellercrm/commit/14ff6b5a71a3cb8f91fcfd1c3674a8c2177e0218))
* **security:** close invoice IDOR (Phase B2) ([782fb75](https://github.com/Amyzellercode/zellercrm/commit/782fb759763ce7199ab0b2fd28e075ea2e9034ab))
* **security:** enforce manager/admin RBAC in MCP product tools (GHSA-wv63-cq38-qg58) ([4502a9c](https://github.com/Amyzellercode/zellercrm/commit/4502a9c9fa0a88803265572254f0962a53658513))
* **security:** enforce manager/admin RBAC in MCP product tools (GHSA-wv63-cq38-qg58) ([04819a8](https://github.com/Amyzellercode/zellercrm/commit/04819a8530db2c50dcefadd7a19a9b90b6d5d42a))
* **security:** enforce object-level authz in MCP campaign tools (GHSA-c9vg-c532-ppqx) ([8ee01e1](https://github.com/Amyzellercode/zellercrm/commit/8ee01e1fe4fc313eee8de109bb07c582c0a73c09))
* **security:** enforce object-level authz in MCP campaign tools (GHSA-c9vg-c532-ppqx) ([59691b1](https://github.com/Amyzellercode/zellercrm/commit/59691b15aa81802b0fb337ebbe962aa6bed8ab50))
* **security:** resolve all open Dependabot and CodeQL alerts ([eca1e3f](https://github.com/Amyzellercode/zellercrm/commit/eca1e3fa70fc2a2bad358cee4de074d20f36a17a))
* **security:** resolve all open Dependabot and CodeQL alerts ([8ca89e8](https://github.com/Amyzellercode/zellercrm/commit/8ca89e81d2f041e34053eee37e12300c05f401d5))
* **security:** scope campaigns + templates (Phase E2) ([1cab980](https://github.com/Amyzellercode/zellercrm/commit/1cab98097f932a3bf69fccfad66b5d9c171ffa86))
* **security:** scope CRM account reads by role (Phase D1) ([fa61ee9](https://github.com/Amyzellercode/zellercrm/commit/fa61ee9a2b21f4a82a748889de7773666600bbeb))
* **security:** scope CRM accounts list by user authz read scope ([6fe04c5](https://github.com/Amyzellercode/zellercrm/commit/6fe04c540655da0624316cf7e0a77eec7611ab7c))
* **security:** scope CRM accounts list by user authz read scope ([89c8bc8](https://github.com/Amyzellercode/zellercrm/commit/89c8bc80af08b6406431e1c82f9e0fa28de50c96))
* **security:** scope CRM lead/contact/opportunity/contract reads by role (Phase D2) ([51b6319](https://github.com/Amyzellercode/zellercrm/commit/51b63193695c3b55d165e193f679f9dee8478b59))
* **security:** scope documents + bulk ops (Phase E3) ([cd3f380](https://github.com/Amyzellercode/zellercrm/commit/cd3f380dcef8a5460980a755a6ad963b92a5e164))
* **security:** scope products + account-products + invoice list (Phase E1) ([1d710c7](https://github.com/Amyzellercode/zellercrm/commit/1d710c7cf8d9c81c35b38982ae0d3916a3051cda))
* **security:** scope projects (boards/sections/tasks) (Phase E4) ([1fdcbb2](https://github.com/Amyzellercode/zellercrm/commit/1fdcbb21908bf9c8bfc3802eb595c300df770ae1))
* **security:** scope reports + dashboard + unified search by role (Phase B3) ([1caccba](https://github.com/Amyzellercode/zellercrm/commit/1caccba798a48001d15d9be115e2360857b766a9))
* **security:** scope targets, activities, audit log, similarity (Phase D3) ([f8213de](https://github.com/Amyzellercode/zellercrm/commit/f8213de60b561f269be4821439c07975f1d35035))
* **security:** verify TLS certificates on IMAP/SMTP connections ([ddd0f62](https://github.com/Amyzellercode/zellercrm/commit/ddd0f62c4da4786522566b7b38924df9363b8606))
* **security:** verify TLS certificates on IMAP/SMTP connections ([2717571](https://github.com/Amyzellercode/zellercrm/commit/2717571fb82b9ebd7ad6ca03c38092c9aa86fe91)), closes [#262](https://github.com/Amyzellercode/zellercrm/issues/262)
* **tests:** merge duplicate prismadb.documents mock keys after lowercase fix ([2b06d58](https://github.com/Amyzellercode/zellercrm/commit/2b06d585159ba6d9d20e7fc86e820b8ad822698c))


### Changed

* **admin:** normalize delete-user and invite-user to canonical requireRole helper ([d459840](https://github.com/Amyzellercode/zellercrm/commit/d459840214b0759f3b072a2d79df01ca69db5036))
* **admin:** normalize invoice-settings to canonical requireRole helper ([a096822](https://github.com/Amyzellercode/zellercrm/commit/a096822989823b87c636223c957dadf819f7be6d))
* **admin:** normalize send-mail-to-all to canonical requireRole helper ([b54f61b](https://github.com/Amyzellercode/zellercrm/commit/b54f61bc9819b464e9e9a834c184491fdfee96a9))
* **admin:** normalize system-api-keys actions to canonical requireRole helper ([6d7be04](https://github.com/Amyzellercode/zellercrm/commit/6d7be043057c44b7847727df92030d4899ac0483))
* **admin:** stop writing is_admin column from user actions ([8a975aa](https://github.com/Amyzellercode/zellercrm/commit/8a975aad71df0c563455d68263a0bf3929499fc8))
* **auth:** rename Better Auth roles member-&gt;manager, viewer-&gt;user ([c2c2b83](https://github.com/Amyzellercode/zellercrm/commit/c2c2b8396ad9a57dea89ed1531a59f6a704fc60a))
* **auth:** switch admin plugin to canonical user/manager/admin roles ([9281bd0](https://github.com/Amyzellercode/zellercrm/commit/9281bd0f42c26c8b7466e16efd3bc7122b863ca4))
* **authz:** gate admin layout on canonical role, drop is_admin check ([d411908](https://github.com/Amyzellercode/zellercrm/commit/d411908ec3ac379b47401634e9ed05448d6144fe))
* **crm:** minimal validation on account create/edit forms ([c6352ca](https://github.com/Amyzellercode/zellercrm/commit/c6352ca749b0b9b9770c83588e200601b5dc48fb))
* **crm:** relax NewAccountForm validation to require only name ([40af516](https://github.com/Amyzellercode/zellercrm/commit/40af516033522a8cd03c0f27114d80222e1c033f))
* **crm:** relax UpdateAccountForm validation to require only name ([157425f](https://github.com/Amyzellercode/zellercrm/commit/157425ff2bb06f0f85973115f94d6d49ac93787f))
* **crm:** stop routing CRM task comments through the projects module ([d484766](https://github.com/Amyzellercode/zellercrm/commit/d4847660d98e594b1bf9ad348feebe00a5982d11))
* **crm:** stop routing CRM task documents through the projects module ([1e435e3](https://github.com/Amyzellercode/zellercrm/commit/1e435e31005d3390d82caac69e182075a48fe68e))
* **crm:** wire account tasks to existing server actions ([a5d1826](https://github.com/Amyzellercode/zellercrm/commit/a5d182605834723b0387c4fd1905d94de59fcc34))
* extract TARGET_FIELDS into shared spreadsheet module ([0dc698f](https://github.com/Amyzellercode/zellercrm/commit/0dc698f28b9f2f7094439fbb1f07bc46281725ba))
* **invoices:** pass role-aware UserCtx to permission helpers ([3f5b74a](https://github.com/Amyzellercode/zellercrm/commit/3f5b74a1a6a3706016c04b12192e0efdce94ff24))
* **invoices:** replace all API routes with direct server actions ([a0129b4](https://github.com/Amyzellercode/zellercrm/commit/a0129b47643a118389ff229cfa6dc6475f989c25))
* **invoices:** require admin role on delete-payment via canonical helper ([d3e2b2c](https://github.com/Amyzellercode/zellercrm/commit/d3e2b2cf2a4d46739f37f32d880f9f41f1cb776b))
* **invoices:** role-aware permissions (user/manager/admin); add canReadInvoice ([9296db0](https://github.com/Amyzellercode/zellercrm/commit/9296db001065605978ee642d8de32db69851bcb5))
* remove axios dependency entirely ([3578333](https://github.com/Amyzellercode/zellercrm/commit/3578333e149db8ca45f95c549267222a8fdd6e32))
* **schema:** consolidate dual creator columns on contacts and opportunities (Phase F.1) ([21988e8](https://github.com/Amyzellercode/zellercrm/commit/21988e8a3047e3d0ca5efb607ee4d05e21c71156))
* **schema:** consolidate dual creator columns on contacts and opportunities (Phase F.1) ([708c3d5](https://github.com/Amyzellercode/zellercrm/commit/708c3d51b36b34ce56f9e39ad88f9119379babc1))
* **schema:** drop legacy is_admin and is_account_admin columns ([bfdd03f](https://github.com/Amyzellercode/zellercrm/commit/bfdd03f5bca4e0aafe349ccf8c3529501c049173))

## [0.22.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.21.2...v0.22.0) (2026-08-10)


### Added

* add CSV/Excel export to campaign targets table ([36e3299](https://github.com/pdovhomilja/nextcrm-app/commit/36e3299b42f4be267755de4e99d59def3afa0a67))
* add CSV/Excel export to target list detail page ([b6bb912](https://github.com/pdovhomilja/nextcrm-app/commit/b6bb9123a43419a391fd1d9c697dfd1a28e85531))
* add CSV/XLSX export utility for targets ([77ca5ae](https://github.com/pdovhomilja/nextcrm-app/commit/77ca5ae7069a74669f62cfbd7ec22942905a986a))
* CSV/Excel export for campaign targets and target lists ([f1ab4dc](https://github.com/pdovhomilja/nextcrm-app/commit/f1ab4dc684feaeddaad03afefdb0b68fd06c04c1))


### Fixed

* map exported 'X / Twitter' header back to social_x in import suggestions ([b457040](https://github.com/pdovhomilja/nextcrm-app/commit/b457040fa16c9ddc632ab71fecadeb67be769d82))
* **security:** verify TLS certificates on IMAP/SMTP connections ([41e3e6b](https://github.com/pdovhomilja/nextcrm-app/commit/41e3e6bfcebd6055f6345f4f32171b3090395df1))
* **security:** verify TLS certificates on IMAP/SMTP connections ([327d240](https://github.com/pdovhomilja/nextcrm-app/commit/327d240ab60f5d45e3066f3483e6e4585c7f92ab)), closes [#262](https://github.com/pdovhomilja/nextcrm-app/issues/262)


### Changed

* extract TARGET_FIELDS into shared spreadsheet module ([1b98905](https://github.com/pdovhomilja/nextcrm-app/commit/1b98905ae8e455d8da248b314e1b4b387de9e71f))

## [0.21.2](https://github.com/pdovhomilja/nextcrm-app/compare/v0.21.1...v0.21.2) (2026-08-01)


### Fixed

* **security:** resolve all open Dependabot and CodeQL alerts ([d7145d7](https://github.com/pdovhomilja/nextcrm-app/commit/d7145d7732c457ac40a6e1fccbf1ca53e8c1188a))
* **security:** resolve all open Dependabot and CodeQL alerts ([5a0c382](https://github.com/pdovhomilja/nextcrm-app/commit/5a0c3820c65d8c36eb41a5949b2ebccfebd73dbe))

## [0.21.1](https://github.com/pdovhomilja/nextcrm-app/compare/v0.21.0...v0.21.1) (2026-08-01)


### Fixed

* add calendar connection feedback ([854233f](https://github.com/pdovhomilja/nextcrm-app/commit/854233f4538264e4a9e6b4800b58051ba7b651c0))

## [0.21.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.20.2...v0.21.0) (2026-08-01)


### Added

* **campaigns:** add rendered email preview to template editor ([60d4933](https://github.com/pdovhomilja/nextcrm-app/commit/60d49338d2a6ebf8e6ceb19e7caf2174d60529f9))
* **campaigns:** react.email layout for campaign emails + editor preview ([90782a7](https://github.com/pdovhomilja/nextcrm-app/commit/90782a73c73f40942bdebc16c350c6c82870afcc))
* **campaigns:** wrap campaign emails in react.email layout ([57d4578](https://github.com/pdovhomilja/nextcrm-app/commit/57d457886508100ade9e39dd6481ad98a72d2d92))


### Fixed

* **campaigns:** sanitize template HTML and escape merge-tag values ([6ab4c86](https://github.com/pdovhomilja/nextcrm-app/commit/6ab4c866a954a84572a8cb3198b3d4ecb8c93c70))

## [0.20.2](https://github.com/pdovhomilja/nextcrm-app/compare/v0.20.1...v0.20.2) (2026-07-23)


### Fixed

* **deps:** resolve all 65 Dependabot security alerts ([29efcd7](https://github.com/pdovhomilja/nextcrm-app/commit/29efcd79c6386f1510563c124bcf4a99e5c42d7d))
* **deps:** resolve all 65 Dependabot security alerts (one PR) ([2647733](https://github.com/pdovhomilja/nextcrm-app/commit/2647733eb536d807adef070b719a95c0f8d7870f))
* **deps:** resolve all 65 Dependabot security alerts via pnpm overrides ([3412d9a](https://github.com/pdovhomilja/nextcrm-app/commit/3412d9ac05963f58c6f5708f863ad45b349e2039))

## [0.20.1](https://github.com/pdovhomilja/nextcrm-app/compare/v0.20.0...v0.20.1) (2026-07-23)


### Fixed

* **crm:** blank-UUID + create-in-context UX; ci(e2e): pin inngest-cli ([2e75f1c](https://github.com/pdovhomilja/nextcrm-app/commit/2e75f1cd11462a30b81a3fbd42c240597605fb2d))
* **crm:** normalize blank UUID fields in createAccount ([6123855](https://github.com/pdovhomilja/nextcrm-app/commit/612385540a259868ecfe1ea81e02d7ea6da0960c))
* **crm:** normalize blank UUID inputs and auto-fill account/assignee on create ([a5b0a78](https://github.com/pdovhomilja/nextcrm-app/commit/a5b0a782f327aadb21c7ccc8faeae63e1de818fa))

## [0.20.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.19.0...v0.20.0) (2026-07-22)


### Added

* **mcp:** reassignment on accounts, contacts and leads; scope CRM lead tools ([0591426](https://github.com/pdovhomilja/nextcrm-app/commit/05914261d7236370237d50edde9d3474d91ea4f3))
* **mcp:** reassignment on accounts, contacts and leads; scope CRM lead tools ([2e7220a](https://github.com/pdovhomilja/nextcrm-app/commit/2e7220a50d1b98d668192299a1e42ba90099b1c9))

## [0.19.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.18.0...v0.19.0) (2026-07-22)


### Added

* **mcp:** add crm_list_users and opportunity reassignment ([d2adc62](https://github.com/pdovhomilja/nextcrm-app/commit/d2adc6262086a975369cc71411e81fd166d89490))


### Fixed

* **mcp:** role-aware read scoping and account/contact linking in CRM tools ([3a89d55](https://github.com/pdovhomilja/nextcrm-app/commit/3a89d5555277c1c5a1fbb83826f91c6a9ee2ce12))
* **mcp:** role-aware read scoping, FK linking, and user lookup for CRM tools ([4575e9d](https://github.com/pdovhomilja/nextcrm-app/commit/4575e9d7dec10a9f689a910ded518a0797cfe2f3))

## [0.18.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.17.0...v0.18.0) (2026-07-22)


### Added

* **admin:** mount Resend service card at /admin/services ([3c552db](https://github.com/pdovhomilja/nextcrm-app/commit/3c552dba846415cbaeb267474f56afa95d84cac5))
* **authz:** object-level authorization on account write actions ([69edcfe](https://github.com/pdovhomilja/nextcrm-app/commit/69edcfea75ec2af1565a54424b93ac17fae72621))
* **authz:** object-level authorization on contact write actions ([c08d61b](https://github.com/pdovhomilja/nextcrm-app/commit/c08d61be5782aa452c1516facea8c98ecccc110c))
* **authz:** object-level authorization on contract write actions ([12750da](https://github.com/pdovhomilja/nextcrm-app/commit/12750dae561e15add52ef62d0bdfefd55b6288eb))
* **authz:** object-level authorization on CRM task write actions ([8be1abb](https://github.com/pdovhomilja/nextcrm-app/commit/8be1abb88516555c8779fdca0cbe4c7adaf15a36))
* **authz:** object-level authorization on lead write actions ([747d9dc](https://github.com/pdovhomilja/nextcrm-app/commit/747d9dc3c56ee97fd278758e79f6744a8fd6ebec))
* **authz:** object-level authorization on opportunity write actions ([c0c8379](https://github.com/pdovhomilja/nextcrm-app/commit/c0c837913aff65ccaede4deb36c4dc5611c564ff))
* **authz:** object-level authorization on target write actions ([522ac83](https://github.com/pdovhomilja/nextcrm-app/commit/522ac832b9bf5b8b4fcf13cbeb12685596e09e53))
* **authz:** object-level authorization on target-list write actions ([a748ef1](https://github.com/pdovhomilja/nextcrm-app/commit/a748ef1f124ebde27a5e07aeac0d65b4084d262b))
* **authz:** parent-scoped authorization on contract line-items ([cad5741](https://github.com/pdovhomilja/nextcrm-app/commit/cad57416c5cefe2a723adf7c7c74b3b296a101fc))
* **authz:** parent-scoped authorization on opportunity line-items ([a973962](https://github.com/pdovhomilja/nextcrm-app/commit/a973962deb106897e591169aa98312fd830cec15))
* **authz:** write-scope asserts for lead, opportunity, contract, target-list, crm-task, line-items ([4eead0e](https://github.com/pdovhomilja/nextcrm-app/commit/4eead0e6ee22e5112e3dcf548bc7854f02624de9))
* **dev:** Inngest dev server via docker-compose.dev.yml for host development ([7596978](https://github.com/pdovhomilja/nextcrm-app/commit/7596978289202d402246f27b47c2e3c15bc786c8))
* **dev:** local pgvector Postgres service for host development ([c28e2d4](https://github.com/pdovhomilja/nextcrm-app/commit/c28e2d41394889682b56f8f8210174cfd8375c20))
* **dev:** point DATABASE_URL at local Postgres, add db:migrate ([0e9b69c](https://github.com/pdovhomilja/nextcrm-app/commit/0e9b69c1268a1081c98a7dd7c921556bf22e6485))
* **dev:** seed local database, add db:seed and db:reset ([8f4f415](https://github.com/pdovhomilja/nextcrm-app/commit/8f4f41520df2350bee74640209d8bac70be85c14))
* **mcp:** assertScopeOrNotFound adapter for object-level tool authorization ([d9e12d2](https://github.com/pdovhomilja/nextcrm-app/commit/d9e12d270a0b01477421d44a335ff52a517ce7b9))
* **mcp:** object-level authorization on project board tools ([df19c69](https://github.com/pdovhomilja/nextcrm-app/commit/df19c69fc49a2829dc04baae812a4bfe5a2cde14))
* **mcp:** object-level authorization on project comment + document-link tools ([b8d967c](https://github.com/pdovhomilja/nextcrm-app/commit/b8d967cf2bc7b078e289ccb94280a300c3de9d78))
* **mcp:** object-level authorization on project section tools ([a5faf98](https://github.com/pdovhomilja/nextcrm-app/commit/a5faf98d8362f10a5f7ae2ca5877ae47bd28ff0e))
* **mcp:** object-level authorization on project task tools; drop userBoardWhere ([f36e85a](https://github.com/pdovhomilja/nextcrm-app/commit/f36e85a2dc0f96c8af19bd68cf6818fd440ee462))
* **mcp:** read-scoped authorization on project watch_board (escalation fix) ([7f6d2f8](https://github.com/pdovhomilja/nextcrm-app/commit/7f6d2f83a2b1e6f19fc9445cdb4989141ab5e1fb))
* **net:** assertPublicHost — resolve-validate-pin guard against SSRF/DNS-rebinding ([e4f8e95](https://github.com/pdovhomilja/nextcrm-app/commit/e4f8e954248f2484341c31f5bfc8d0bb9f01ac90))
* **net:** ip-rules — refuse non-public-unicast addresses (SSRF) ([17cbb28](https://github.com/pdovhomilja/nextcrm-app/commit/17cbb28de85aa29192b4a66837372a148aaf794c))
* **security:** SSRF host-guard on IMAP test/discover/create sinks ([a775e0d](https://github.com/pdovhomilja/nextcrm-app/commit/a775e0d0498362b7240e82b6543cdf25e9c1249e))
* **security:** SSRF host-guard on SMTP send and background IMAP connect ([53eeac4](https://github.com/pdovhomilja/nextcrm-app/commit/53eeac43eb4ec9aa3ba57777d88a01504f6c570c))


### Fixed

* **authz:** guard directly-callable convertTarget action ([8b9f291](https://github.com/pdovhomilja/nextcrm-app/commit/8b9f291cdccdcf51c31562d8ceed072205845566))
* **authz:** use shared opportunity write-scope in setInactiveOpportunity ([30f9544](https://github.com/pdovhomilja/nextcrm-app/commit/30f95446bb825ded9105604a39c2c81b5ad86a58))
* **db-guard:** block empty/unresolvable host instead of passing it ([521137f](https://github.com/pdovhomilja/nextcrm-app/commit/521137f93129f3af146b4ee2fc7faf10c6a4390d))
* **db-guard:** close query-string [@localhost](https://github.com/localhost) bypass, fix bracketed IPv6 ([8909bc3](https://github.com/pdovhomilja/nextcrm-app/commit/8909bc3f631cc007bfdd21e76c6f94a35a9aa8cf))
* **dev:** bind local Postgres to loopback and bound db:wait retries ([989e2ed](https://github.com/pdovhomilja/nextcrm-app/commit/989e2ed9ccdf8b621147db962121b9b5a18721b0))
* **dev:** guard db scripts against remote DB and correct local Postgres docs ([3482cd0](https://github.com/pdovhomilja/nextcrm-app/commit/3482cd0936de273d6ce24cf28018ac8ff965cd7b))
* **security:** authorize Resend key action, harden IMAP/SMTP connect surface ([648160f](https://github.com/pdovhomilja/nextcrm-app/commit/648160f0dfdaa235d45ec8b3806f4552277244f3))

## [0.17.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.16.0...v0.17.0) (2026-07-20)


### Added

* **calendar:** emit outbound sync events from activity writers ([de3c34b](https://github.com/pdovhomilja/nextcrm-app/commit/de3c34b5ad903ab654930c7c5982949456737b4d))
* **calendar:** two-way sync upgrade button + scope level in profile UI ([2cf2f1d](https://github.com/pdovhomilja/nextcrm-app/commit/2cf2f1d68ef5727bfd22c1213d242b9437012e66))


### Fixed

* **calendar:** close unrelated-connection guard gap for disconnected accounts ([1c13839](https://github.com/pdovhomilja/nextcrm-app/commit/1c138396ed6b2132509b3ca3ce6e4c3c0cb7556b))
* **calendar:** harden outbound push against guest-list wipes, false revocations, and unauthorized writes ([03e3f60](https://github.com/pdovhomilja/nextcrm-app/commit/03e3f60e75aa6d577b2c76588c0c00b06d328d9c))
* **calendar:** harden outbound sync emit against slow sends and fix write/emit ordering ([55845a1](https://github.com/pdovhomilja/nextcrm-app/commit/55845a1a7cf32d9c268775c2328f9c234c5e5be2))
* **calendar:** keep stored scopeLevel truthful, kill race duplicates, patch back-dated meetings ([e0729cc](https://github.com/pdovhomilja/nextcrm-app/commit/e0729cc3920aa3415f5bde05140d3c14ac0a9da7))
* **calendar:** stop notes edits on past meetings from emailing customers ([9eb4344](https://github.com/pdovhomilja/nextcrm-app/commit/9eb4344a52e5e1af8c0e1dfddc64f5d2eddaeb47))

## [0.16.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.15.0...v0.16.0) (2026-07-19)


### Added

* **calendar:** CalendarConnection + crm_CalendarEvents models for Phase 4 sync ([816a5c0](https://github.com/pdovhomilja/nextcrm-app/commit/816a5c045f876f456418a0bd28a19fee62a73784))
* **calendar:** Calendly admin settings page + org webhook subscription ([bdede85](https://github.com/pdovhomilja/nextcrm-app/commit/bdede854b6e26242f76cdd7ef16312605f293a3e))
* **calendar:** Calendly settings storage + signed webhook endpoint ([f92c728](https://github.com/pdovhomilja/nextcrm-app/commit/f92c7283359dae3cdf63f4c7c9050de64fa04131))
* **calendar:** Calendly webhook HMAC signature verification ([42d3142](https://github.com/pdovhomilja/nextcrm-app/commit/42d31424c7036187e7edd96741c7a7292306ea92))
* **calendar:** counterparty email matcher (contact &gt; target &gt; lead) ([e942991](https://github.com/pdovhomilja/nextcrm-app/commit/e9429917eeb99ac3522dab7d79944bbdf37311b1))
* **calendar:** dedicated Calendar tab on profile + OAuth result banner ([7240889](https://github.com/pdovhomilja/nextcrm-app/commit/724088999b2d139d6e09d993624df9c6441aaf94))
* **calendar:** Google Calendar incremental polling sync via Inngest ([f70b663](https://github.com/pdovhomilja/nextcrm-app/commit/f70b66320de1b508f6207aa8f760496921cf4898))
* **calendar:** Google Calendar OAuth connect flow (readonly scope) ([2e8b591](https://github.com/pdovhomilja/nextcrm-app/commit/2e8b59147bde47a176dee78da272591aecbd4d0d))
* **calendar:** inngest processor for crm/calendar.event.received ([dc96cd1](https://github.com/pdovhomilja/nextcrm-app/commit/dc96cd1dcbedfe9a89c4eaf941c910ce330196bd))
* **calendar:** profile UI for Google Calendar connections ([ea5e7c5](https://github.com/pdovhomilja/nextcrm-app/commit/ea5e7c5dc6bfed2ed7be97f7fe2b67ebcb3a1be3))
* **calendar:** register calendar settings in admin sidebar ([7791ab2](https://github.com/pdovhomilja/nextcrm-app/commit/7791ab2d6ac62c1111a2ae1a875fdd1533b206d2))
* **calendar:** shared idempotent calendar-event processor ([2e4aa70](https://github.com/pdovhomilja/nextcrm-app/commit/2e4aa70712cf45400544256bb0fe7a7b1160573d))
* **crm:** AQUNAMA Phase 4 — calendar sync (Calendly + Google Calendar inbound) ([57fa4ec](https://github.com/pdovhomilja/nextcrm-app/commit/57fa4ec4c26b481c06a874db00a8f4f9503bfc93))


### Fixed

* **calendar:** classify Google auth-revocation vs rate-limit/token errors ([51cdbec](https://github.com/pdovhomilja/nextcrm-app/commit/51cdbecfbc5dbdcfcc6d4475ac2b8a51886ad345))
* **calendar:** exception-safe Calendly subscription + shared authz in admin settings ([5a127ab](https://github.com/pdovhomilja/nextcrm-app/commit/5a127ab6db964a5d125ecd0ac366ff91e22064a9))
* **calendar:** filter soft-deleted contacts/leads in matcher ([eba5ecd](https://github.com/pdovhomilja/nextcrm-app/commit/eba5ecd39595c6fbd32c4e0aec9d9071c423e3a2))
* **calendar:** log dropped Calendly webhook events missing uri/start_time ([290f23f](https://github.com/pdovhomilja/nextcrm-app/commit/290f23f26d21672d7f5d05c29722a4674e2166a0))
* **calendar:** OAuth state (CSRF) validation + narrowed error logging ([5978f82](https://github.com/pdovhomilja/nextcrm-app/commit/5978f82b072c2b1f2c7f06f542c6217a4a343695))
* **calendar:** record lastSyncError for upsert-loop failures in google sync ([fc3dedd](https://github.com/pdovhomilja/nextcrm-app/commit/fc3deddd447c20b387755bf9f0001222d1fd7e47))
* **calendar:** transactional upsert + P2002 race handling in calendar processor ([7b8c34a](https://github.com/pdovhomilja/nextcrm-app/commit/7b8c34a6a9f07b2713132df66d02df0735df87fe))
* **crm:** exclude cancelled activities from the Phase 2 kill-clock query ([a2c8a2d](https://github.com/pdovhomilja/nextcrm-app/commit/a2c8a2dfdb2d01531e36116b4a37f75d6c740bb4))

## [0.15.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.14.0...v0.15.0) (2026-07-19)


### Added

* AQUNAMA Phase 3 — SOW/quote approval workflow + case-study flags ([43f95bf](https://github.com/pdovhomilja/nextcrm-app/commit/43f95bfdac390298c70751ff462143f4987a312d))

## [0.14.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.13.3...v0.14.0) (2026-07-19)


### Added

* **admin:** connect automation trigger kinds to sales stages in CRM settings ([49847ba](https://github.com/pdovhomilja/nextcrm-app/commit/49847bab3a41f5617530de09edd4e79ad3193d69))
* **admin:** instance-grade funnel timing settings page ([e94d1da](https://github.com/pdovhomilja/nextcrm-app/commit/e94d1da373c2e84b68d72bb6104aea3f39958c2c))
* AQUNAMA Phase 2 — funnel timer & task engine (kill rule, cadence, care, recycle, renewals) ([8d2a866](https://github.com/pdovhomilja/nextcrm-app/commit/8d2a866c703f950defc6517cd4411cb05de32a25))
* **crm:** 45-day kill rule cron with inbound-email/activity clock ([aa591a1](https://github.com/pdovhomilja/nextcrm-app/commit/aa591a142ccda15e2304ecdbd62c21405cea41fa))
* **crm:** auto-task helper and 5-touch qualified follow-up cadence ([366af8a](https://github.com/pdovhomilja/nextcrm-app/commit/366af8a7d8debb1acd37d77cbac087ee5a1e4a60))
* **crm:** care touchpoint engine (check-in, referral, quarterly) ([ab9aff8](https://github.com/pdovhomilja/nextcrm-app/commit/ab9aff8fc39061dd474a26b16a8488ebdfe3324f))
* **crm:** configurable timer logic — business days, cadence/care schedules, kill predicate, settings loader ([cd956fc](https://github.com/pdovhomilja/nextcrm-app/commit/cd956fce0934aeb9865ae64496d6c27b0f23c6ce))
* **crm:** emit crm/opportunity.stage-changed from all stage-writing actions ([413bd48](https://github.com/pdovhomilja/nextcrm-app/commit/413bd48d558574d297e24f24d0eb0bb8323c577c))
* **crm:** stage_kind on sales stages, task-opportunity link, stage_entered_at ([8eff98c](https://github.com/pdovhomilja/nextcrm-app/commit/8eff98c4ea8b493ff7a3847450498caa3977fbae))
* **crm:** target recycle cron with Recycled list and admin digest ([8c83243](https://github.com/pdovhomilja/nextcrm-app/commit/8c8324357bd011aae849daab8ec14b8930aeb3c8))
* **crm:** weekly renewal reminder sweep for contracts and account products ([18da8de](https://github.com/pdovhomilja/nextcrm-app/commit/18da8de91bac437ca271cf4585aa94da96d4a905))


### Fixed

* **crm:** final-review fixes — protect re-engaged targets and completed renewals ([f2a7434](https://github.com/pdovhomilja/nextcrm-app/commit/f2a743412d657a8ac99782595790ab9e8b37c937))

## [0.13.3](https://github.com/pdovhomilja/nextcrm-app/compare/v0.13.2...v0.13.3) (2026-07-17)


### Fixed

* **ci:** make migration chain replayable on a fresh database ([2c34ebb](https://github.com/pdovhomilja/nextcrm-app/commit/2c34ebbe203ffa620535eaf3437d2db5ed067d15))
* **crm:** drop empty currency on opportunity update; e2e round 2 ([bbac5ea](https://github.com/pdovhomilja/nextcrm-app/commit/bbac5ea7a9e57b66346101f678806a4cfc8766f1))

## [0.13.2](https://github.com/pdovhomilja/nextcrm-app/compare/v0.13.1...v0.13.2) (2026-07-17)


### Fixed

* **crm:** align lead/contract table display schemas with DB nullability ([c1c8ef4](https://github.com/pdovhomilja/nextcrm-app/commit/c1c8ef42be008c4e4951efa336a5450b9fbaeb28))
* **crm:** align table display schemas with DB nullability (close_date, leads, contracts) ([37cfbef](https://github.com/pdovhomilja/nextcrm-app/commit/37cfbefd7df79c36bfebb04cc8aaa01581002a1b))

## [0.13.1](https://github.com/pdovhomilja/nextcrm-app/compare/v0.13.0...v0.13.1) (2026-07-17)


### Fixed

* **crm:** serialize Prisma Decimals in opportunities/contracts fetches (RSC boundary error) ([48a6bb0](https://github.com/pdovhomilja/nextcrm-app/commit/48a6bb0550d9fafc174c55911e5aff7215b794e3))
* **crm:** serialize Prisma Decimals in opportunities/contracts list fetches ([ffba94a](https://github.com/pdovhomilja/nextcrm-app/commit/ffba94aebec29c2bdad101a6d6d6875073cc3583))

## [0.13.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.12.3...v0.13.0) (2026-07-17)


### Added

* add Mailtrap email provider helper ([562aeb9](https://github.com/pdovhomilja/nextcrm-app/commit/562aeb947f5f5c2038d29753176fb871562e19a7))
* add Mailtrap sandbox email testing provider ([9dd0a7d](https://github.com/pdovhomilja/nextcrm-app/commit/9dd0a7db078334d418576c5eea1ccad04e8758d9))
* add real sending capability to Mailtrap helper ([7229e90](https://github.com/pdovhomilja/nextcrm-app/commit/7229e903c494efed6aed4987066da8cbe079a0af))
* AQUNAMA Phase 1 — global email opt-out, target-to-deal conversion, delivery deadline, XLSX import ([f8dacb3](https://github.com/pdovhomilja/nextcrm-app/commit/f8dacb3b3ab3e2c6626e8d9019233785d468f792))
* **campaigns:** enforce global do_not_email across send pipeline and import ([4471454](https://github.com/pdovhomilja/nextcrm-app/commit/44714549f46acbe1f2f03ecc4b8f581180ce4887))
* **campaigns:** unsubscribe sets global do_not_email suppression on targets ([6a97c5b](https://github.com/pdovhomilja/nextcrm-app/commit/6a97c5b43da924d4961e6d0648ab154d598f5c82))
* **crm:** add delivery_deadline field to opportunities (PO-stage requirement) ([fba530b](https://github.com/pdovhomilja/nextcrm-app/commit/fba530b9354f2a3dc626300b380a6d00870902b5))
* **crm:** add global do_not_email flag on targets and delivery_deadline on opportunities ([8a7c8a6](https://github.com/pdovhomilja/nextcrm-app/commit/8a7c8a6ff525d9f04ad3d9c2ed2ef2e25b62aab6))
* **crm:** convert target to deal with campaign attribution and entry stage ([2d79035](https://github.com/pdovhomilja/nextcrm-app/commit/2d79035315263eaae9c1f009c3def7c76f74158b))
* **crm:** support XLSX target imports via shared spreadsheet parser ([4dabb29](https://github.com/pdovhomilja/nextcrm-app/commit/4dabb29b2e0a35a2f150cc45c0dd0e2e96b61180))


### Fixed

* **campaigns:** case-insensitive suppression matching and send-step last-gate guard ([f9df822](https://github.com/pdovhomilja/nextcrm-app/commit/f9df822c230c5da8b1c2dbb31a2d53301e0b9b4e))
* **campaigns:** keep unsubscribe confirmation on suppression write failure ([2bee7dc](https://github.com/pdovhomilja/nextcrm-app/commit/2bee7dc07fd15fc516592131476aa2fea561b77d))
* **crm:** make target-to-deal conversion idempotent and honor error contract ([a27cf00](https://github.com/pdovhomilja/nextcrm-app/commit/a27cf00c1740c8f69cb0474dd1f365d1ff28670c))
* **deploy:** pin pnpm 11 via packageManager so nixpacks doesn't build with pnpm 9 ([aedeab3](https://github.com/pdovhomilja/nextcrm-app/commit/aedeab33fd90f10f22e3c842daf8d59819b553b4))
* **deploy:** use current corepack in nixpacks and migrate to pnpm 11 allowBuilds ([82ccda4](https://github.com/pdovhomilja/nextcrm-app/commit/82ccda4b2b577cb46cf9f911fbac7d34ee26ff7c))
* **deps:** pin kysely 0.28 — restore main deployability (better-auth 1.6.13 adapter breakage) ([b7392ac](https://github.com/pdovhomilja/nextcrm-app/commit/b7392acc5d0e42ff0465e0db0b9a20c14deafbfd))
* **deps:** pin kysely to 0.28 line — better-auth 1.6.13 adapter incompatible with kysely 0.29 ([284a305](https://github.com/pdovhomilja/nextcrm-app/commit/284a30519f12cc95a53bb56dbc43ac70f8629478))

## [0.12.3](https://github.com/pdovhomilja/nextcrm-app/compare/v0.12.2...v0.12.3) (2026-06-13)


### Bug Fixes

* **security:** enforce manager/admin RBAC in MCP product tools (GHSA-wv63-cq38-qg58) ([02e7a22](https://github.com/pdovhomilja/nextcrm-app/commit/02e7a226e1363a060013cc16bb4d26d4c190bc27))
* **security:** enforce manager/admin RBAC in MCP product tools (GHSA-wv63-cq38-qg58) ([1c41d58](https://github.com/pdovhomilja/nextcrm-app/commit/1c41d5832629f50e658fb64a884c98e846830549))

## [0.12.2](https://github.com/pdovhomilja/nextcrm-app/compare/v0.12.1...v0.12.2) (2026-06-13)


### Bug Fixes

* **security:** enforce object-level authz in MCP campaign tools (GHSA-c9vg-c532-ppqx) ([d219b7b](https://github.com/pdovhomilja/nextcrm-app/commit/d219b7b47291e52cd200fba193f4da68c6dde75a))
* **security:** enforce object-level authz in MCP campaign tools (GHSA-c9vg-c532-ppqx) ([88258b1](https://github.com/pdovhomilja/nextcrm-app/commit/88258b1cce63f42e9399b1ce9575a72dc89b72c5))

## [0.12.1](https://github.com/pdovhomilja/nextcrm-app/compare/v0.12.0...v0.12.1) (2026-05-11)


### Bug Fixes

* **mcp:** set basePath so /api/mcp/{mcp,sse} actually route ([16fb5be](https://github.com/pdovhomilja/nextcrm-app/commit/16fb5be137fb54b5de324f659dd8b48881004aad))
* **mcp:** set basePath so /api/mcp/{mcp,sse} actually route ([3c36be2](https://github.com/pdovhomilja/nextcrm-app/commit/3c36be22658d27092606e32dea3d083fcc0b1bfd))

## [0.12.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.11.1...v0.12.0) (2026-05-08)


### Features

* **authz:** add account read-scope helpers ([6fdff66](https://github.com/pdovhomilja/nextcrm-app/commit/6fdff669fdd1db42789b106e0e4f8939a98f6ff0))
* **authz:** add account write-scope assertion helper ([fb4b8f6](https://github.com/pdovhomilja/nextcrm-app/commit/fb4b8f66052d62097bea9c66c1d0c8bf9ae4c05c))
* **authz:** add account/lead/opportunity id-filter helpers (similarity post-filter) ([98b32f1](https://github.com/pdovhomilja/nextcrm-app/commit/98b32f17eb2c11e9237f95eddc85d0bf89d8206b))
* **authz:** add activity-for-entity scope dispatch helper ([db08f51](https://github.com/pdovhomilja/nextcrm-app/commit/db08f51b8b943ffac1a755029a27c352e6ac7a6f))
* **authz:** add AuthenticationError and AuthorizationError ([47e4980](https://github.com/pdovhomilja/nextcrm-app/commit/47e49805928975b8a0932c380871c0e174c287c1))
* **authz:** add barrel export ([48a2a5e](https://github.com/pdovhomilja/nextcrm-app/commit/48a2a5e379f8a634ebd322603c139c2cf715a399))
* **authz:** add board and task read/write scope helpers ([380e6a5](https://github.com/pdovhomilja/nextcrm-app/commit/380e6a59f636416ef1650ef849b947b6edab7a4a))
* **authz:** add bulk-id authorization filters for contacts and targets ([388d29d](https://github.com/pdovhomilja/nextcrm-app/commit/388d29dcbea52c6dfcfe2e3720ed2bb3fc515cb7))
* **authz:** add campaign and template read/write scope helpers ([6af7af0](https://github.com/pdovhomilja/nextcrm-app/commit/6af7af033f6d49df1844fb07e2687401d110c7c0))
* **authz:** add canonical AppRole type and legacy role mapper ([1350ed3](https://github.com/pdovhomilja/nextcrm-app/commit/1350ed39623a61aa31ed2e9220fa66b7782796a4))
* **authz:** add document read/write scope helpers (linked-entity aware) ([f2122a2](https://github.com/pdovhomilja/nextcrm-app/commit/f2122a23eec404e431445d7645ef9c3431e5bdce))
* **authz:** add enrichment cancel permission helpers ([6acbfec](https://github.com/pdovhomilja/nextcrm-app/commit/6acbfec765d0bc68748a20f8b3df75602220bd5c))
* **authz:** add lead/contact/opportunity/contract read-scope helpers (linked-account aware) ([bfaef87](https://github.com/pdovhomilja/nextcrm-app/commit/bfaef8756686eb2c07236b1250e67032cbaafbb4))
* **authz:** add read/write assertion helpers for contacts and targets ([e0fff6b](https://github.com/pdovhomilja/nextcrm-app/commit/e0fff6b911f145fe1878de9d3969657b897bb2f9))
* **authz:** add ReportScope builder for per-role report data filtering ([0035bf0](https://github.com/pdovhomilja/nextcrm-app/commit/0035bf0cb3047a5a54c7caf7eb898b2037306d79))
* **authz:** add requireAuthenticated, requireRole, role predicates ([30c3472](https://github.com/pdovhomilja/nextcrm-app/commit/30c3472f94e6e2555ad2ca9109f793c795b7c497))
* **authz:** add route response helpers (401/403/404) ([7ad29ae](https://github.com/pdovhomilja/nextcrm-app/commit/7ad29aea1639d3c403d1283698c65c74aef164ed))
* **authz:** add scoped contact and target update helpers ([071cb2c](https://github.com/pdovhomilja/nextcrm-app/commit/071cb2ceab48858c505a3ed7e3b0ae47119e7b1e))
* **authz:** add target and target-list read-scope helpers ([45b82a8](https://github.com/pdovhomilja/nextcrm-app/commit/45b82a87538d54921cbb370b9d873cb42cc68a35))
* **authz:** align UI/action callers to canonical role names ([1dc5618](https://github.com/pdovhomilja/nextcrm-app/commit/1dc5618c6c17d3e5b96295c9c38ff2324fd91447))
* **authz:** switch Users.role to Prisma enum AppRole ([d598305](https://github.com/pdovhomilja/nextcrm-app/commit/d598305ebc97b15852f41d5cc5f1807836302cfe))
* **authz:** validate setUserRole against canonical AppRole ([77241b7](https://github.com/pdovhomilja/nextcrm-app/commit/77241b726b748a5191c5acb6c331888672eac947))
* **db:** backfill canonical roles (admin/manager/user) and sync is_admin ([f7475f5](https://github.com/pdovhomilja/nextcrm-app/commit/f7475f5d081a1cba0ae76c9af962c10f5209648b))
* **reports:** per-category functions accept ReportScope to filter data by role ([87d73e0](https://github.com/pdovhomilja/nextcrm-app/commit/87d73e0c982b11c259bbdeef298641e087fd4251))
* **security:** permission-driven authorization migration (Phases A → F.1) ([e06478f](https://github.com/pdovhomilja/nextcrm-app/commit/e06478ff16f9a7472c6d16cd0ef6e96c5c409446))


### Bug Fixes

* **account-products:** require account read scope on get-account-products ([36f2d0d](https://github.com/pdovhomilja/nextcrm-app/commit/36f2d0d073adcab04729e15395d1f1b1d0273890))
* **account-products:** require account write scope on assignment mutations ([dfa1850](https://github.com/pdovhomilja/nextcrm-app/commit/dfa18506a9d96eacb31c7014ca39d17cf46c1c56))
* **admin:** require admin role on activate/deactivate user (close audit gap) ([8215af2](https://github.com/pdovhomilja/nextcrm-app/commit/8215af27d86575b3a094e554dbe4e401810fc5e4))
* **admin:** require admin role on CRM-settings server actions ([be27db7](https://github.com/pdovhomilja/nextcrm-app/commit/be27db7b31c6e65796bed7d73d1ba8433173a561))
* **admin:** require admin role on currency server actions ([8dfc9ad](https://github.com/pdovhomilja/nextcrm-app/commit/8dfc9ad99c3c5224675f9d11046f014a98c1115c))
* **api:** filter contact bulk enrichment ids by user scope ([5014d9a](https://github.com/pdovhomilja/nextcrm-app/commit/5014d9ad747c75e0278950a361e30073d09c7c17))
* **api:** filter target bulk enrichment ids by user scope ([4af94fe](https://github.com/pdovhomilja/nextcrm-app/commit/4af94fe910f9eb3b0290fe519eae0e7efde1a72e))
* **api:** require contact write scope on enrich POST/DELETE ([b1530c0](https://github.com/pdovhomilja/nextcrm-app/commit/b1530c091ebc15e255ccce47e220b755bae8db17))
* **api:** require invoice read scope on PDF route ([a35d7d0](https://github.com/pdovhomilja/nextcrm-app/commit/a35d7d0c0c7d12a58b4567bb3fa62fe1dc324508))
* **api:** require parent target write scope on target-contact create ([28912b4](https://github.com/pdovhomilja/nextcrm-app/commit/28912b43aed27a08243c066ed644d57c195fe817))
* **api:** require target write scope and contact linkage on per-target-contact enrich ([80f9ee4](https://github.com/pdovhomilja/nextcrm-app/commit/80f9ee4dadaff611cbd4fc578e2d7048e371ca76))
* **api:** require target write scope on enrich POST/DELETE (auto-fixes campaign re-export) ([18a0b56](https://github.com/pdovhomilja/nextcrm-app/commit/18a0b562a14b36f3b6137a18a856fb8f616f3414))
* **api:** require target write scope on per-target enrich (auto-fixes campaign re-export) ([85cfe72](https://github.com/pdovhomilja/nextcrm-app/commit/85cfe720fb2281eb73d74ec737d3c7037442b37f))
* **api:** scope reports/export by role; gate users-directory report ([571fbf3](https://github.com/pdovhomilja/nextcrm-app/commit/571fbf37caf71a7a2f66980cf28c6e1a710141e7))
* **api:** scoped contact PATCH closes BOLA/IDOR (GHSA-mg5f-m89f-4gmc) ([c80d3ec](https://github.com/pdovhomilja/nextcrm-app/commit/c80d3ec564ddb5f3bf38aec54ff5fb5aa3e7e90c))
* **api:** scoped target PATCH closes BOLA/IDOR (auto-fixes campaign re-export) ([cd0ed0a](https://github.com/pdovhomilja/nextcrm-app/commit/cd0ed0a4139398cf003505c44e9bc8a91a9def76))
* **auth:** align auth-client roles with renamed manager/user ([66e0e84](https://github.com/pdovhomilja/nextcrm-app/commit/66e0e8428556c9c75da28f601ef33d38cf94a674))
* **authz:** drop readonly tuple from accountUserScopeOR for Prisma compat ([39bcebe](https://github.com/pdovhomilja/nextcrm-app/commit/39bcebe70acfe17a391b1d0ad06178c7752b0a43))
* **authz:** include deletedAt:null in target read scope (crm_Targets has soft-delete) ([7a8fc2e](https://github.com/pdovhomilja/nextcrm-app/commit/7a8fc2e620c11e3abd9c3b1456703eced05eb61d))
* **authz:** replace is_admin checks with requireRole on admin invoice routes ([a54ed98](https://github.com/pdovhomilja/nextcrm-app/commit/a54ed9836deb11b7ba8714fc15a0248d36824ab3))
* **authz:** use lowercase prismadb.documents accessor ([a816361](https://github.com/pdovhomilja/nextcrm-app/commit/a816361a0029165294d1e201423a10fdc4e570d8))
* **campaign-templates:** scope template reads/mutations by role and ownership ([417ae5a](https://github.com/pdovhomilja/nextcrm-app/commit/417ae5a8e7ad6049397af2a03997d27b81cc2bfe))
* **campaigns:** narrow createCampaign result before using campaign.id ([1794a88](https://github.com/pdovhomilja/nextcrm-app/commit/1794a88ebde37b491a532865229c78175e5f65f4))
* **campaigns:** require auth + ownership on create/update/delete/pause ([6f2b02e](https://github.com/pdovhomilja/nextcrm-app/commit/6f2b02e1b35823c87a5a9d6a15e751bc90064c23))
* **campaigns:** require manager/admin role on schedule and send-now ([7361442](https://github.com/pdovhomilja/nextcrm-app/commit/7361442c5226030125ede66cb45ba6ea5c4a9aab))
* **campaigns:** scope campaign reads by role ([146d5b4](https://github.com/pdovhomilja/nextcrm-app/commit/146d5b4b224bd887dacb50e69b954ea7bdbb8795))
* **crm:** require account read scope on getAccountById ([edb9b9b](https://github.com/pdovhomilja/nextcrm-app/commit/edb9b9b821b10cc5271560b73caf8efaba02c59c))
* **crm:** require entity-scoped read access on activity feed ([568a7cc](https://github.com/pdovhomilja/nextcrm-app/commit/568a7cc8c56e0eb10f97442bb43ea3206978a4d6))
* **crm:** scope account list by user/manager/admin role ([a9f9a6f](https://github.com/pdovhomilja/nextcrm-app/commit/a9f9a6fa3755e561678361d91af6bae8e239fa2e))
* **crm:** scope account search by user/manager/admin role ([3fd6673](https://github.com/pdovhomilja/nextcrm-app/commit/3fd6673879f88ffff8c50dd5801d02b141cecc89))
* **crm:** scope audit-log-by-entity and normalize audit-log-admin to canonical helper ([ea45503](https://github.com/pdovhomilja/nextcrm-app/commit/ea45503d576a6fc3181f742adaff58e58b735936))
* **crm:** scope contact reads by role and linked-account/opportunity access ([be7e186](https://github.com/pdovhomilja/nextcrm-app/commit/be7e186236b2eef48b0915428cc75eca1c6f0667))
* **crm:** scope contract reads by role and linked-account access ([9b39448](https://github.com/pdovhomilja/nextcrm-app/commit/9b39448178c3d6ed241aadf60894ea1fd9479a9f))
* **crm:** scope lead reads by role and linked-account access ([b5d088b](https://github.com/pdovhomilja/nextcrm-app/commit/b5d088bbb63d69e5bc79fd62c32f37edf46eabbc))
* **crm:** scope opportunity reads by role; cache key respects user scope ([16c64fb](https://github.com/pdovhomilja/nextcrm-app/commit/16c64fbfb063ae0ea41678fa059e74357e296561))
* **crm:** scope pgvector similarity results by user/manager/admin ([a1fb3a8](https://github.com/pdovhomilja/nextcrm-app/commit/a1fb3a84a6aab9913929d61d1b5b1bc54420e276))
* **crm:** scope remaining opportunity read actions (by-account, by-contact, user-opps) ([e8bcfc9](https://github.com/pdovhomilja/nextcrm-app/commit/e8bcfc91192d6929c046d91456393c1b82f0d6b7))
* **crm:** scope target and target-list reads by role ([9e326eb](https://github.com/pdovhomilja/nextcrm-app/commit/9e326ebf35c6596af27779a3faa3b366856f9101))
* **documents:** filter bulk document operations by user scope (fail-closed) ([61132fe](https://github.com/pdovhomilja/nextcrm-app/commit/61132fee767cffbd9b4d81d9dc7b052bb969d3c0))
* **documents:** require ownership/account scope on document mutations ([5bb9035](https://github.com/pdovhomilja/nextcrm-app/commit/5bb9035052326065cab5d5c56c57d959d60fce07))
* **documents:** scope document reads by role and linked-entity access ([220cf23](https://github.com/pdovhomilja/nextcrm-app/commit/220cf231c5ddcda9905e556f92aefa4268d6015b))
* **invoices:** require account read scope on get-invoices-by-accountId ([c8cbf66](https://github.com/pdovhomilja/nextcrm-app/commit/c8cbf669e34e651eb65e9799f25491480eef52f2))
* **invoices:** require account write scope on create and on accountId reassignment ([f8282e5](https://github.com/pdovhomilja/nextcrm-app/commit/f8282e5ec64f7f469502173d1d28af34b81f7bae))
* **invoices:** require read scope on source and write scope on accountId for duplicateInvoice ([eb792a7](https://github.com/pdovhomilja/nextcrm-app/commit/eb792a76dd05dfba7bf9db855e27f6d293db5ce9))
* **migration:** scrub orphan creator FK refs before adding new FK constraint ([7fa5196](https://github.com/pdovhomilja/nextcrm-app/commit/7fa5196b04d594386ce17bd23049207a556e581e))
* **products:** require authentication on product read actions ([b2a860f](https://github.com/pdovhomilja/nextcrm-app/commit/b2a860fcbff5cd84bbd73faf574c1f3079653ce2))
* **products:** require manager/admin role on product mutations ([61ed918](https://github.com/pdovhomilja/nextcrm-app/commit/61ed918e65629661f9818ca2a4dcf6bc3f46a4cb))
* **projects:** require board write/read scope on board mutations ([522ca13](https://github.com/pdovhomilja/nextcrm-app/commit/522ca1323f45b38f5c78fdd64116d5c6c8f07206))
* **projects:** require parent board write scope on section mutations ([65e208f](https://github.com/pdovhomilja/nextcrm-app/commit/65e208fcff948eca80e3380fb599dc585f63b0e7))
* **projects:** scope project read actions by board access ([5ddaa97](https://github.com/pdovhomilja/nextcrm-app/commit/5ddaa976f853b88b526c129e0787939aa4567a9b))
* **projects:** scope task mutations (board strict + assignee soft) ([27f0cf8](https://github.com/pdovhomilja/nextcrm-app/commit/27f0cf8dfd7999599397d4f65a7f9d082900c848))
* **reports:** gate users-directory report behind manager/admin ([20aeeaf](https://github.com/pdovhomilja/nextcrm-app/commit/20aeeafec24b3d6f02ad3f69e1d0d2d68c88f4f8))
* **reports:** scope config and schedule reads/mutations by role and ownership ([932de36](https://github.com/pdovhomilja/nextcrm-app/commit/932de36cd3dd84c20fae20d49f72badd76a970e0))
* **reports:** scope dashboard tasks count and unified search by role ([d17a880](https://github.com/pdovhomilja/nextcrm-app/commit/d17a880eb6b8ac06097756d6006fcf11b44b1138))
* **reports:** scope scheduled-report data by schedule owner role ([7f7c7b6](https://github.com/pdovhomilja/nextcrm-app/commit/7f7c7b63f1cf6fd550454b3040981f1bbef13b5d))
* **security:** admin server action lockdown (Phase C) ([5a555fe](https://github.com/pdovhomilja/nextcrm-app/commit/5a555febe929bb3d477704914756737a04f3d3fd))
* **security:** authz cleanup — drop is_admin, role enum (Phase F) ([c22bf83](https://github.com/pdovhomilja/nextcrm-app/commit/c22bf837e83b10487641fcfc458629fa0fedf5d6))
* **security:** close enrichment BOLA/IDOR (Phase B1) ([726be4c](https://github.com/pdovhomilja/nextcrm-app/commit/726be4cb48c60620a15c3a3a850e8bde379a6e54))
* **security:** close GHSA-mg5f-m89f-4gmc + permission-driven authz foundation ([e6987aa](https://github.com/pdovhomilja/nextcrm-app/commit/e6987aa049dc6816a25c45436556960893c9c15d))
* **security:** close invoice IDOR (Phase B2) ([88d488b](https://github.com/pdovhomilja/nextcrm-app/commit/88d488b939057f4769d22f6ce00442738d73792b))
* **security:** scope campaigns + templates (Phase E2) ([99effa9](https://github.com/pdovhomilja/nextcrm-app/commit/99effa90d2154a930933b58bf64105fd70e0f52a))
* **security:** scope CRM account reads by role (Phase D1) ([cbc3a30](https://github.com/pdovhomilja/nextcrm-app/commit/cbc3a30a9b16ef3bd3e85ea7cc5bec234eba17f6))
* **security:** scope CRM accounts list by user authz read scope ([08c0ec7](https://github.com/pdovhomilja/nextcrm-app/commit/08c0ec7c521d44c02e7978aaf1744d9229e049df))
* **security:** scope CRM accounts list by user authz read scope ([8e86e03](https://github.com/pdovhomilja/nextcrm-app/commit/8e86e03894e4cb4b9d9c5d2265a915fd9ce775bb))
* **security:** scope CRM lead/contact/opportunity/contract reads by role (Phase D2) ([d795b00](https://github.com/pdovhomilja/nextcrm-app/commit/d795b00f6558777f3019a830069561fccb4de4f5))
* **security:** scope documents + bulk ops (Phase E3) ([12ac3df](https://github.com/pdovhomilja/nextcrm-app/commit/12ac3df7218d9512a5b6f0cf33cc750cc9ffe4d1))
* **security:** scope products + account-products + invoice list (Phase E1) ([4ecfc56](https://github.com/pdovhomilja/nextcrm-app/commit/4ecfc565c7b40c2b038f418971fc292a2c596663))
* **security:** scope projects (boards/sections/tasks) (Phase E4) ([bc2a72a](https://github.com/pdovhomilja/nextcrm-app/commit/bc2a72a23c6ae4895c7c9cdf74f45ccaeb915bf2))
* **security:** scope reports + dashboard + unified search by role (Phase B3) ([477dcf6](https://github.com/pdovhomilja/nextcrm-app/commit/477dcf6b31db740bfb3e875f972c63ba2cd19bba))
* **security:** scope targets, activities, audit log, similarity (Phase D3) ([07a03f9](https://github.com/pdovhomilja/nextcrm-app/commit/07a03f9f23b09b29994c1ccacd16fb3e520308c6))
* **tests:** merge duplicate prismadb.documents mock keys after lowercase fix ([3446bc9](https://github.com/pdovhomilja/nextcrm-app/commit/3446bc96e08d28457dee09d014297ef42370e91a))

## [0.11.1](https://github.com/pdovhomilja/nextcrm-app/compare/v0.11.0...v0.11.1) (2026-04-24)


### Bug Fixes

* **deps:** patch Dependabot advisories via pnpm overrides ([42eba8e](https://github.com/pdovhomilja/nextcrm-app/commit/42eba8e1b83cbe87b7f3a21f5d7df096f051e3d1))
* **deps:** patch Dependabot security advisories ([6002241](https://github.com/pdovhomilja/nextcrm-app/commit/60022410b56eab12abd4b10615e1602ade8c159f))
* **deps:** patch Dependabot security advisories via pnpm overrides ([22b2ecf](https://github.com/pdovhomilja/nextcrm-app/commit/22b2ecf2f09528a3219e740df36b7399ad967298))

## [0.11.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.10.3...v0.11.0) (2026-04-23)


### Features

* **crm:** show invoices on account detail page ([a207314](https://github.com/pdovhomilja/nextcrm-app/commit/a207314aded4b706b6fca9b537a603cbb55a9972))

## [0.10.3](https://github.com/pdovhomilja/nextcrm-app/compare/v0.10.2...v0.10.3) (2026-04-21)


### Bug Fixes

* **invoices:** add supplier company details, PDF regeneration, admin route guard ([31e2b29](https://github.com/pdovhomilja/nextcrm-app/commit/31e2b29c0d99d5a86429eeb5b03de38c45586cd2))
* **invoices:** supplier company details, PDF regeneration, admin route guard ([4c45b8e](https://github.com/pdovhomilja/nextcrm-app/commit/4c45b8e48ca60741c39d54ff2744a93242e1fabe))

## [0.10.2](https://github.com/pdovhomilja/nextcrm-app/compare/v0.10.1...v0.10.2) (2026-04-20)


### Bug Fixes

* **crm-settings:** allow creating industry, opportunity type, and sales stage values ([dc111f0](https://github.com/pdovhomilja/nextcrm-app/commit/dc111f03541e3724e1483e832f39dbc0411b58fd))
* **invoices:** consolidate Invoice_Currencies into shared Currency table ([43f3814](https://github.com/pdovhomilja/nextcrm-app/commit/43f3814a57973d18a7d687ee153a7b108231f68b))
* **invoices:** consolidate Invoice_Currencies into shared Currency table ([2c6820d](https://github.com/pdovhomilja/nextcrm-app/commit/2c6820d65e440906472f498b490f7c9fbdd73ea3))

## [0.10.1](https://github.com/pdovhomilja/nextcrm-app/compare/v0.10.0...v0.10.1) (2026-04-19)


### Bug Fixes

* **prisma:** add missing crm_Target_Contact migration ([7d76537](https://github.com/pdovhomilja/nextcrm-app/commit/7d76537f9ae994430fd782b6c7a789eb4dac69a8))
* **prisma:** add missing migration for crm_Target_Contact table ([792b8c3](https://github.com/pdovhomilja/nextcrm-app/commit/792b8c3ec24efeea963afdcbc71d4b2bf003bc72))

## [0.10.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.9.0...v0.10.0) (2026-04-18)


### Features

* **dashboard:** add Invoices, Campaigns, Targets cards; remove Employee card ([df13534](https://github.com/pdovhomilja/nextcrm-app/commit/df1353496e128f0f6c7035a28391e9ec8c786b76))
* **invoices:** add FKs, indexes, line-item trigger, money CHECK ([1496266](https://github.com/pdovhomilja/nextcrm-app/commit/1496266419db40292f2b0829eacafbc2c9457c4d))
* **invoices:** add numbering format template + counter consumer ([e533aeb](https://github.com/pdovhomilja/nextcrm-app/commit/e533aeb4e7bbe55c1b5a4a5e77c8a6872ef2bc6f))
* **invoices:** add PDF i18n string bundles (EN/CZ) ([02bcd7d](https://github.com/pdovhomilja/nextcrm-app/commit/02bcd7d04f3ffda004f8b2297038314ea0564dbd))
* **invoices:** add permission guards ([cb12109](https://github.com/pdovhomilja/nextcrm-app/commit/cb121093ed0f49895fa079a8158ed02ba74810ef))
* **invoices:** add Prisma schema, migration, tsvector trigger ([6b9f7f3](https://github.com/pdovhomilja/nextcrm-app/commit/6b9f7f366e8592a07d0ac534d0cc6b216762379c))
* **invoices:** add search filter builder ([a37c5fb](https://github.com/pdovhomilja/nextcrm-app/commit/a37c5fb894101a9f1d30ab91651f3ece0707d109))
* **invoices:** add totals computation with mixed VAT support ([cced002](https://github.com/pdovhomilja/nextcrm-app/commit/cced002054d70f3b6ccb26d6fca20d31bcf70584))
* **invoices:** admin pages — tax rates, series, currencies, settings ([9ed05dc](https://github.com/pdovhomilja/nextcrm-app/commit/9ed05dc5f6518784e72f697e5ef0595d04eea5b9))
* **invoices:** API routes for invoices CRUD, lifecycle, payments, search, admin config ([dcd47d0](https://github.com/pdovhomilja/nextcrm-app/commit/dcd47d09b367006c3fd467d817b7ef98969cc68c))
* **invoices:** fetch FX rates via frankfurter.app ([04c4e0e](https://github.com/pdovhomilja/nextcrm-app/commit/04c4e0e208aba5eb5ad849736357fbca4223f708))
* **invoices:** full invoicing module ([2b420ff](https://github.com/pdovhomilja/nextcrm-app/commit/2b420ff085211e321572a55e02a400662380fbc7))
* **invoices:** invoice email template ([788252b](https://github.com/pdovhomilja/nextcrm-app/commit/788252b5f3e31692f90a965f4132c1147619d8db))
* **invoices:** invoice UI — list, new, detail, edit pages ([40a09a6](https://github.com/pdovhomilja/nextcrm-app/commit/40a09a6e3e62da41d9b01bca8cbfab1bf687c4df))
* **invoices:** MinIO storage wrapper for invoice PDFs ([028d4c2](https://github.com/pdovhomilja/nextcrm-app/commit/028d4c2ed35b1cc0a945d317263cf76f82d18bc2))
* **invoices:** PDF render entry ([b9112c4](https://github.com/pdovhomilja/nextcrm-app/commit/b9112c426ad86b810d28a62a1faf723c4b7271ce))
* **invoices:** PDF template (@react-pdf/renderer) ([11109f6](https://github.com/pdovhomilja/nextcrm-app/commit/11109f62c5fdc5754446862b1beffb285a476127))
* **invoices:** seed currencies, default series, tax rates, settings ([68a8b80](https://github.com/pdovhomilja/nextcrm-app/commit/68a8b80793a5f989bd5ea031522e8e467d7459c0))
* **invoices:** server actions for invoice lifecycle ([e698e71](https://github.com/pdovhomilja/nextcrm-app/commit/e698e716141f4dcd0d48e2bea7a0bb9ec7217e7e))
* **invoices:** sidebar nav entry + i18n (EN/CZ) ([8c5f1d6](https://github.com/pdovhomilja/nextcrm-app/commit/8c5f1d609961e870b5823990695f75edbcd6a839))
* **invoices:** Zod schemas + shared types ([103b2c8](https://github.com/pdovhomilja/nextcrm-app/commit/103b2c81517ae23eed2e01f7361c0b1d8acc7273))


### Bug Fixes

* **invoices:** add PROFORMA to Zod invoice type enum ([18d6e40](https://github.com/pdovhomilja/nextcrm-app/commit/18d6e40281ab8fb726f21c6c4b99ddb92ea79ff6))
* **invoices:** fix Set type annotation in permissions for strict tsc ([1132616](https://github.com/pdovhomilja/nextcrm-app/commit/1132616272afd08368884862a2ef436bf24dfb12))
* **invoices:** hydration mismatches, decimal serialization, server action refactor ([75368f4](https://github.com/pdovhomilja/nextcrm-app/commit/75368f409bf61792ca0997492448b30ab4a3cd36))
* **invoices:** redirect to /invoices after creating new invoice ([2dd2d5e](https://github.com/pdovhomilja/nextcrm-app/commit/2dd2d5ecbee40f515a1f5d77153acffcea519600))
* **invoices:** redirect to invoice detail page after create/edit ([d58c35d](https://github.com/pdovhomilja/nextcrm-app/commit/d58c35db10e4ab03d88aec9fa0be7297d915db58))
* **invoices:** remove unused imports and prefix unused params ([b3e4ccc](https://github.com/pdovhomilja/nextcrm-app/commit/b3e4cccdabf580dedd4329afd3d2133eba38a436))
* **invoices:** remove unused React import from PDF template ([b851ece](https://github.com/pdovhomilja/nextcrm-app/commit/b851ece3b534acfbc4d628ad6fb10227679ee7c1))
* **invoices:** replace Account select with searchable combobox ([08e9b3d](https://github.com/pdovhomilja/nextcrm-app/commit/08e9b3d61f87113e6254fae2f48da15f6c2b42b5))
* **invoices:** review fixes — balanceDue, FX outside tx, permissions, search column, email template ([dde9dfa](https://github.com/pdovhomilja/nextcrm-app/commit/dde9dfaba15274c910329a71ad299585407c47f8))

## [0.9.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.8.0...v0.9.0) (2026-04-12)


### Features

* **crm:** add assign/disconnect document server actions for CRM tasks ([26f234a](https://github.com/pdovhomilja/nextcrm-app/commit/26f234a4837014b6ce8d8d3ae2f128367a7ec6c2))


### Bug Fixes

* **crm:** expand getCrMTask document select and clean up junction on delete ([b6d2f6b](https://github.com/pdovhomilja/nextcrm-app/commit/b6d2f6b4197999af116ae2165d80c7feb4cefd42))
* **crm:** remove task-specific filters from document table toolbar ([5cca3d1](https://github.com/pdovhomilja/nextcrm-app/commit/5cca3d1e4e25caef5b6b09056575495ec77c9a64))
* **crm:** switch CRM task document actions from broken axios calls to server actions ([efae73e](https://github.com/pdovhomilja/nextcrm-app/commit/efae73e56c78d80fcfa7b1358a3bf78df32e8f43))
* **crm:** uncomment assigned_to_user in task document schema and remove ts-ignore ([46c2868](https://github.com/pdovhomilja/nextcrm-app/commit/46c2868b34779d0924f578ae94dc3eb9cd303d7b))
* **crm:** wire CRM task documents to correct junction table + cleanup ([d4c503c](https://github.com/pdovhomilja/nextcrm-app/commit/d4c503c598a6905b6be826d311beb3fac2218bfa))
* **crm:** wire task comments to correct FK column (assigned_crm_account_task) ([c60ea57](https://github.com/pdovhomilja/nextcrm-app/commit/c60ea57dd2f45d800ead11466a32a5696d1c3754))
* **deps:** patch 2 Dependabot vulnerabilities ([0e2746c](https://github.com/pdovhomilja/nextcrm-app/commit/0e2746c2dd504e7e6a8c0d5e86ef9186e5b3c8f7))

## [0.8.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.7.1...v0.8.0) (2026-04-10)


### Features

* add Docker entrypoint script for auto-initialization ([1acba0a](https://github.com/pdovhomilja/nextcrm-app/commit/1acba0a5311dc99181075e61da92d59b099aff1c))
* add docker-compose.yml with all services ([c045ebb](https://github.com/pdovhomilja/nextcrm-app/commit/c045ebbfb0d07c25fa3e5c09c44b4ace7467b067))
* add multi-stage Dockerfile for NextCRM ([70a1b45](https://github.com/pdovhomilja/nextcrm-app/commit/70a1b45937af818df1a6b1c99f7d774f49af2796))
* Docker self-hosting setup with full automation ([bff363e](https://github.com/pdovhomilja/nextcrm-app/commit/bff363e646f0bfa55178922f4af05234515a0920))
* enable Next.js standalone output for Docker ([d8d1056](https://github.com/pdovhomilja/nextcrm-app/commit/d8d10565fb0fbb425f5d9bb2a41c3fe06a24cf83))


### Bug Fixes

* Docker e2e verification fixes ([e1ae699](https://github.com/pdovhomilja/nextcrm-app/commit/e1ae699cf8ce0e767bacdd3034f14bf3b4bf304b))
* **docker:** make admin email configurable via ADMIN_EMAIL ([7427b0a](https://github.com/pdovhomilja/nextcrm-app/commit/7427b0a3277b8fff83635cd1cf339eab92d442f1))
* **docker:** replace hardcoded credentials with env-driven placeholders ([255b11e](https://github.com/pdovhomilja/nextcrm-app/commit/255b11e882d4e6bdcb4172f8905bd65556ee22df))

## [0.7.1](https://github.com/pdovhomilja/nextcrm-app/compare/v0.7.0...v0.7.1) (2026-04-08)


### Bug Fixes

* merge dependabot vulnerability patches to main ([db6975a](https://github.com/pdovhomilja/nextcrm-app/commit/db6975a43a23fded9abb53bbdf6e9c45aa6c165d))
* patch 9 open dependabot vulnerabilities ([4c659fa](https://github.com/pdovhomilja/nextcrm-app/commit/4c659fa89d180933ef6ddc4df161e12e025d35a4))

## [0.7.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.6.1...v0.7.0) (2026-04-08)


### Features

* add SKILL.md download to Developer tab ([b1f528d](https://github.com/pdovhomilja/nextcrm-app/commit/b1f528d03b26ca4332f4d673c60cf51a8f303cab))
* add SKILL.md for Claude Code MCP integration ([b3a57b8](https://github.com/pdovhomilja/nextcrm-app/commit/b3a57b870403285efb883fafd1a4306db19fc5c2))

## [0.6.1](https://github.com/pdovhomilja/nextcrm-app/compare/v0.6.0...v0.6.1) (2026-04-07)


### Bug Fixes

* allow null description in opportunities table schema ([662e6bd](https://github.com/pdovhomilja/nextcrm-app/commit/662e6bd7992537a3f7c31e708f1b89d1d4399e96))
* allow null description in opportunities table schema ([8b414ac](https://github.com/pdovhomilja/nextcrm-app/commit/8b414acbe81bc327ffa7ff6a23fbc21436b817b0))

## [0.6.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.5.1...v0.6.0) (2026-04-07)


### Features

* align activity actions with deletedAt soft delete ([95de688](https://github.com/pdovhomilja/nextcrm-app/commit/95de688b97f712271e4ae771423aaadea627d104))
* align board/project actions with deletedAt soft delete ([df3fe1e](https://github.com/pdovhomilja/nextcrm-app/commit/df3fe1eb1a222cec130c1abd92918cfdbcc76c09))
* align campaign template actions with deletedAt soft delete ([a95ac24](https://github.com/pdovhomilja/nextcrm-app/commit/a95ac246e784cb3748a676126beefbd6b7e20d37))
* align crm-data and target-list actions with deletedAt soft delete ([eaa6a15](https://github.com/pdovhomilja/nextcrm-app/commit/eaa6a15ab8d76867100bb28bc84892180e583434))
* align target actions with deletedAt soft delete ([bbdad13](https://github.com/pdovhomilja/nextcrm-app/commit/bbdad13defcf45a9756cf055ea977cf156d66fab))
* MCP full parity (104 tools) + universal deletedAt soft-delete ([a164dcb](https://github.com/pdovhomilja/nextcrm-app/commit/a164dcb458a99a423a30357111c2068136973dc1))
* **mcp:** accounts delete uses deletedAt instead of status ([f565523](https://github.com/pdovhomilja/nextcrm-app/commit/f5655230775e703c0390811c0f9e7a4b77c2af25))
* **mcp:** add activities tools (5 tools, with entity links) ([7298d63](https://github.com/pdovhomilja/nextcrm-app/commit/7298d632b1ed1f87e32a911b216bbbae60f93425))
* **mcp:** add barrel export and update route handler with new error codes ([bec7bbd](https://github.com/pdovhomilja/nextcrm-app/commit/bec7bbd4a3eb832795c0485df508a1c88085cb4b))
* **mcp:** add campaigns tools (19 tools, full lifecycle + templates + steps + stats) ([7155053](https://github.com/pdovhomilja/nextcrm-app/commit/7155053f44598eb5db45b5f4460a370578ee2bf7))
* **mcp:** add contracts tools (5 tools, with line items) ([79c3013](https://github.com/pdovhomilja/nextcrm-app/commit/79c301311e0c1873941bb40d4af231aeec56e19a))
* **mcp:** add documents tools (8 tools, presigned URLs, entity linking) ([756d2be](https://github.com/pdovhomilja/nextcrm-app/commit/756d2bea8630cbd1196df6e14884139fe22fa465))
* **mcp:** add enrichment tools (4 tools, single + bulk for contacts and targets) ([2067f21](https://github.com/pdovhomilja/nextcrm-app/commit/2067f21ba57c61594cffa0ace229e3843a8bf9c4))
* **mcp:** add products tools (5 tools, org-wide catalog) ([7038bf2](https://github.com/pdovhomilja/nextcrm-app/commit/7038bf2dac23b7a12ad23cc0213f2aeb49ba56f1))
* **mcp:** add projects tools (18 tools, boards/sections/tasks/comments/watchers) ([b40f3ae](https://github.com/pdovhomilja/nextcrm-app/commit/b40f3ae572c61ad62de8b8c2ce0477535f2c6849))
* **mcp:** add reports tools (2) and email accounts tool (1) ([efe9cc7](https://github.com/pdovhomilja/nextcrm-app/commit/efe9cc719ac15ed1f3d99f8496eee9e5bb39adf4))
* **mcp:** add shared helpers for pagination, search, soft-delete, errors ([a8a0eb0](https://github.com/pdovhomilja/nextcrm-app/commit/a8a0eb0dd40375242c167c4f1a7f398286cfd683))
* **mcp:** add target lists tools (7 tools, membership management) ([4cdd748](https://github.com/pdovhomilja/nextcrm-app/commit/4cdd748582733be4f63f7382a6717cfb70a0cf62))
* **mcp:** campaigns use deletedAt instead of status for soft-delete ([0fac95e](https://github.com/pdovhomilja/nextcrm-app/commit/0fac95e803ff1bcd07a22e0af68e1da4ad76b8bd))
* **mcp:** documents use deletedAt instead of status for soft-delete ([440c629](https://github.com/pdovhomilja/nextcrm-app/commit/440c629f31a4af548640fd18ba66fc36ea9b2eb3))
* **mcp:** enable board soft-delete, add deletedAt filters to board queries ([8973d34](https://github.com/pdovhomilja/nextcrm-app/commit/8973d343ef5bc2bd7828f36b90fcf65f8cd2fabe))
* **mcp:** enable opportunities soft-delete, add deletedAt filters ([3805ab2](https://github.com/pdovhomilja/nextcrm-app/commit/3805ab298afb1f0c14848af12c503025ce472ad5))
* **mcp:** enable soft-delete for contacts, leads, targets, activities ([75217e4](https://github.com/pdovhomilja/nextcrm-app/commit/75217e431146a4a6871f17445a67c178c0e01405))
* **mcp:** rename account tools with crm_ prefix, add soft-delete, use helpers ([288204b](https://github.com/pdovhomilja/nextcrm-app/commit/288204bf7e870a7cc2b560c3994f7823ad311eb2))
* **mcp:** rename contacts/leads/opportunities/targets with crm_ prefix, add delete stubs ([24bfdcd](https://github.com/pdovhomilja/nextcrm-app/commit/24bfdcd7bbebdb164a25305438f566557995bb9e))
* **mcp:** target lists use deletedAt instead of boolean status ([1e917ed](https://github.com/pdovhomilja/nextcrm-app/commit/1e917edf1ba029648bee72cd9aa9c81aba907450))
* **mcp:** update helpers to use deletedAt-based soft delete ([41433ce](https://github.com/pdovhomilja/nextcrm-app/commit/41433ce7d26ac6b2ae6a31b7865b3da9007539db))


### Bug Fixes

* **mcp:** add explicit ReportFilters type annotation to fix date type mismatch ([68414eb](https://github.com/pdovhomilja/nextcrm-app/commit/68414eb4001ce2e0c35ea1e690db58c99960f510))
* **mcp:** fix campaign status filter collision and document unlink auth ([fc6f8a9](https://github.com/pdovhomilja/nextcrm-app/commit/fc6f8a91a24098a21b1f1a9ad454fa7c14d6c0e4))
* **mcp:** fix remaining status:true in target lists, update soft-delete report ([3037daf](https://github.com/pdovhomilja/nextcrm-app/commit/3037daf3dbc6a06360096f5934efab835a7401cb))
* **mcp:** prefix unused entity param in notFound helper ([e76305f](https://github.com/pdovhomilja/nextcrm-app/commit/e76305f4ff439c27c76f1cfedff31ae1296ef405))
* **mcp:** remove isNotDeleted from opportunities (enum type mismatch), fix unused import in products ([3792d51](https://github.com/pdovhomilja/nextcrm-app/commit/3792d515a0c05f97ea6f2c37749adcdafda8c3bc))

## [0.5.1](https://github.com/pdovhomilja/nextcrm-app/compare/v0.5.0...v0.5.1) (2026-04-06)


### Bug Fixes

* close pg pool on seed completion ([8193219](https://github.com/pdovhomilja/nextcrm-app/commit/81932196b5988495e329313b01c2f2e8a50b3ca6))

## [0.5.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.4.2...v0.5.0) (2026-04-05)


### Features

* **line-items:** add line items section to Contract detail page with copy-from-opportunity ([e3235fe](https://github.com/pdovhomilja/nextcrm-app/commit/e3235fe0f8c4c1e468ed239668dcb1d60a46a1ac))
* **line-items:** add line items section to Opportunity detail page ([24436e1](https://github.com/pdovhomilja/nextcrm-app/commit/24436e17a3d043ac1cefed2269cb6bebcf008323))
* **line-items:** add Prisma schema for Opportunity and Contract line items ([f3b1f30](https://github.com/pdovhomilja/nextcrm-app/commit/f3b1f301e464760780dea6402192e71cbfb90de8))
* **line-items:** add server actions for Contract line items with copy-from-opportunity ([baa83d1](https://github.com/pdovhomilja/nextcrm-app/commit/baa83d1b2bcc8401dd895f54c98402727ad8568b))
* **line-items:** add server actions for Opportunity line items ([680fa93](https://github.com/pdovhomilja/nextcrm-app/commit/680fa93ef4d2631b7f71d035804f954966b629a9))
* **line-items:** add shared calculation helper ([825c733](https://github.com/pdovhomilja/nextcrm-app/commit/825c7339302d995094ef595722f5c4f0718e6383))
* **line-items:** add shared LineItemsTable, AddLineItemForm, and EditLineItemForm components ([e839227](https://github.com/pdovhomilja/nextcrm-app/commit/e839227a731660b4c1bd32d9c6206f6ac03c6543))
* Products module, Line Items, and E2E test coverage ([cdb4498](https://github.com/pdovhomilja/nextcrm-app/commit/cdb4498460b2081c8609370a79e19ae7e9d4f6fc))
* **products:** add create and update product form components ([98c4e60](https://github.com/pdovhomilja/nextcrm-app/commit/98c4e60128ce5c983e48056197d6c69615d4ad56))
* **products:** add CSV bulk import server action ([3ed188a](https://github.com/pdovhomilja/nextcrm-app/commit/3ed188aee12bc9d9b98b00b1c0481a0acb569888))
* **products:** add CSV import dialog with preview and template download ([c9b7388](https://github.com/pdovhomilja/nextcrm-app/commit/c9b7388e0319c425716489a28a4a71bb1638a6dc))
* **products:** add Prisma schema for Products, ProductCategories, AccountProducts ([2c51b70](https://github.com/pdovhomilja/nextcrm-app/commit/2c51b70350dcede4e3ef2ec4e64993477916f79c))
* **products:** add product categories to CRM data fetching ([eba0ea6](https://github.com/pdovhomilja/nextcrm-app/commit/eba0ea653b3872c1288b8c1c40f83f7198e18d74))
* **products:** add product detail page with basic view, accounts tab, and history ([53d0d1f](https://github.com/pdovhomilja/nextcrm-app/commit/53d0d1f3fb6be30b08b5487e8c5996e74893dbc6))
* **products:** add products list page and view component ([9b33aa7](https://github.com/pdovhomilja/nextcrm-app/commit/9b33aa7440a4f7acb3a5eaba6d47f38b66d0a0fd))
* **products:** add server actions for Account-Product assignments ([ea3bc87](https://github.com/pdovhomilja/nextcrm-app/commit/ea3bc8746f4fa3bd3225ed47818d345a8f8e4d4c))
* **products:** add server actions for Product CRUD and data fetching ([e84ea83](https://github.com/pdovhomilja/nextcrm-app/commit/e84ea835663c59cef8021b86f3fd3afb9b64655b))
* **products:** add sidebar nav, account detail products tab with assign form ([3c1ab8b](https://github.com/pdovhomilja/nextcrm-app/commit/3c1ab8b1ceec1616362676b1cf6de7968d5aeb22))
* **products:** add table components with columns, filters, and row actions ([7fe5c4c](https://github.com/pdovhomilja/nextcrm-app/commit/7fe5c4ce5e1dfbfe196a55d2245e473952162ee4))


### Bug Fixes

* add currency field to contracts table schema ([ed6a675](https://github.com/pdovhomilja/nextcrm-app/commit/ed6a675648110d30aaf57920d9439c0f4c3f88fb))
* add line items migration and resolve migration drift ([1b6f483](https://github.com/pdovhomilja/nextcrm-app/commit/1b6f48392cf3801551ed918fd7b379aefe6b4513))
* default accounts prop to empty array in UpdateContractForm ([3e21eac](https://github.com/pdovhomilja/nextcrm-app/commit/3e21eac5fba06aed2e718964995a0b06f7f3ef50))
* guard FormSelect against undefined data and pass safe defaults ([91f1a45](https://github.com/pdovhomilja/nextcrm-app/commit/91f1a457083794e2301dda4863376acbc37e7584))
* **line-items:** resolve build and type issues ([211ab7c](https://github.com/pdovhomilja/nextcrm-app/commit/211ab7cf3cc496d08cc522c123323d9159426ecf))
* make FormSelect fully controlled to show defaultValue correctly ([0c926fc](https://github.com/pdovhomilja/nextcrm-app/commit/0c926fc80a7851d780dd62611b3f63e3596d8d3f))
* **products:** resolve audit log type errors and build issues ([784c444](https://github.com/pdovhomilja/nextcrm-app/commit/784c444267f635594402f0528be6679e3e9d37d2))
* refactor UpdateContractForm to self-fetch accounts and currencies ([23e1dab](https://github.com/pdovhomilja/nextcrm-app/commit/23e1dabcc8185deb0f93c161d08aa6347a972636))
* remove conflicting defaultValue from controlled FormDatePicker input ([326f995](https://github.com/pdovhomilja/nextcrm-app/commit/326f995857da1294a86ebb45420c9affc0d579b5))
* replace getEnabledCurrencies with proper server action ([614162d](https://github.com/pdovhomilja/nextcrm-app/commit/614162d9a2a70941cf6d338e5ad6c85243d04caf))
* serialize Decimal fields in getAllCrmData for client components ([8451299](https://github.com/pdovhomilja/nextcrm-app/commit/845129965078a0260c7cdc2a82a5a326104e38f4))
* serialize opportunity Decimal fields before passing to client component ([bed1604](https://github.com/pdovhomilja/nextcrm-app/commit/bed16042018525b18b9e2c59ace7f74568e1e574))
* stabilize flaky e2e tests across CRM modules ([dbb88b6](https://github.com/pdovhomilja/nextcrm-app/commit/dbb88b69fbe5dd013d7ea61d0da0c72036fbe3b2))

## [0.4.2](https://github.com/pdovhomilja/nextcrm-app/compare/v0.4.1...v0.4.2) (2026-04-04)


### Bug Fixes

* **security:** override defu&lt;=6.1.4 to 6.1.5 for prototype pollution CVE-2026-35209 ([507a866](https://github.com/pdovhomilja/nextcrm-app/commit/507a866326a3920e04e38afefdc60bd4140f9de7))
* **security:** patch defu prototype pollution CVE-2026-35209 ([29d187d](https://github.com/pdovhomilja/nextcrm-app/commit/29d187d2ab56fc7ec78913563864c2f7093c9c1b))

## [0.4.1](https://github.com/pdovhomilja/nextcrm-app/compare/v0.4.0...v0.4.1) (2026-04-04)


### Bug Fixes

* **build:** resolve failed migration before deploy ([d063791](https://github.com/pdovhomilja/nextcrm-app/commit/d0637914f2f296e079afd3fd280be204540c8b60))
* **migration:** rename and make idempotent for failed deploy recovery ([3393859](https://github.com/pdovhomilja/nextcrm-app/commit/339385928a7005ff36fbc6a3df64eaf678fa600b))
* **migration:** seed currencies and clean data before VARCHAR cast ([6ca3dcc](https://github.com/pdovhomilja/nextcrm-app/commit/6ca3dccf08960b8cf6c2d1e83c8a8a2632acb75a))

## [0.4.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.3.1...v0.4.0) (2026-04-04)


### Features

* add currency conversion library with unit tests ([b2eb41c](https://github.com/pdovhomilja/nextcrm-app/commit/b2eb41cdea7381c3aa513b785ef22a4410b8de90))
* add CurrencyProvider context and header CurrencySwitcher ([4851c56](https://github.com/pdovhomilja/nextcrm-app/commit/4851c562ee47116890bd414448ee2ecfa55f0b7f))
* **admin:** add currencies management page with table, rates, and ECB toggle ([6011159](https://github.com/pdovhomilja/nextcrm-app/commit/60111591311e525f2d5857f73ce40cd9e7aca231))
* **contracts:** add currency and snapshot rate to create/update actions ([1a6a4c8](https://github.com/pdovhomilja/nextcrm-app/commit/1a6a4c8010f7561985e2b865c20bae5d77e81082))
* **contracts:** add currency dropdown to create/update forms ([f0e961d](https://github.com/pdovhomilja/nextcrm-app/commit/f0e961d184c98acb39b4edb2d598e2e78ea651d7))
* **contracts:** display contract value with dynamic currency formatting ([d2c7308](https://github.com/pdovhomilja/nextcrm-app/commit/d2c7308d76ae70d6f5838bf33474d2bfb1f59b38))
* convert opportunity detail budget to display currency ([aa82933](https://github.com/pdovhomilja/nextcrm-app/commit/aa82933d27d3b5a960232c679f98fe451947786a))
* convert opportunity table budget to display currency ([030ca11](https://github.com/pdovhomilja/nextcrm-app/commit/030ca11feb1427455d33d1143b8ab1bf7cbb1e36))
* convert reports dashboard KPIs to display currency ([a564588](https://github.com/pdovhomilja/nextcrm-app/commit/a5645887b2f4ec14ee4db19a62bde43c25a85295))
* **dashboard:** display expected revenue in selected display currency ([7a2fa8f](https://github.com/pdovhomilja/nextcrm-app/commit/7a2fa8fece3fc5a10b35eabc1ebcf5b4dce2a9ff))
* **inngest:** add daily ECB exchange rate sync function ([61e0819](https://github.com/pdovhomilja/nextcrm-app/commit/61e08199f0bf783f7ebbb5230e298b8feafb0c56))
* **migration:** add currency support migration ([86b7663](https://github.com/pdovhomilja/nextcrm-app/commit/86b76636742c8bc4860de078f3731ac0e36886f9))
* multi-currency support for Sales module ([19848b0](https://github.com/pdovhomilja/nextcrm-app/commit/19848b0b050cf7f76e1694cc1a608c1f7a558eb2))
* **opportunities:** add currency dropdown to create/update forms ([49cb1b7](https://github.com/pdovhomilja/nextcrm-app/commit/49cb1b78e2595ee86651fe5ab6c0471856034d50))
* **opportunities:** add snapshot rate lookup on create/update ([f0f8380](https://github.com/pdovhomilja/nextcrm-app/commit/f0f8380a2cc72cac4ede8304a737129ec4f93313))
* **opportunities:** display budget and revenue with currency formatting ([664c096](https://github.com/pdovhomilja/nextcrm-app/commit/664c09645f9f161499e1e3486afda7b6700eeced))
* **reports:** convert sales report values to display currency ([3784f7d](https://github.com/pdovhomilja/nextcrm-app/commit/3784f7df9df29567cfe4a443f2fc9fdfefadd1d2))
* **schema:** add Currency, ExchangeRate, SystemSettings models and migrate money fields to Decimal ([bf3f16d](https://github.com/pdovhomilja/nextcrm-app/commit/bf3f16d29532af16e8cd9dae46bb2d570fa6d0fd))
* **seed:** add currency and exchange rate seed data ([3da4975](https://github.com/pdovhomilja/nextcrm-app/commit/3da4975b75029a1b7134c875e8f6656849cd73df))


### Bug Fixes

* add currency to Opportunity schema type and fix implicit any ([a7ab752](https://github.com/pdovhomilja/nextcrm-app/commit/a7ab752aa9c5879ee13600e7565852e0d251f2c6))
* add explicit types to currency map callbacks ([7d4d5a4](https://github.com/pdovhomilja/nextcrm-app/commit/7d4d5a4912b285c7f84974fd08fadef3855c3aa1))
* add explicit types to currency map callbacks in layout ([33e74f4](https://github.com/pdovhomilja/nextcrm-app/commit/33e74f44d2bf16a28a880986803e1247034e294d))
* remove any casts from serializeDecimalsList call sites ([10a5fe9](https://github.com/pdovhomilja/nextcrm-app/commit/10a5fe9e8d0530d8993d080cf5b78555840b4709))
* resolve build errors - type casts and Inngest function signature ([0e3bf0f](https://github.com/pdovhomilja/nextcrm-app/commit/0e3bf0f0ae5abed134d9319d460985c4dae7c782))
* resolve type issues in ECB sync function ([79b2663](https://github.com/pdovhomilja/nextcrm-app/commit/79b266346fada836cb16c971224bc4a9ee502b9b))
* **schema:** add [@db](https://github.com/db).VarChar(3) to crm_Opportunities.currency field ([0ef0b8b](https://github.com/pdovhomilja/nextcrm-app/commit/0ef0b8ba54251aed2900f8dc03558c315025869e))
* serialize Decimal fields before passing to client components ([ff68db2](https://github.com/pdovhomilja/nextcrm-app/commit/ff68db28f40b01111cf56ccd4b6d822f3e69cf24))
* split currency lib into client-safe and server-only modules ([1a61be3](https://github.com/pdovhomilja/nextcrm-app/commit/1a61be3b404ce10b85e50769b76dba1a8037477c))
* **tests:** update sales report tests for currency-aware aggregation ([c02d752](https://github.com/pdovhomilja/nextcrm-app/commit/c02d7524a9636eb1ea2f2e81f27cb303833db81e))
* wire currencies prop through opportunity and contract components ([dba0036](https://github.com/pdovhomilja/nextcrm-app/commit/dba0036335819f598ec430f165cad8edf55b8213))

## [0.3.1](https://github.com/pdovhomilja/nextcrm-app/compare/v0.3.0...v0.3.1) (2026-04-04)


### Bug Fixes

* **auth:** resolve Google OAuth user creation failures ([844389a](https://github.com/pdovhomilja/nextcrm-app/commit/844389a689c0f20ab8d75bdf10648beeb829c5e3))
* **auth:** resolve Google OAuth user creation failures ([094e7ee](https://github.com/pdovhomilja/nextcrm-app/commit/094e7ee715c034b7c023a574241871690cee68ad))

## [0.3.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.2.0...v0.3.0) (2026-04-04)


### Features

* **documents:** add batch actions bar for bulk delete, type change, and account linking ([7ed7cfa](https://github.com/pdovhomilja/nextcrm-app/commit/7ed7cfa0ef97bd7281605a390a7b212fc3aa1324))
* **documents:** add bulk actions, versioning, and account linking server actions ([6a8908a](https://github.com/pdovhomilja/nextcrm-app/commit/6a8908a39580f20e99e232fc03f944d381b1265f))
* **documents:** add document detail panel with summary, metadata, and version history ([9fd00f1](https://github.com/pdovhomilja/nextcrm-app/commit/9fd00f1a0785e7715aaf4e4e6c70457e7256efee))
* **documents:** add enrichment fields, chunks table, and embeddings model ([c58a1e6](https://github.com/pdovhomilja/nextcrm-app/commit/c58a1e657b23795504cdc9708682ab6e5d69178c))
* **documents:** add Inngest enrichment orchestrator with text extraction, embedding, summary, classification ([a7216cb](https://github.com/pdovhomilja/nextcrm-app/commit/a7216cbb1a0a5370096560a5a513ec0e732b1743))
* **documents:** add name/content search toggle on documents page ([8043818](https://github.com/pdovhomilja/nextcrm-app/commit/8043818bc1c2756ceb4cf7d3dd19f0fabe8de461))
* **documents:** add processing status badge component ([514fa69](https://github.com/pdovhomilja/nextcrm-app/commit/514fa6963c9c4c7946bd4f08ac4d634110f68dc2))
* **documents:** add thumbnail generator and register Inngest functions ([b0b406e](https://github.com/pdovhomilja/nextcrm-app/commit/b0b406ea4be6e75d865b0f85f1f21ccb5a693365))
* **documents:** add upload-from-account-context with auto-linking ([cb3a096](https://github.com/pdovhomilja/nextcrm-app/commit/cb3a0963573e6ca5d38e4bb2d731b639dce09ee0))
* **documents:** redesign columns with type badges, summaries, status, and filters ([9ecd298](https://github.com/pdovhomilja/nextcrm-app/commit/9ecd2984127f91fdcbe50616a5ae21afcf8eb64d))
* **documents:** replace 3 upload buttons with single bulk upload modal ([dde3a47](https://github.com/pdovhomilja/nextcrm-app/commit/dde3a477e01ded54ba52953ed80da2baa8099e4e))
* **documents:** update createDocument with Inngest event, add checkDuplicate action ([90c2bbc](https://github.com/pdovhomilja/nextcrm-app/commit/90c2bbc3021ba54eb3133a89fe6df9c9c8ecdfef))
* **documents:** update Zod schema and static filter data for enrichment fields ([4ce71b3](https://github.com/pdovhomilja/nextcrm-app/commit/4ce71b37a63ab09999ba4d7283a8d1a4850fb6bc))
* **search:** add document search to command palette ([a0a5bbe](https://github.com/pdovhomilja/nextcrm-app/commit/a0a5bbe064b358933f33fa8ad1b43c039c64659d))
* **search:** add documents to unified search with keyword + vector similarity ([299736f](https://github.com/pdovhomilja/nextcrm-app/commit/299736fd74c539b65472db021cc8cfe0f1335abd))


### Bug Fixes

* **documents:** check upload response status in bulk upload modal ([d71dbf5](https://github.com/pdovhomilja/nextcrm-app/commit/d71dbf52edb03144ba89f3b20e2dc5b4ef9deca1))
* **documents:** exclude pdf-parse and pdfjs-dist from Turbopack server bundle ([6ea7e4b](https://github.com/pdovhomilja/nextcrm-app/commit/6ea7e4bec671046ea396e29930d132dcbe10d6f0))
* **documents:** replace next/image with img tag in DocumentViewModal ([3d2dafd](https://github.com/pdovhomilja/nextcrm-app/commit/3d2dafdae168a2dccc6826d0b897a99351d0c901))
* **documents:** use pdf-parse v2 class-based API for text extraction ([2825f90](https://github.com/pdovhomilja/nextcrm-app/commit/2825f90efc4f2cf97c65901f7c1f7d9f4125db25))
* **documents:** use row.original directly instead of Zod parse in row actions ([20a6016](https://github.com/pdovhomilja/nextcrm-app/commit/20a601665e0e7b24b6a9555eeb298460c4468505))
* update @vercel/mcp-adapter to v1.0.0 and add to trusted builds ([e1583c2](https://github.com/pdovhomilja/nextcrm-app/commit/e1583c2a7d87f6fc1790f0e0432d4812308988a7))

## [0.2.0](https://github.com/pdovhomilja/nextcrm-app/compare/v0.1.0...v0.2.0) (2026-04-03)


### Features

* **footer:** read app version from package.json ([0052e17](https://github.com/pdovhomilja/nextcrm-app/commit/0052e17aadf5283299da88bc695c4b4124fa48fd))
* **footer:** read app version from package.json instead of env var ([003a728](https://github.com/pdovhomilja/nextcrm-app/commit/003a728b56429230d40058622e7d0f6fb925e150))

## [0.1.0] - 2026-04-03

This release is a major milestone — it replaces the entire authentication system, adds a full reporting module, CRM activity tracking, audit logging, soft delete, configurable CRM settings, and AI-powered contact enrichment via E2B sandboxes.

### Added

#### Authentication (better-auth)
- Replaced next-auth with better-auth (Google OAuth + Email OTP login)
- Role-based access control (RBAC) — admin / member / viewer roles
- Server-side `getSession` helper and admin plugins
- Email OTP authentication flow with magic link support
- Admin UI for role management (replaces activate/deactivate toggles)
- Idempotent role backfill migration script
- better-auth session, account, and verification tables in database

#### Reports Module
- Full reporting dashboard with KPI cards (sales, leads, accounts, activity, campaigns, users)
- Sub-pages: Sales, Leads, Accounts, Activity, Campaigns, Users
- Date range picker and filter bar
- CSV export via API route
- PDF export with Inngest-scheduled email delivery
- Save report configurations and schedule recurring reports
- shadcn/ui chart components replacing Tremor

#### CRM Activities
- Activity tracking on all 5 CRM entity detail pages (accounts, contacts, leads, opportunities, contracts)
- `ActivityForm` sheet for creating/editing activities
- `ActivitiesView` paginated feed with compound cursor pagination
- `crm_Activities` and `crm_ActivityLinks` database models

#### CRM Audit Log & Soft Delete
- Soft delete on accounts, contacts, leads, opportunities, contracts
- `crm_AuditLog` model tracking all field changes with before/after diffs
- History tab on all CRM entity detail pages
- Admin audit log page with global filterable table and restore actions

#### CRM Settings (Admin)
- Admin page with 7-tab configuration UI for CRM field values
- Configurable: Contact Types, Lead Sources, Lead Statuses, Lead Types
- CRUD dialogs for each config category
- CRM Settings link in admin sidebar

#### AI Enrichment (E2B Agent)
- E2B sandbox agent enrichment for campaign targets
- Multi-field enrichment with preset selector
- Company-name-only enrichment path (no email required)
- Bulk enrichment modal with field selector
- `crm_Target_Contact` model for multi-contact per target
- 8 new enrichment fields: personal email, LinkedIn, Twitter, phone, title, department, location, bio
- Skip-list cache (5-min TTL) to avoid re-enriching recently processed targets

#### Target Enrichment & Conversion
- Convert Target → Account/Contact flow
- Conversion tracking fields in `crm_Targets`
- Gmail quick-connect with App Password guide and folder discovery
- `TargetContactsTable` with add-contact and enrich actions

#### Contracts
- Contracts detail page with BasicView
- Contracts listed in admin audit log

### Fixed

- Auth: Critical authorization bypass patched
- Auth: Operator precedence bugs in session checks
- Auth: Redirect to sign-in after sign-out
- Auth: better-auth schema compatibility and modelName mapping for Users table
- Reports: Chart colors using `hsl()` wrapper and purple palette
- Reports: Prisma field names aligned across all report actions
- Reports: `created_on` vs `createdAt` field name in campaigns action
- CRM: `assigned_to_user` null guard in account BasicView
- CRM: UUID constraints in update forms (`z.uuid()` replacing `max(30)`)
- CRM: Operator precedence in leads name column cell
- CRM: Soft-delete columns migration made idempotent
- Campaigns: Targets import validation relaxed (last_name or company required)
- Enrichment: Company domain discovery before agent runs
- Enrichment: Personal email vs company domain routing
- Enrichment: Null upsert key guard and DB updates wrapped in `step.run`
- Inngest: `gen_random_uuid()` added to embedding INSERT statements
- Inngest: v4 API compatibility fixes
- Build: All TypeScript errors resolved (operator precedence, missing imports, type safety)

### Changed

- Login page rewritten — credentials/register flow removed, Google OAuth + Email OTP only
- All server actions migrated from next-auth to better-auth session
- All API routes migrated to better-auth session
- Admin `isAdmin`/`is_admin` checks replaced with role-based RBAC
- CRM lead/contact forms now use DB-backed FK select values
- Reports page replaced static view with live KPI dashboard
- Tremor chart library removed — replaced with shadcn/ui charts

### Security

- Critical authorization bypass fixed in auth middleware
- Password removed from invite email template
- Session token strategy updated to better-auth cookie-based auth

### Removed

- next-auth package and all type definitions
- Register page and password reset flow
- Credentials-based login
- Tremor (`@tremor/react`) dependency

---

## [0.0.3-beta] - 2024

- Initial beta releases with MongoDB → PostgreSQL migration
- Basic CRM modules: Accounts, Contacts, Leads, Opportunities
- Campaign management with target lists
- AI document processing (OCR, PDF, DOCX)
- Vector embeddings with pgvector

[0.1.0]: https://github.com/pdovhomilja/nextcrm-app/compare/v0.0.3-beta...v0.1.0
[0.0.3-beta]: https://github.com/pdovhomilja/nextcrm-app/releases/tag/v0.0.3-beta

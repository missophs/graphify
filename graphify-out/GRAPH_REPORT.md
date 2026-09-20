# Graph Report - graphify  (2026-09-20)

## Corpus Check
- 717 files · ~1,254,977 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 13155 nodes · 26610 edges · 740 communities (647 shown, 70 thin omitted)
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 1094 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `2f194859`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- test_extract.py
- test_analyze.py
- test_languages.py
- cli.py
- engine.py
- extract.py
- _make_id
- build_from_json
- graphify/__main__.py
- test_multilang.py
- test_devin.py
- detect.py
- test_detect.py
- test_dedup.py
- test_export.py
- test_js_import_resolution.py
- export.py
- test_install.py
- classify_file
- extract_bash
- extract_js
- test_dotnet.py
- _edge_labels
- expand_oversized_files
- test_cache.py
- test_watch.py
- extract
- test_llm_backends.py
- test_cli_export.py
- test_import_extension_resolution.py
- test_ruby_resolution.py
- test_pdf_token_estimate.py
- _call_claude_cli
- patch
- test_pascal.py
- test_image_vision.py
- test_serve.py
- test_csharp_member_calls.py
- test_security.py
- test_codebuddy.py
- test_multigraph_diagnostics.py
- cache.py
- Communities (141 total, 52 thin omitted)
- Path
- _labels
- to_obsidian
- test_benchmark.py
- _parse_llm_json
- save_semantic_cache
- extract_python
- extract_commonlisp
- _make_graph
- test_skillgen.py
- _looks_like_context_exceeded
- test_reflect.py
- validate_extraction
- gen.py
- graphify exports reference (kiro)
- test_global_graph.py
- extract_cpp
- load_platforms
- test_ollama.py
- test_indirect_dispatch.py
- save_cached
- dedup.py
- test_community_labels_skill.py
- install
- test_serve_http.py
- extract_objc
- to_wiki
- reflect.py
- serve.py
- Communities
- normalize_id
- claude_install
- ingest_scip_json
- graphify-out/ output directory (shared pipeline state)
- test_cluster.py
- extract_markdown
- test_transcribe.py
- README.ja-JP.md
- _relations
- test_query_induced_edges.py
- test_install_references.py
- CsharpNameResolver
- test_mcp_ingest.py
- security.py
- test_scip_ingest.py
- test_stat_index_portability.py
- test_affected_cli.py
- attach_hyperedges
- hooks.py
- ingest.py
- test_querylog.py
- _score_nodes
- HttpClient
- test_no_dedup_flag.py
- callflow_html.py
- test_obsidian_vault_migration.py
- prs.py
- _query_terms
- test_explain_cli.py
- test_hooks.py
- parametrize
- test_minhash.py
- build_merge
- skipif
- render_all
- test_unverified_semantic_shrink.py
- extract_dm
- run_language_resolvers
- _query_graph_text
- test_indirect_call_function_expression_shadow.py
- graphify Whisper video/audio transcription
- write_callflow_html
- test_go_qualified_resolution.py
- test_install_roundtrip.py
- test_path_cli.py
- storage.py
- test_csharp_interface_dispatch.py
- extract_vue
- test_labeling.py
- test_prs.py
- test_hook_guard.py
- test_read_hook.py
- _make_symbol_doc
- test_swift_cross_file_calls.py
- sample.swift
- test_callflow_html.py
- _parse_apm_fallback
- scip_ingest.py
- DataProcessor
- introspect_cargo
- test_dedup_remaps_hyperedges.py
- test_ignore_file_encoding.py
- resolve_bash_source_edges
- build_tree
- _fixture
- test_extract_code_only_cli.py
- _corpus
- e
- _semantic_id_remap
- google_workspace.py
- test_symbol_resolution.py
- test_incremental.py
- test_jsconfig_baseurl.py
- multigraph_compat.py
- _shrink_payload
- _clear_backend_keys
- _make_corpus
- test_js_dynamic_imports.py
- test_kotlin_grammar.py
- test_prune_sweeps_orphans.py
- graphify github-and-merge reference (kiro)
- test_hook_out_of_project_paths.py
- test_atomic_writes.py
- test_semantic_cleanup.py
- _rewire_unique_stub_nodes
- test_js_dynamic_import_affected.py
- _write_raw_doc
- test_search_hook.py
- generate_section_flowchart
- test_manifest_ingest.py
- _pick_seeds
- edge_data
- Path
- build
- test_python_decorators.py
- graphify query "<question>" (CLI) / query_graph (MCP)
- Graphify Skill Spec (Claude Code)
- generate_section_cards
- _collision_rank
- extract_ocaml
- save_query_result
- test_evidence_binding.py
- test_csharp_partial_classes.py
- _two_community_graph
- test_settings_merge.py
- convert_office_file
- sanitize_semantic_fragment
- test_query_names_its_graph.py
- typescript_advanced.ts
- test_cpp_objc_cross_file_calls.py
- test_go_builtin_call_targets.py
- test_incomplete_build_guard.py
- test_install_upgrade.py
- test_java_type_resolution.py
- _run
- sample.php
- Reference: Extraction Spec (subagent prompt)
- test_carried_hyperedge_remap.py
- test_inherited_field_receivers.py
- extract_dart
- _hooks_dir
- test_paths.py
- test_cross_extension_reexport_self_cycle.py
- test_csharp_object_creation.py
- test_extract_cli.py
- _claude_artifacts
- test_ts_inheritance.py
- test_watch_manifest_location.py
- UserControl
- PRInfo
- Graph
- sample.kt
- TestSubprocessEncoding
- test_indirect_call_external_import_shadow.py
- test_semantic_cache_out_root.py
- test_ts_decorators.py
- Window
- cluster.py
- extract_terraform
- _platform_skill_destination
- _detect_default_branch
- test_wiki_link_filename_parity.py
- main
- test_java_member_calls.py
- test_merge_graphs_cli.py
- test_typescript_enum_members.py
- Window
- string
- test_falkordb_integration.py
- file_hash
- _stale_graph_sources
- _is_regular_file
- _make_scip_node_id
- test_indirect_call_nested_closure_shadow.py
- test_inferred_confidence_rubric.py
- test_objc_category_interfaces.py
- test_objc_property_ivar_receivers.py
- test_agents_platform.py
- test_type_only_import_cycles.py
- test_uninstall_scope.py
- Platform
- sample.json
- AccountService
- _extract_sql_or_skip
- test_objc_field_table_remap.py
- _resolve_js_import_target
- exceptions.py
- TDataProcessor
- Path
- test_cross_repo_shared_types.py
- test_csharp_call_site_generic_args.py
- test_csharp_enum_members.py
- test_csharp_field_generic_args.py
- Specific Issues Found
- test_merge_chunks_validation.py
- README.md
- clear_cache
- README.he-IL.md
- wiki.py
- sample.sv
- test_csharp_member_nodes.py
- test_extract_cache_location.py
- _run_extract
- test_hollow_chunks_arm_shrink_guard.py
- test_indirect_call_arrow_single_param_shadow.py
- test_indirect_call_catch_binding_shadow.py
- _vault_extract
- test_node_id_canonical.py
- test_ts_namespace.py
- test_ts_receiver_member_calls.py
- README.fa-IR.md
- Geometry
- sample.razor
- geometry
- sample.go
- affected_nodes
- mcp_ingest.py
- DataProcessor
- Animal
- sample.dmf
- ScopedCallsUnit
- test_extraction_spec_ids.py
- test_objc_member_calls.py
- test_query_cli.py
- test_src_layout_import_resolution.py
- Always-On graphify Rules for AGENTS.md (Expected Output)
- graphify hook (git post-commit hook)
- test_injection_sentinel_coverage.py
- README.uk-UA.md
- _communities_from_graph
- barrel_reexport.ts
- test_architecture_doc.py
- extract_json
- _inferred_uses
- test_indirect_dispatch_getattr.py
- test_install_strings.py
- test_js_callback_calls.py
- test_scala_self_type.py
- test_ts_generators.py
- test_ts_import_type_arguments.py
- test_typescript_module_extensions.py
- Graphify Exports & Benchmark Reference (claude)
- manifest.json
- Demo.ViewModels
- /graphify add <url> Command
- _bash_invokes_search
- compute_pr_impact
- parse_memory_doc
- TMainForm
- test_cjs_module_extension.py
- test_indirect_dispatch_assign_return.py
- test_kotlin_object_literal.py
- test_partial_extraction_warning.py
- test_pascal_call_scoping.py
- test_php_object_creation.py
- test_php_type_resolution.py
- test_wheel_packaging.py
- _inline_links
- utils.py
- extract_csharp
- compilerOptions
- extract_fortran
- test_indirect_call_for_of_binding_shadow.py
- test_phantom_cross_package_call.py
- test_python_import_resolution.py
- monolith_roundtrip
- render_always_on
- test_ts_parse_warning.py
- Extra Exports and Benchmark Reference (Agents Skill, Expected)
- sample.csproj
- graphify clone Command
- extract_robot
- gemini_install
- _parse_ci
- _shortest_path_text
- conftest.py
- dynamic_import.ts
- Widget
- TBaseGadget
- sample.scala
- sample_calls.py
- test_cross_language_call_resolution.py
- test_god_nodes_cli.py
- test_import_self_loops.py
- _many_communities
- generate
- test_swift_computed_properties.py
- test_ts_new_expression_calls.py
- Shell: PowerShell Interpreter Detection
- saxpy
- semantic_cleanup.py
- first_present
- format_node_refs
- safe_file_path
- llm.py
- extract_go
- lessons_fresh
- load_memory_docs
- load_validated_semantic_fragment
- Whisper-based Transcription (transcribe_all)
- gen_demo_path.py
- sample.zig
- sample.rb
- test_antigravity_install.py
- test_case_sensitive_resolution.py
- test_gemini_hook.py
- test_phantom_external_import.py
- test_swift_builtin_noise.py
- test_swift_import_resolution.py
- Graphify GitHub Clone & Cross-Repo Merge Reference (claude)
- build_community_labels
- Foo
- sample_php_listen.php
- test_cpp_preprocess.py
- test_crossfile_identical_labels_stay_distinct_for_guarded_types
- test_home_sandbox.py
- extract_rust
- BENCHMARKS.md
- _match_anchored_ignore_pattern
- _get_extractor
- Cookies
- sample.c
- Attention Is All You Need
- sample.sh
- TSampleForm
- sample_php_container.php
- SampleSpec
- test_cli_broken_pipe.py
- extract_powershell_manifest
- Graphify Commit Hook & CLAUDE.md Integration Reference (claude)
- Graphify Add-URL & Watch Reference (claw)
- graphify post-commit hook
- graphify --watch folder watcher
- graphify post-commit hook
- graphify --watch folder watcher
- graphify post-commit hook
- graphify --watch folder watcher
- graphify post-commit hook
- graphify --watch folder watcher
- graphify post-commit hook
- GitHub Clone and Cross-Repo Merge Reference (Windows Skill)
- Add URL and Watch Folder Reference (Agents Skill, Expected)
- Transcribe Video/Audio Reference (Windows Skill)
- SamplePackage
- CI workflow
- test_provider_registry.py
- pascal_resolution.py
- test_semantic_similarity.py
- QuranicWords Deploy Guide (Test Fixture)
- TOtherGadget
- sample_doctest.cpp
- MyApp.Accounts.User
- sample.luau
- RateLimiter
- ColorResolver
- sample.sln
- UserControl
- MainViewModel
- Graphify Transcribe Reference (claude)
- Dispatch fragment: parallel Agent tool dispatch (PowerShell paths)
- generate_header
- Graphify Evaluation - Mixed Corpus (2026-04-04)
- test_file_label_disambiguation.py
- graphify/extractors/ package
- _community_label_lines
- test_pipeline.py
- copilot skill: exports reference doc
- copilot skill: github-and-merge reference doc
- droid skill: exports reference doc
- droid skill: github-and-merge reference doc
- kilo skill: exports reference doc
- kilo skill: github-and-merge reference doc
- kiro skill: exports reference doc
- kiro skill: github-and-merge reference doc
- shapes
- cjs_require.js
- a/Logger.cpp
- b/Logger.cpp
- Server
- App
- sample.ts
- Transformer
- test_cli_help.py
- Communities
- App.csproj
- graphify/__init__.py
- CLAUDE.md native graphify integration
- codex skill: transcribe reference doc
- /graphify add <url> ingestion (ingest())
- CLAUDE.md native graphify integration
- copilot skill: transcribe reference doc
- /graphify add <url> ingestion (ingest())
- CLAUDE.md native graphify integration
- droid skill: transcribe reference doc
- /graphify add <url> ingestion (ingest())
- CLAUDE.md native graphify integration
- kilo skill: transcribe reference doc
- /graphify add <url> ingestion (ingest())
- CLAUDE.md native graphify integration
- kiro skill: transcribe reference doc
- test_zig_enum_and_union_methods_are_extracted
- Dup
- Dup
- AccountTrigger
- sample.dmi
- Foo
- Foo
- Benchmark: Karpathy Repos + Research Papers
- test_ingest_non_dict_input_returns_empty
- graphify.serve MCP server
- Publish to PyPI workflow
- no_tokenizer
- graphify
- test_label_cli_drops_sentinel_and_bare_key_echoes
- test_ingest_symbol_trailing_hash_no_display_name_has_non_empty_label
- test_relationship_target_unknown_emits_stub_node
- test_non_string_relative_path_falls_back_to_default
- test_non_string_language_falls_back
- test_documents_field_non_list_returns_empty
- test_occurrence_negative_line_falls_back_to_zero
- test_unique_cross_document_symbol_still_resolves
- test_relationship_truthy_string_flag_is_ignored
- test_relationship_int_flag_is_ignored
- test_relationship_boolean_true_routes_correctly
- test_ingest_multiple_symbols_in_one_document
- test_ingest_multiple_documents
- test_ingest_documents_empty_list
- test_ingest_edge_source_location_from_first_occurrence
- test_ingest_single_symbol_no_relationships
- test_ingest_duplicate_symbols_in_same_file_are_deduplicated
- test_ingest_document_item_not_a_dict_is_skipped
- test_ingest_symbol_without_symbol_id_is_skipped
- test_ingest_document_without_symbols_key
- test_ingest_symbol_without_kind_defaults_to_unknown
- test_ingest_document_relative_path_overrides_source_file_param
- test_ingest_symbol_with_short_range_uses_first_element_as_line
- test_ingest_symbol_with_documentation_becomes_description
- test_ingest_symbol_with_empty_documentation_skips_description
- test_ingest_edge_with_zero_sourceline_has_empty_location
- test_community_article_truncation_notice
- test_to_wiki_god_node_label_case_collides_with_community
- Query Stub: Default
- TButton
- x
- y
- z
- Int
- Reference: Add URL & Watch Folder
- Reference: GitHub Clone & Cross-Repo Merge
- Response
- Graph Report - worked/mixed-corpus/raw  (2026-04-05)
- prompt_fingerprint
- Case Study: rsl-siege-manager (Python + TypeScript monorepo)
- README.de-DE.md
- README.es-ES.md
- README.fr-FR.md
- graphify
- README.pt-BR.md
- README.ru-RU.md
- README.uz-UZ.md
- README.ar-SA.md
- graphify
- NetworkError
- README.hi-IN.md
- verilog.py
- Graph Report - .  (2026-05-13)
- Review: rsl-siege-manager
- _write_two_tier_graph
- _labels
- Graph Report - /home/safi/graphify-benchmark  (2026-04-04)
- Corpus (52 files)
- README.da-DK.md
- README.fil-PH.md
- README.hu-HU.md
- README.it-IT.md
- README.no-NO.md
- README.pl-PL.md
- README.ro-RO.md
- README.sv-SE.md
- README.th-TH.md
- README.zh-TW.md
- _path_match
- test_hyperedge_member_shapes.py
- Research Notes
- Headers
- _coerce_hyperedge_member_refs
- Document Pipeline Architecture
- Reproducible Example
- CookieConflict
- httpx Corpus Benchmark
- Mixed Corpus Benchmark
- _default_model_for_backend
- _ApiKeyMiddleware
- _call_pairs
- test_mask_sql_comments_monotone_against_frozen_baseline
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\env.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0002_add_preview_columns.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0003_make_siege_date_nullable.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0004_add_post_priority_config.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0005_add_description_to_post_priority_config.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0006_power_level_and_drop_sort_value.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0007_fix_group_number_max.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0008_add_matched_condition_id_to_position.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0009_add_discord_id_to_member.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0010_add_last_seen_changelog_at_to_member.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0011_add_post_suggest_preview.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\attack_day.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\auth.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\autofill.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\board.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\buildings.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\changelog.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\comparison.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\discord_sync.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\health.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\images.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\lifecycle.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\members.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\notifications.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\post_priority_config.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\post_suggestions.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\posts.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\reference.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\siege_members.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\sieges.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\validation.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\version.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\config.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\db\\base.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\db\\__init__.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\db\\seeds.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\db\\session.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\dependencies\\auth.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\dependencies\\__init__.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\__init__.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\main.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\middleware.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\building_group.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\building.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\building_type_config.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\enums.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\__init__.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\member_post_preference.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\member.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\notification_batch.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\notification_batch_result.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\position.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\post_active_condition.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\post_condition.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\post_priority_config.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\post.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\siege_member.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\siege.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\rate_limit.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\attack_day.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\autofill.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\board.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\building.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\changelog.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\common.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\comparison.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\__init__.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\member.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\post_condition.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\post.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\post_suggestions.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\siege_member.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\siege.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\validation.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\version.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\attack_day.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\autofill.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\board.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\bot_client.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\building_capacity.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\buildings.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\comparison.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\discord_sync.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\image_gen.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\lifecycle.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\members.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\notification_message.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\post_suggestions.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\posts.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\reference.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\siege_members.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\sieges.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\validation.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\telemetry.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\scripts\\seed_demo.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\scripts\\seed.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\conftest.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\__init__.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_attack_day.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_auth.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_auth_rate_limit.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_autofill.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_board.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_bot_client.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_buildings.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_changelog.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_comparison.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_config_endpoint.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_config.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_cors.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_discord_sync.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_enums.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_health.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_image_gen.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_lifecycle_integration.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_lifecycle.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_member_changelog_column.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_members.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_notification_message.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_notifications.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_post_suggestions_integration.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_post_suggestions.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_posts.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_reference.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_schema.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_seed_canonical.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_seed_demo.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_sieges.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_telemetry.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_validation.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_version.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\config.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\discord_client.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\http_api.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\__init__.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\telemetry.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\conftest.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\__init__.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\test_discord_client.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\test_get_guild_member.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\test_http_api.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\test_telemetry.py
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\e2e\\board.spec.ts
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\e2e\\siege-lifecycle.spec.ts
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\e2e\\smoke.spec.ts
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\eslint.config.js
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\playwright.config.ts
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\postcss.config.js
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\board.ts
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\changelog.ts
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\client.ts
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\config.ts
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\members.ts
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\notifications.ts
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\App.tsx
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\main.tsx
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\vite-env.d.ts
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\tailwind.config.ts
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\vite.config.ts
- I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\vitest.config.ts
- CLAUDE.md
- _doc_community
- test_sql_cte_never_binds_to_cross_language_symbol
- test_sql_tsql_proc_shorthand_is_recovered
- test_sql_commented_ddl_is_not_fabricated_by_error_recovery
- test_sql_comment_openers_inside_string_literals_do_not_hide_ddl
- test_mask_sql_comments_literal_and_comment_handling
- test_mask_sql_comments_invariants_fuzz
- test_sql_ddl_keywords_inside_delimited_identifiers_do_not_fabricate

## God Nodes (most connected - your core abstractions)
1. `extract()` - 551 edges
2. `build_from_json()` - 210 edges
3. `_rebuild_code()` - 163 edges
4. `_make_id()` - 127 edges
5. `detect()` - 126 edges
6. `_read_text()` - 123 edges
7. `dispatch_command()` - 120 edges
8. `_file_stem()` - 113 edges
9. `_labels()` - 99 edges
10. `main()` - 97 edges

## Surprising Connections (you probably didn't know these)
- `graphify hook (git post-commit hook)` --semantically_similar_to--> `--watch folder watcher`  [INFERRED] [semantically similar]
  graphify/skills/opencode/references/hooks.md → tools/skillgen/expected/graphify__skills__trae__references__add-watch.md
- `test_dmi_no_error()` --calls--> `extract_dmi()`  [INFERRED]
  tests/test_languages.py → graphify/extractors/dm.py
- `test_dmi_state_contained_by_file()` --calls--> `extract_dmi()`  [INFERRED]
  tests/test_languages.py → graphify/extractors/dm.py
- `test_dmf_elem_under_window()` --calls--> `extract_dmf()`  [INFERRED]
  tests/test_languages.py → graphify/extractors/dm.py
- `test_dmf_no_dangling_edges()` --calls--> `extract_dmf()`  [INFERRED]
  tests/test_languages.py → graphify/extractors/dm.py

## Import Cycles
- 1-file cycle: `tests/fixtures/sample.sv -> tests/fixtures/sample.sv`

## Hyperedges (group relationships)
- **graphify cross-repo / monorepo graph workflow (clone, per-subfolder extract, merge-graphs)** — tools_skillgen_expected_graphify__skills__kiro__references__github_and_merge_clone_github_repo, tools_skillgen_expected_graphify__skills__kiro__references__github_and_merge_merge_graphs, tools_skillgen_expected_graphify__skills__kiro__references__github_and_merge_extract_per_subfolder [EXTRACTED 0.90]
- **graphify optional export pipeline flags (wiki/neo4j/falkordb/svg/graphml/mcp/benchmark)** — tools_skillgen_expected_graphify__skills__kilo__references__exports_wiki_export, tools_skillgen_expected_graphify__skills__kilo__references__exports_neo4j_export, tools_skillgen_expected_graphify__skills__kilo__references__exports_falkordb_export, tools_skillgen_expected_graphify__skills__kilo__references__exports_svg_export, tools_skillgen_expected_graphify__skills__kilo__references__exports_graphml_export, tools_skillgen_expected_graphify__skills__kilo__references__exports_mcp_server_export, tools_skillgen_expected_graphify__skills__kilo__references__exports_token_reduction_benchmark [EXTRACTED 0.90]
- **Cross-Repo and Monorepo Graph Merging Workflow** — tools_skillgen_expected_graphify__skills__claude__references__github_and_merge_github_clone, tools_skillgen_expected_graphify__skills__claude__references__github_and_merge_cross_repo_merge, tools_skillgen_expected_graphify__skills__claude__references__github_and_merge_monorepo_subfolder_merge [EXTRACTED 1.00]
- **manifest.json portability documented across changelog, README, and skill runbook** — changelog_manifest_portability, readme_manifest_portable, graphify_skill_agents_manifest_stamping [EXTRACTED 1.00]
- **Prompt-fingerprinted semantic cache across the changelog fix, cache module, and skill flow** — changelog_semantic_cache, graphify_skill_agents_cache_fingerprint, graphify_cache [EXTRACTED 1.00]
- **Shrink guard: feature, fixes, and skill-runbook write ordering** — changelog_shrink_guard, graphify_skill_agents_shrink_guard_check, graphify_skill_aider [EXTRACTED 1.00]
- **Always-On Graphify Automation Mechanisms** — tools_skillgen_expected_graphify__skills__claude__references__hooks_post_commit_hook, tools_skillgen_expected_graphify__skills__claude__references__hooks_claude_md_integration, tools_skillgen_expected_graphify__skills__claw__references__add_watch_graphify_watch [INFERRED 0.75]
- **Post-commit hook reference duplicated across CLI tool skills** — graphify_skills_copilot_references_hooks_committhook, graphify_skills_droid_references_hooks_committhook, graphify_skills_kilo_references_hooks_committhook, graphify_skills_kiro_references_hooks_committhook, graphify_skills_codex_references_hooks_committhook [INFERRED 0.75]
- **graphify-out/ as shared pipeline state across hook, watch, and ingestion flows** — graphify_out_directory, post_commit_hook, watch_mode, url_ingestion [INFERRED 0.75]
- **merge-graphs reference duplicated across CLI tool skills** — graphify_skills_copilot_references_github_and_merge_mergegraphs, graphify_skills_droid_references_github_and_merge_mergegraphs, graphify_skills_kilo_references_github_and_merge_mergegraphs, graphify_skills_kiro_references_github_and_merge_mergegraphs [INFERRED 0.75]
- **Per-agent native memory-file integration variants (AGENTS.md / CLAUDE.md)** — agents_md_integration_generic, agents_md_integration_amp, claude_md_integration [INFERRED 0.75]
- **Whisper transcription reference duplicated across CLI tool skills** — graphify_skills_copilot_references_transcribe_whispertranscription, graphify_skills_droid_references_transcribe_whispertranscription, graphify_skills_kilo_references_transcribe_whispertranscription, graphify_skills_kiro_references_transcribe_whispertranscription, graphify_skills_codex_references_transcribe_whispertranscription [INFERRED 0.75]
- **Automatic Graph Freshness Mechanisms** — graphify_watch_command, graphify_hook_command, graphify_claude_md_integration [INFERRED 0.80]
- **Graphify Export Flag Pipeline (Neo4j / FalkorDB / MCP Server)** — tools_skillgen_expected_graphify__skills__claude__references__exports_neo4j_export, tools_skillgen_expected_graphify__skills__claude__references__exports_falkordb_export, tools_skillgen_expected_graphify__skills__claude__references__exports_mcp_server_export [INFERRED 0.80]
- **Post-Commit Hook + Host File Integration** — tools_skillgen_fragments_references_host_hooks_agents_md, tools_skillgen_fragments_references_shared_hooks, concept_graphify_hook [INFERRED 0.80]
- **Python Interpreter Detection & Caching** — tools_skillgen_fragments_shell_posix, tools_skillgen_fragments_shell_powershell, tools_skillgen_fragments_shell_interpreter_guard_posix, tools_skillgen_fragments_shell_interpreter_guard_powershell [INFERRED 0.80]
- **Always-On graphify Awareness Templates Across AI Platforms** — tools_skillgen_expected_graphify__always_on__agents_md, tools_skillgen_expected_graphify__always_on__antigravity_rules, tools_skillgen_expected_graphify__always_on__claude_md, tools_skillgen_expected_graphify__always_on__gemini_md, tools_skillgen_expected_graphify__always_on__kiro_steering, tools_skillgen_expected_graphify__always_on__vscode_instructions [INFERRED 0.85]
- **Host-Specific Subagent Dispatch Pattern** — tools_skillgen_fragments_dispatch_agent_tool_disk, tools_skillgen_fragments_dispatch_codex_agenttask, tools_skillgen_fragments_dispatch_manual_paste, tools_skillgen_fragments_dispatch_opencode_mention, tools_skillgen_fragments_dispatch_task_tool_disk_trae, tools_skillgen_fragments_dispatch_task_tool_disk [INFERRED 0.85]
- **Standing routing-instruction injection across hosts** — graphify_always_on_agents_md_injection, graphify_always_on_antigravity_rules_injection, graphify_always_on_claude_md_injection, graphify_always_on_gemini_md_injection, graphify_always_on_kiro_steering_injection, graphify_always_on_vscode_instructions_injection [INFERRED 0.85]
- **Cross-platform skill distribution** — graphify_skill_core_spec, graphify_skill_amp_adapter, graphify_skill_claw_adapter, graphify_skill_codex_adapter, graphify_skill_copilot_adapter, graphify_skill_devin_adapter, graphify_skill_droid_adapter, graphify_skill_kilo_adapter, graphify_skill_kiro_adapter, graphify_skill_opencode_adapter, graphify_skill_pi_adapter, graphify_skill_trae_adapter, graphify_skill_vscode_adapter, graphify_skill_windows_adapter [INFERRED 0.85]
- **Export flag pipeline (Steps 6b-8)** — wiki_export, neo4j_export, falkordb_export, svg_export, graphml_export, mcp_server_export, token_reduction_benchmark [INFERRED 0.85]
- **Post-Commit Hook + Native Platform Integration Pattern** — graphify_skills_windows_references_hooks, tools_skillgen_expected_graphify__skills__agents__references__hooks, tools_skillgen_expected_graphify__skills__amp__references__hooks, concept_graphify_hook, concept_graphify_claude_install, concept_graphify_agents_install, concept_graphify_amp_install [INFERRED 0.85]
- **graphify hooks reference duplicated identically across agent tool targets (droid/kilo/kiro/opencode/pi)** — tools_skillgen_expected_graphify__skills__droid__references__hooks, tools_skillgen_expected_graphify__skills__kilo__references__hooks, tools_skillgen_expected_graphify__skills__kiro__references__hooks, tools_skillgen_expected_graphify__skills__opencode__references__hooks, tools_skillgen_expected_graphify__skills__pi__references__hooks [INFERRED 0.85]
- **Trae/VS Code/Windows add-watch reference docs (same feature, three IDE targets)** — tools_skillgen_expected_graphify__skills__trae__references__add_watch, tools_skillgen_expected_graphify__skills__vscode__references__add_watch, tools_skillgen_expected_graphify__skills__windows__references__add_watch [INFERRED 0.90]
- **Trae/VS Code/Windows exports-and-benchmark reference docs (same feature set, three IDE targets)** — tools_skillgen_expected_graphify__skills__trae__references__exports, tools_skillgen_expected_graphify__skills__vscode__references__exports, tools_skillgen_expected_graphify__skills__windows__references__exports [INFERRED 0.90]
- **Trae/VS Code/Windows transcribe reference docs (same Whisper pipeline, three IDE targets)** — tools_skillgen_expected_graphify__skills__trae__references__transcribe, tools_skillgen_expected_graphify__skills__vscode__references__transcribe, tools_skillgen_expected_graphify__skills__windows__references__transcribe [INFERRED 0.90]
- **GitHub Clone/Merge Reference Duplicated Across Skill Variants** — graphify_skills_windows_references_github_and_merge, tools_skillgen_expected_graphify__skills__agents__references__github_and_merge, tools_skillgen_expected_graphify__skills__amp__references__github_and_merge [INFERRED 0.90]
- **Add-Watch Feature Documented Across Tool Variants** — graphify_skills_opencode_references_add_watch, graphify_skills_pi_references_add_watch, graphify_skills_trae_references_add_watch, graphify_skills_vscode_references_add_watch, graphify_skills_windows_references_add_watch [INFERRED 0.90]
- **Export & Benchmark Feature Documented Across Tool Variants** — graphify_skills_opencode_references_exports, graphify_skills_pi_references_exports, graphify_skills_trae_references_exports, graphify_skills_vscode_references_exports, graphify_skills_windows_references_exports [INFERRED 0.90]

## Communities (740 total, 70 thin omitted)

### Community 0 - "test_extract.py"
Cohesion: 0.01
Nodes (179): collect_files(), #2339 as reported: collect_files returned [] for a real coverage package, both…, test_collect_files_keeps_coverage_code_namespace(), _legacy_collect_files(), Two different files' same-named, otherwise-undefined base class must not…, #2653: function declarations nested inside another function emit nodes, source…, #2653: arbitrary depth nested named function declarations establish…, #2653 (the motivating React idiom): a named function declared inside an ARROW-… (+171 more)

### Community 1 - "test_analyze.py"
Cohesion: 0.03
Nodes (98): _cross_community_surprises(), _cross_file_surprises(), _cross_language(), _file_category(), find_import_cycles(), graph_diff(), _is_concept_node(), _is_json_key_node() (+90 more)

### Community 2 - "test_languages.py"
Cohesion: 0.03
Nodes (118): extract_c(), extract_swift(), Extract functions and includes from a .c/.h file., Extract classes, structs, protocols, functions, imports, and calls from a…, extract_elixir(), Path, Extract modules, functions, imports, and calls from a .ex/.exs file., extract_julia() (+110 more)

### Community 3 - "cli.py"
Cohesion: 0.02
Nodes (192): god_nodes(), Return the top_n most-connected real entities - the core abstractions. File-…, Find connections that are genuinely surprising - not obvious from file…, Generate questions the graph is uniquely positioned to answer. Based on:…, suggest_questions(), surprising_connections(), _abs_identity(), _build_prune_sets() (+184 more)

### Community 4 - "engine.py"
Cohesion: 0.02
Nodes (148): extract_lua(), Extract functions, methods, require() imports, and calls from a .lua file., _c_collect_type_refs(), _cpp_collect_type_refs(), _cpp_declarator_name(), _cpp_local_var_types(), _csharp_classify_base(), _csharp_extra_walk() (+140 more)

### Community 5 - "extract.py"
Cohesion: 0.04
Nodes (137): _augment_js_reexport_edges(), _get_c_func_name(), _import_c(), _import_csharp(), _import_java(), _import_kotlin(), _import_lua(), _import_php() (+129 more)

### Community 6 - "_make_id"
Cohesion: 0.03
Nodes (104): _augment_cpp_string_tests(), _extract_js_rationale(), _extract_python_rationale(), _extract_spock_fallback(), _import_js(), _is_autogenerated_python(), Return True if this Python file is auto-generated and its module docstring is…, Post-pass: extract docstrings and rationale comments from Python source.… (+96 more)

### Community 7 - "build_from_json"
Cohesion: 0.02
Nodes (135): build_from_json(), _doc_twin_remap(), edge_datas(), _fold_edge_aliases(), Fold legacy edge field aliases onto canonical keys, in place (#2194). ``type``…, Return every edge attribute dict for (u, v); always a list., Map a markdown quick-scan's bare doc node ``<slug>`` to the semantic…, Build a NetworkX graph from an extraction dict. directed=True produces a… (+127 more)

### Community 8 - "graphify/__main__.py"
Cohesion: 0.04
Nodes (130): _agents_install(), _agents_platform_install(), _agents_platform_uninstall(), _agents_uninstall(), _always_on(), _amp_install(), _amp_legacy_cleanup(), _amp_uninstall() (+122 more)

### Community 9 - "test_multilang.py"
Cohesion: 0.06
Nodes (34): _confidences(), Tests for multi-language AST extraction: JS/TS, Go, Rust, SQL., ANSI SQL escapes a literal double quote inside a delimited identifier by…, #2577: `WITH levels(a, b) AS (...)` — the name precedes a column list., #2577: inside the declaring statement the CTE shadows a real same-named table…, #2577 refinement: a WITH inside a subquery is scoped to that subquery only. A…, #2812: `class FooApiException extends \\Exception` names PHP's global built-in.…, #2324: a REFERENCES target defined in ANOTHER file must collapse onto the real… (+26 more)

### Community 10 - "test_devin.py"
Cohesion: 0.06
Nodes (45): _devin_install_user(), Tests for graphify devin install / uninstall commands., The rules file installed by devin must use query-first policy., Installing rules twice does not change content and prints 'no change'., Project-scope install prints a git add hint covering .devin/ and .windsurf/., User-scope uninstall removes the skill file., User-scope uninstall prints an appropriate message when nothing is installed., Project-scope uninstall removes .devin/skills/graphify/SKILL.md. (+37 more)

### Community 11 - "detect.py"
Cohesion: 0.02
Nodes (167): _auto_follow_symlinks(), count_words(), detect_incremental(), docx_to_markdown(), _env_command_args(), extract_pdf_text(), _file_within_size_cap(), _find_vcs_root() (+159 more)

### Community 12 - "test_detect.py"
Cohesion: 0.01
Nodes (249): detect(), _is_sensitive(), Return True if this file likely contains secrets and should be skipped., as_posix_list(), _git(), parametrize, Path, skipif (+241 more)

### Community 13 - "test_dedup.py"
Cohesion: 0.03
Nodes (116): deduplicate_entities(), _entropy(), _norm(), Lowercase + collapse non-alphanumeric runs to space (Unicode-aware)., Shannon entropy in bits/char of the normalised label., Deduplicate near-identical entities in a knowledge graph. Args: nodes: list of…, _make_edges(), _make_nodes() (+108 more)

### Community 14 - "test_export.py"
Cohesion: 0.04
Nodes (102): cluster(), Run Leiden community detection. Returns {community_id: [node_ids]}. Community…, to_json(), _html_document_title(), _html_script(), _html_styles(), _hyperedge_script(), html — moved verbatim from graphify/export.py. (+94 more)

### Community 15 - "test_js_import_resolution.py"
Cohesion: 0.07
Nodes (102): _file_node_id(), File-level node ID matching the skill.md spec: ``{parent_dir}_{stem}`` — one…, _assert_no_root_slug(), _astro_paths(), _astro_project(), Path, Regression tests for #2195: Astro/Svelte regex-rescued imports must not mint…, Relative inputs: the real file node keeps its canonical id — the #1462… (+94 more)

### Community 16 - "export.py"
Cohesion: 0.04
Nodes (66): Release graph asset workflow, _node_community_map(), Invert communities dict: node_id -> community_id., _cap_filename(), _cypher_escape(), _cypher_label(), _git_head(), _obsidian_safe_stem() (+58 more)

### Community 17 - "test_install.py"
Cohesion: 0.02
Nodes (133): main(), Handle a downstream reader that closed the pipe early. Redirect stdout to…, Console entry point. Wraps the CLI so that when a downstream consumer closes…, _silence_broken_pipe(), _agents_install(), _agents_uninstall(), _cli_dispatched_commands(), _hook_commands() (+125 more)

### Community 18 - "classify_file"
Cohesion: 0.04
Nodes (87): Enum, classify_file(), FileType, Return the interpreter name from a shebang line. Handles forms that a naive…, Peek at the first line of an extensionless file for a shebang., _shebang_file_type(), _shebang_interpreter(), str (+79 more)

### Community 19 - "extract_bash"
Cohesion: 0.03
Nodes (74): _bash_assignment_base(), extract_bash(), Path, Extract functions, source imports, and cross-function calls from a .sh file., True if *target* is *ceiling* or lives beneath it, compared lexically…, Resolve a top-level assignment's value to a directory, or None if untracked.…, _within_tree(), parametrize (+66 more)

### Community 20 - "extract_js"
Cohesion: 0.02
Nodes (89): extract_js(), Extract classes, functions, arrow functions, and imports from a…, by_label_by_id(), #3035: Calls inside HOF-wrapped export callbacks (with options) are attributed…, #3035 / #1077: Arbitrary `obj.x = wrap(...)` must NOT produce a node., `Foo.prototype.bar = fn` must be captured as a method owned by Foo., `const f = function(){}` (function expression, not arrow) must be captured., A class field initialised with an arrow function (`x = () => {}`) must be… (+81 more)

### Community 21 - "test_dotnet.py"
Cohesion: 0.04
Nodes (82): extract_slnx(), extract_xaml(), _project_xml_is_safe(), Reject XML that declares DTDs or entities. Stdlib ``xml.etree.ElementTree``…, Extract projects and inter-project dependencies from a .slnx file. .slnx is the…, Extract WPF/XAML structure, bindings, x:Class, and event handler references., _xaml_binding_refs(), _xaml_explicit_viewmodel_names() (+74 more)

### Community 22 - "_edge_labels"
Cohesion: 0.04
Nodes (77): extract_java(), extract_kotlin(), extract_scala(), Extract classes, interfaces, methods, constructors, and imports from a .java…, Extract classes, objects, functions, and imports from a .kt/.kts file., Extract classes, objects, functions, and imports from a .scala file., extract_verilog(), Path (+69 more)

### Community 23 - "expand_oversized_files"
Cohesion: 0.05
Nodes (84): _best_cut(), bisect_slice(), expand_oversized_files(), FileSlice, is_splittable_text(), _pdf_text(), Path, Intra-file slicing for oversized text documents (#1369). The extraction packer… (+76 more)

### Community 24 - "test_cache.py"
Cohesion: 0.05
Nodes (53): _body_content(), check_semantic_cache(), Check semantic extraction cache for a list of absolute file paths. Returns…, Strip YAML frontmatter from Markdown content, returning only the body., Tests for graphify/cache.py., mode='deep' saves under cache/semantic-deep/ and reads back from it., Deep entries must not satisfy mode=None reads (and plain entries must not…, Omitting mode writes exactly the historical cache/semantic/ layout — forward-… (+45 more)

### Community 25 - "test_watch.py"
Cohesion: 0.02
Nodes (261): _drain_pending(), _is_read_only_event(), _is_remote_source(), _merge_changed_paths(), _notify_only(), _queue_pending(), Re-run AST extraction + build + optional cluster + report for code files. No…, Concatenate path lists, preserving order and dropping duplicates. Used to… (+253 more)

### Community 26 - "extract"
Cohesion: 0.07
Nodes (73): _canonicalize_csharp_namespace_nodes(), _check_tree_sitter_version(), extract(), Collapse duplicate C# namespace node entries to one canonical node per label., Raise a clear error if tree-sitter is too old for the new Language API., Extract AST nodes and edges from a list of code files. Two-pass process: 1.…, _labels_by_id(), Builtin-global receiver types must not resolve to same-named user symbols.… (+65 more)

### Community 27 - "test_llm_backends.py"
Cohesion: 0.04
Nodes (104): _call_openai_compat(), detect_backend(), extract_corpus_parallel(), extract_files_direct(), _get_backend_api_key(), _model_requires_default_temperature(), Path, Detect a successful HTTP response that yielded no usable extraction. A local… (+96 more)

### Community 28 - "test_cli_export.py"
Cohesion: 0.06
Nodes (76): _calls(), _init_git_repo(), _make_graph(), CompletedProcess, Path, Integration tests for graphify export subcommands and CLI commands. Each test…, #1423: `graphify extract` honours GRAPHIFY_OUT for where it WRITES, not only…, Write a minimal hand-rolled directed graph.json for path-direction tests. (+68 more)

### Community 29 - "test_import_extension_resolution.py"
Cohesion: 0.05
Nodes (75): Resolve a JS/TS module path or specifier to a local source file. With a Path…, _resolve_js_module_path(), _import_targets(), Path, Tests for #716 — TypeScript bare-path imports, Svelte 5 rune file imports…, JS variant of the rune file pattern: a `.svelte.js` file (used in JavaScript-…, When both `.svelte.ts` and `.svelte.js` exist (hybrid project mid- migration,…, If `foo.svelte` IS a real markup file, importing `./foo.svelte` must resolve to… (+67 more)

### Community 30 - "test_ruby_resolution.py"
Cohesion: 0.07
Nodes (72): extract_ruby(), Extract classes, methods, singleton methods, and calls from a .rb file., test_ruby_no_error(), _find_raw_call(), _has_call_edge(), _labels(), _method_edges(), _mixes_in() (+64 more)

### Community 31 - "test_pdf_token_estimate.py"
Cohesion: 0.08
Nodes (31): _file_to_text(), _get_tokenizer(), _pdf_text_for_estimate(), Extracted text of a PDF, memoised for the packing pass., Return a tiktoken encoder for accurate token counts, or None if tiktoken is not…, Return a text-like file's content for the extraction prompt. Most files are…, test_non_pdf_still_read_as_plain_text(), _actual_tokens() (+23 more)

### Community 32 - "_call_claude_cli"
Cohesion: 0.04
Nodes (74): _call_claude_cli(), _call_llm(), _claude_cli_envelope(), _claude_cli_error(), _claude_cli_supports_json_schema(), estimate_cost(), _no_window_kwargs(), Parse the JSON returned by `claude -p --output-format json`. Older Claude Code… (+66 more)

### Community 33 - "patch"
Cohesion: 0.03
Nodes (101): _estimate_file_tokens(), _extract_with_adaptive_retry(), _is_vision_image(), _pack_chunks_by_tokens(), Estimate the prompt-token cost of a file or slice under `_read_files` rules.…, Greedily pack files/slices into chunks that fit a token budget. Units are first…, Extract a chunk; if the response is truncated (`finish_reason="length"`), the…, fetch_worktrees() (+93 more)

### Community 34 - "test_pascal.py"
Cohesion: 0.07
Nodes (49): extract_lazarus_package(), Extract package metadata from Lazarus .lpk package files (XML format). .lpk is…, extract_delphi_form(), extract_lazarus_form(), Path, Extract component hierarchy from Delphi .dfm form files. .dfm files come in two…, Extract component hierarchy from Lazarus .lfm form files. .lfm is a text-based…, _dup_edges() (+41 more)

### Community 35 - "test_image_vision.py"
Cohesion: 0.06
Nodes (55): _anthropic_response_text(), _backend_supports_vision(), _bedrock_response_text(), _build_image_refs(), _partition_semantic_files(), Return the first Anthropic content block that carries text. Current Claude…, Return the first Converse content block that carries text. Converse returns…, Split a chunk into (text-like units, raster-image files). A ``FileSlice`` is… (+47 more)

### Community 36 - "test_serve.py"
Cohesion: 0.06
Nodes (59): _community_header(), _cut_lines_to_budget(), _find_node(), _load_graph(), Render pre-built lines under the same ~3-chars/token budget rule as…, Return node IDs whose label or ID matches the search term (diacritic-…, Shared node resolution for the get_node / get_neighbors tools. Returns…, _resolve_single_node() (+51 more)

### Community 37 - "test_csharp_member_calls.py"
Cohesion: 0.06
Nodes (66): _calls(), _find(), C# receiver-typed member-call resolution (#1609). `recv.Method()` where `recv`…, `Svc` exists in namespaces A and B; a caller file `using A;` must bind an…, No using directive and `Svc` in two foreign namespaces: genuinely ambiguous —…, A caller in namespace A resolves `Svc` to A.Svc even though B.Svc also exists —…, A local `Other x` shadowing a field `Server x` makes the name's type…, `var x = Compute();` (untypable) redeclaring a typed field poisons the name:… (+58 more)

### Community 38 - "test_security.py"
Cohesion: 0.06
Nodes (61): check_graph_file_size_cap(), _max_graph_file_bytes(), Any, Path, Resolve *path* and verify it stays inside *base*. *base* defaults to the…, Reject *path* if its size exceeds the configured graph-file cap. Protects…, Return the graph.json size cap in bytes. Honors the…, Strip control characters and cap length. Safe for embedding in JSON data… (+53 more)

### Community 39 - "test_codebuddy.py"
Cohesion: 0.06
Nodes (58): codebuddy_install(), codebuddy_uninstall(), Install the graphify skill and CODEBUDDY.md section for CodeBuddy., Remove the graphify skill tree (SKILL.md + references/) and the CODEBUDDY.md…, _codebuddy_install_user(), _codebuddy_md_path(), Tests for graphify codebuddy install / uninstall commands., The installed hook must include Read|Glob matcher for file-read interception. (+50 more)

### Community 40 - "test_multigraph_diagnostics.py"
Cohesion: 0.08
Nodes (58): load_graph(), _canonical_edge(), _count_extra(), diagnose_extraction(), diagnose_file(), _edge_list(), _exact_signature(), format_diagnostic_json() (+50 more)

### Community 41 - "cache.py"
Cohesion: 0.06
Nodes (59): _absolutize_ids_in(), _absolutize_source_files_in(), cached_files(), cached_word_count(), _cleanup_stale_ast_entries(), _ensure_stat_index(), _id_anchor(), _mtime_granularity_ns() (+51 more)

### Community 42 - "Communities (141 total, 52 thin omitted)"
Cohesion: 0.03
Nodes (71): Communities (141 total, 52 thin omitted), Community 0 - "Community 0", Community 10 - "Community 10", Community 11 - "Community 11", Community 12 - "Community 12", Community 13 - "Community 13", Community 14 - "Community 14", Community 15 - "Community 15" (+63 more)

### Community 43 - "Path"
Cohesion: 0.05
Nodes (62): _emit_rescued_import(), extract_astro(), _extract_parallel(), _extract_sequential(), _extract_single_file(), extract_svelte(), _is_cpp_header(), _is_objc_header() (+54 more)

### Community 44 - "_labels"
Cohesion: 0.05
Nodes (55): extract_csproj(), extract_groovy(), Extract classes, methods, constructors, and imports from a .groovy/.gradle…, Extract packages, project refs, and target framework from a…, extract_apex(), Path, Extract classes, interfaces, enums, methods, and Salesforce constructs from…, _labels() (+47 more)

### Community 45 - "to_obsidian"
Cohesion: 0.06
Nodes (63): _dedup_node_filenames(), Export graph as an Obsidian Canvas file - communities as groups, nodes as…, Map each node_id to a unique note filename, appending a numeric suffix on…, Export graph as an Obsidian vault - one .md file per node with [[wikilinks]],…, to_canvas(), to_obsidian(), Largest filename stem an exporter may write directly into ``output_dir``.…, stem_filename_budget() (+55 more)

### Community 46 - "test_benchmark.py"
Cohesion: 0.09
Nodes (54): _estimate_tokens(), _hr(), print_benchmark(), _query_subgraph_tokens(), Token-reduction benchmark - measures how much context graphify saves vs naive…, Print a human-readable benchmark report., Return unicode_char if stdout can encode it, else ascii_fallback. Windows…, Horizontal rule that survives non-UTF-8 stdout (e.g. Windows cp1252 console). (+46 more)

### Community 47 - "_parse_llm_json"
Cohesion: 0.05
Nodes (54): _parse_llm_json(), Strip optional markdown fences and parse JSON. Returns empty fragment on…, Force ``nodes``/``edges``/``hyperedges`` to lists of dicts, in place. A model…, _sanitize_fragment(), test_sanitize_fragment_coerces_dict_members_to_strings(), _make_envelope(), Tests for `_parse_llm_json` robustness and the `_call_claude_cli` subprocess…, Extraction instructions must be delivered in the user turn, not via --system-… (+46 more)

### Community 48 - "save_semantic_cache"
Cohesion: 0.06
Nodes (55): _group_has_partial_marker(), load_cached(), True if any node/edge/hyperedge in a per-file group carries the internal…, Save semantic extraction results to cache, keyed by source_file. Groups nodes…, Return cached extraction for this file if hash matches, else None. Cache key:…, save_semantic_cache(), _mark_partial(), _partial_source_files() (+47 more)

### Community 49 - "extract_python"
Cohesion: 0.07
Nodes (51): extract_python(), Extract classes, functions, and imports from a .py file via tree-sitter AST., All edge sources must reference a known node (targets may be external imports)., contains / method / inherits / imports edges must always be EXTRACTED., Call-graph pass must produce INFERRED calls edges., AST-resolved call edges are deterministic and should be EXTRACTED/1.0., run_analysis() calls compute_score() - must appear as a calls edge., Analyzer.process() calls run_analysis() - cross class→function calls edge. (+43 more)

### Community 50 - "extract_commonlisp"
Cohesion: 0.08
Nodes (40): extract_commonlisp(), Path, Extract packages, classes, functions, methods, macros, and calls from a Common…, _needs_commonlisp, A superclass defined in another file must still yield an inherits edge. The…, The def-prefix heuristic should catch definline / definline-maybe., Functions defined via custom definers should appear in the call graph., upi=, upi<, upi> must produce distinct ids (operator chars matter). (+32 more)

### Community 51 - "_make_graph"
Cohesion: 0.06
Nodes (44): Render subgraph as text, cutting at token_budget (approx 3 chars/token). seeds:…, _subgraph_to_text(), _make_graph(), A high-degree hub plus a low-degree answer node, to force the answer past a…, BUG2: a low-degree answer node passed as a seed is rendered first and survives…, BUG2 regression guard: the query path must pass seeds to the renderer (a branch…, #2601: nodes render before edges, so a budget overflow that only trims trailing…, #2784: once every node fits, edges are never dropped (#2601) — but that used to… (+36 more)

### Community 52 - "test_skillgen.py"
Cohesion: 0.06
Nodes (50): _platform_artifacts(), Tests for the tools/skillgen generator and the claude lean-core split. skillgen…, `agents` re-homes amp's agents-md body but with its OWN install wording. It…, The Windows bootstrap must not write the sidecar markers with a BOM (#3028).…, windows: name must be `graphify` (folder-name rule, #1635), powershell install,…, codex: spawn/wait/close_agent dispatch needing multi_agent = true., codex (was 4-value) and windows (was 5-value) now carry the superset., The extraction variant differs: codex compact, windows verbose. (+42 more)

### Community 53 - "_looks_like_context_exceeded"
Cohesion: 0.22
Nodes (9): BaseException, _looks_like_context_exceeded(), _looks_like_timeout(), Heuristically classify an exception as a context-window overflow. Different…, Classify an exception as a recognized subprocess or SDK timeout., test_looks_like_context_exceeded_ignores_unrelated_errors(), test_looks_like_context_exceeded_matches_common_messages(), test_looks_like_timeout_ignores_unrelated_errors() (+1 more)

### Community 54 - "test_reflect.py"
Cohesion: 0.09
Nodes (49): aggregate_lessons(), Aggregate parsed memory docs into a deterministic lessons structure. ``now``…, Render the aggregate into the deterministic LESSONS.md markdown body., render_lessons_md(), _days_before(), _doc(), Tests for `graphify reflect` and the work-memory reflection layer. `graphify…, Corroboration (k>=2) + sign decide the bucket, not raw frequency: A is useful… (+41 more)

### Community 55 - "validate_extraction"
Cohesion: 0.07
Nodes (48): introspect_postgres(), _quote_ident(), Connect to PostgreSQL, reconstruct DDL, and extract via extract_sql()., Double-quote a PostgreSQL identifier, escaping embedded double-quotes., assert_valid(), Validate an extraction JSON dict against the graphify schema. Returns a list of…, Raise ValueError with all errors if extraction is invalid., validate_extraction() (+40 more)

### Community 56 - "gen.py"
Cohesion: 0.05
Nodes (47): The translator is strict: a bash line it does not recognize fails the render…, test_powershell_translator_rejects_unknown_bash(), _core_to_powershell(), _enum_lines(), _is_cache_unlink_fix_line(), _is_chunk_cleanup_line(), _is_community_label_export_fix_line(), _is_content_scope_fix_line() (+39 more)

### Community 57 - "graphify exports reference (kiro)"
Cohesion: 0.05
Nodes (48): graphify exports reference (kilo), Rationale: skip the token-reduction benchmark for corpora under 5000 words because the graph's value there is structural clarity, not token compression, graphify detect step (.graphify_detect.json), graphify export falkordb, Rationale: prefer --falkordb-push over generating a Cypher file because FalkorDB's GRAPH.QUERY runs one statement at a time, unlike Neo4j's bulk cypher-shell import, graphify export graphml, Rationale: Claude Desktop config must use the absolute Python interpreter path because it can't run shell $(...) substitution and uv tool install's system python3 can't import graphify, graphify MCP server (graphify.serve) (+40 more)

### Community 58 - "test_global_graph.py"
Cohesion: 0.10
Nodes (44): prefix_graph_for_global(), prune_repo_from_graph(), Return a copy of G with all node IDs prefixed with repo_tag::. Labels are…, Remove all nodes tagged with repo_tag from G in-place. Returns count removed., _file_hash(), global_add(), global_list(), global_path() (+36 more)

### Community 59 - "extract_cpp"
Cohesion: 0.06
Nodes (48): _blank_keeping_newlines(), extract_cpp(), _normalize_cpp_cli(), Replace a match with spaces, but keep its line breaks. Byte length alone is not…, Rewrite C++/CLI spellings to standard C++ ones, or None if not C++/CLI. The…, Extract functions, classes, and includes from a .cpp/.cc/.cxx/.hpp file.…, _labels(), parametrize (+40 more)

### Community 60 - "load_platforms"
Cohesion: 0.06
Nodes (46): _powershell_platform_keys(), The per-host audit (the guard amp is the exact case for) passes for amp. amp…, The agents skill body is amp's body verbatim (it re-homes amp's bundle). The…, `agents` is a post-v8 platform, so its audit baseline is amp's v8 body., Every v8 heading single-homes for the cli-inline split hosts too., Every v8 heading lands in the lean core or exactly one reference., Every platform now carries one unified frontmatter description, byte for byte.…, Every platform that renders for a strict-PowerShell host (windows today, plus… (+38 more)

### Community 61 - "test_ollama.py"
Cohesion: 0.11
Nodes (20): _ollama_host_is_link_local_or_metadata(), True if *host* is, or resolves to, a link-local / cloud-metadata address.…, Warn if OLLAMA_BASE_URL looks unsafe; hard-block link-local/metadata (F3).…, _validate_ollama_base_url(), parametrize, Tests for the Ollama backend additions in graphify/llm.py., Link-local / cloud-metadata Ollama targets fail closed (F3)., Loopback is silent; a general LAN host warns but is allowed (F3). (+12 more)

### Community 62 - "test_indirect_dispatch.py"
Cohesion: 0.10
Nodes (44): _build(), _extract(), _extract_dir(), _extract_js_dir(), Indirect dispatch edges. A function passed BY NAME as a call argument…, No recall regression: a real module fn passed by name still emits an edge., Regression: when the scan root relativizes node ids (cache_root == project…, The cross-file resolver guard in extract.py must suppress indirect_call edges… (+36 more)

### Community 63 - "save_cached"
Cohesion: 0.06
Nodes (44): cache_dir(), prune_semantic_cache(), Save extraction result for this file. Stores as graphify-…, Remove orphaned semantic cache entries, returning the count pruned. The…, Returns the cache directory for ``kind`` - creates it if needed. kind is "ast",…, save_cached(), Prune touches only cache/semantic/*.json: AST entries and atomic-write *.tmp…, #1894 follow-up to #1527: prune must sweep cache/semantic/ AND cache/semantic-… (+36 more)

### Community 64 - "dedup.py"
Cohesion: 0.06
Nodes (39): _content_token_swap(), _crossfile_fileanchored_blocked(), _is_code(), _is_variant_pair(), _llm_tiebreak(), _make_minhash(), _merge_missing_attributes(), _numeric_tokens_differ() (+31 more)

### Community 65 - "test_community_labels_skill.py"
Cohesion: 0.20
Nodes (15): _code_blocks(), parametrize, Path, Curated community labels must reach the persisted graph.json (#2490). Two…, Same lint at the source of truth: the core fragments skillgen renders from., Passing community_labels stamps community_name on that community's nodes., Omitting the kwarg is the #2490 bug shape: no node carries community_name., Fenced code blocks of a markdown body, fence lines excluded. (+7 more)

### Community 66 - "install"
Cohesion: 0.07
Nodes (44): install(), Install graphify post-commit and post-checkout hooks in the nearest git repo., _make_git_repo(), Test 2: Without .graphifyrc, generated hooks omit GRAPHIFY_VIZ_NODE_LIMIT…, Test 3: viz_node_limit from .graphifyrc is baked into both hooks., Persisting the project default must not clobber an explicit per-run…, A typo in the committed .graphifyrc must not turn the read-only `status`…, Test 4: Re-running install updates existing Graphify hook block with new config. (+36 more)

### Community 67 - "test_serve_http.py"
Cohesion: 0.09
Nodes (55): _build_http_app(), _main(), _max_server_contexts(), _MCPASGIApp, Raw-ASGI wrapper around the Streamable HTTP session manager. Passed to a…, Build the Starlette ASGI app for the Streamable HTTP transport. Split out from…, Start the MCP server over Streamable HTTP (MCP spec 2025-03-26). Serves the…, Return the project-context LRU capacity (default 8, minimum 1).… (+47 more)

### Community 68 - "extract_objc"
Cohesion: 0.05
Nodes (43): extract_objc(), Path, Extract interfaces, implementations, protocols, methods, and imports from…, `@protocol Derived <Base>` must emit an implements edge Derived->Base.…, `[self speak]` inside Dog.fetch must produce a calls edge. The method-body…, `+ (…)shared` is a class method and must be labeled +shared, not -shared…, A compound message `[self a:x b:y]` resolves to the compound method def (#1475)., `NSArray<Product *> *` must reference the element type Product (and the… (+35 more)

### Community 69 - "to_wiki"
Cohesion: 0.09
Nodes (42): Path, Generate a Wikipedia-style wiki from the graph. Writes: - index.md — agent…, to_wiki(), _make_graph(), Tests for graphify.wiki — Wikipedia-style article generation., Each incident edge is counted exactly ONCE (#2633). The Parsing Layer (n1, n2)…, On a MultiGraph each parallel edge is its own row in the split (#2633).…, God node with bad ID should not crash. (+34 more)

### Community 70 - "reflect.py"
Cohesion: 0.09
Nodes (43): _build_id_label_maps(), build_learning_overlay(), _code_fingerprint(), _content_hash(), _decay(), _dedupe_by_question(), _empty_bucket(), _finalize_sources() (+35 more)

### Community 71 - "serve.py"
Cohesion: 0.06
Nodes (60): _compute_idf(), _filter_blank_stdin(), find_node_ambiguity(), _find_node_tiers(), _get_trigram_index(), _infer_context_filters(), _node_search_text(), _normalize_context_filters() (+52 more)

### Community 72 - "Communities"
Cohesion: 0.04
Nodes (54): Communities, Community 0 - "nanoGPT Model Architecture", Community 10 - "micrograd README + Backprop", Community 11 - "Attention Residuals Paper", Community 12 - "Continual LoRA Paper", Community 13 - "minGPT Trainer Class", Community 14 - "NeuralWalker Paper", Community 15 - "Dataset Abstractions" (+46 more)

### Community 73 - "normalize_id"
Cohesion: 0.08
Nodes (44): given, make_id(), normalize_id(), Single source of truth for node-ID normalization. Three independent producers…, r"""Normalize a single ID string to its canonical form. Guarantees, all…, Build a canonical node ID from one or more name parts. Parts are joined with…, _make_id(), Build a stable node ID via the single shared recipe (#1378). (+36 more)

### Community 74 - "claude_install"
Cohesion: 0.07
Nodes (39): claude_install(), Write the graphify section to the local CLAUDE.md., Tests for graphify claude install / uninstall commands., claude_install also writes .claude/settings.json with PreToolUse hook., Running claude_install twice does not duplicate the PreToolUse hook., Creates CLAUDE.md when none exists., claude_uninstall removes the PreToolUse hook from settings.json., A hook relocated to .claude/settings.local.json is removed on uninstall. (+31 more)

### Community 75 - "ingest_scip_json"
Cohesion: 0.05
Nodes (40): ingest_scip_json(), Convert a SCIP-style JSON document into Graphify nodes and edges. Parameter…, Cross-symbol relationship within ONE document resolves via the symbol index., Result passes Graphify's validate_extraction and build_from_json keeps the…, A symbol entry with `symbol: <int>` is silently skipped., A symbol with `relationships: None` ingests without error and emits no edges., A symbol with `kind` as a non-string falls back to 'unknown'., `display_name` as a non-string falls back to the symbol suffix. (+32 more)

### Community 76 - "graphify-out/ output directory (shared pipeline state)"
Cohesion: 0.12
Nodes (39): Native AGENTS.md integration - Amp (graphify amp install), Native AGENTS.md integration - generic agent (graphify agents install), Native CLAUDE.md integration - Claude Code (graphify claude install), Cross-repo / multi-subfolder graph merge (graphify merge-graphs), FalkorDB export (--falkordb / --falkordb-push), GitHub repo clone (graphify clone), graphify-out/ output directory (shared pipeline state), graphify skill reference: exports.md (agents) (+31 more)

### Community 77 - "test_cluster.py"
Cohesion: 0.09
Nodes (32): cohesion_score(), _native_leiden(), _partition(), Context manager to suppress stdout/stderr during library calls. graspologic's…, Call graspologic_native.leiden() directly, bypassing graspologic's own package…, Run a second Leiden pass on a community subgraph to split it further., Ratio of actual intra-community edges to maximum possible., Run community detection. Returns {node_id: community_id}. Tries Leiden… (+24 more)

### Community 78 - "extract_markdown"
Cohesion: 0.07
Nodes (38): _active_scan_root(), _build_link_index(), extract_markdown(), _nfc(), _parse_frontmatter(), _parse_frontmatter_fallback(), Path, Markdown extractor. Moved verbatim from graphify/extract.py. (+30 more)

### Community 79 - "test_transcribe.py"
Cohesion: 0.08
Nodes (35): build_whisper_prompt(), download_audio(), _get_whisper(), _get_yt_dlp(), is_url(), _model_name(), Path, Transcribe a video/audio file or URL to a .txt transcript. If video_path is a… (+27 more)

### Community 80 - "README.ja-JP.md"
Cohesion: 0.05
Nodes (42): Co získáte, Instalace, Jak to funguje, Postaveno na graphify — Penpax, Použití, Soukromí, Απόρρητο, Δημιουργήθηκε στο graphify — Penpax (+34 more)

### Community 81 - "_relations"
Cohesion: 0.07
Nodes (31): extract_php(), Extract classes, functions, methods, namespace uses, and calls from a .php file., Interfaces, enums, and traits must be captured as class-like nodes so their…, Module-level arrow functions must still emit a node and capture their calls…, _relations(), test_cpp_finds_includes(), test_cuda_finds_includes(), test_java_finds_imports() (+23 more)

### Community 82 - "test_query_induced_edges.py"
Cohesion: 0.14
Nodes (32): _bfs(), _complete_induced_edges(), _dfs(), _filter_graph_by_context(), Append edges between visited nodes that the traversal never recorded (#2323).…, _add(), _induced(), _link() (+24 more)

### Community 83 - "test_install_references.py"
Cohesion: 0.06
Nodes (40): _build_wheel_names(), fake_bundle(), _first_unbuilt_progressive_host(), _install(), Tests for the progressive-disclosure references/ sidecar install path. The real…, Reinstall swaps references/ in place, dropping a stale fragment., Uninstall rmtrees references/ before the dir walk so the tree is cleared., If SKILL.md links references/ but the dir is gone, warn to repair. (+32 more)

### Community 84 - "CsharpNameResolver"
Cohesion: 0.15
Nodes (14): _build_csharp_type_def_index(), CsharpNameResolver, _is_dotnet_source_file(), _metadata(), Path, C# cross-file resolution. The config-driven C# *extractor* (``extract_csharp``…, Namespace/using/alias-aware C# simple-name resolution. Factored out of…, Return deterministic ``(namespace, name) -> node_id`` C# type definitions. (+6 more)

### Community 85 - "test_mcp_ingest.py"
Cohesion: 0.11
Nodes (38): extract_mcp_config(), is_mcp_config_path(), Path, Return True when ``path`` is a recognised MCP config filename., Parse an MCP config file into Graphify nodes and edges. Behaviour matches other…, _label_by_kind(), Path, Tests for graphify.mcp_ingest — MCP config file extraction. (+30 more)

### Community 86 - "security.py"
Cohesion: 0.07
Nodes (29): _build_opener(), _ip_is_blocked(), _NoFileRedirectHandler, Raise ValueError if *url* is not http or https, or targets a private/internal…, Resolve *host* once and return (family, validated_ip) for the first address…, HTTPConnection that resolves + validates DNS once, then connects to the exact…, HTTPSConnection variant of _SSRFGuardedHTTPConnection. Connects to the…, urllib handler that routes http:// through _SSRFGuardedHTTPConnection. (+21 more)

### Community 87 - "test_scip_ingest.py"
Cohesion: 0.06
Nodes (35): Comprehensive tests for graphify.scip_ingest., Cross-document relationship resolves to the target document's node id., A relationship entry whose `symbol` is a non-string is silently skipped., A non-dict entry in `documents` is silently skipped., When two docs both have `F#`, a relationship from b.py's F# to F# must resolve…, When occurrences list is empty, source_location is empty string., Duplicate symbol records within the SAME document collapse to one node id in…, SCIP-supplied description must be HTML-escaped before reaching node metadata; a… (+27 more)

### Community 88 - "test_stat_index_portability.py"
Cohesion: 0.11
Nodes (32): _flush_stat_index(), _dirty(), _fresh_index(), Path, The atexit stat-index flush must not resurrect a deleted directory (#2974). A…, A first run writes the index before graphify-out/ exists at all; that stays as…, test_a_corpus_deleted_mid_run_stays_deleted(), test_a_redirected_cache_root_that_vanished_is_not_recreated() (+24 more)

### Community 89 - "test_affected_cli.py"
Cohesion: 0.08
Nodes (32): resolve_seed(), A trailing path separator must not change the match (parity with explain's…, Several nodes share a source_file but none is the L1 file node and none's…, A caller whose call site (L158) differs from its own def line (L90)., An edge with no stored location honestly falls back to the node's def line., `./x.py`, an absolute path and `x.py` name one file and must resolve alike. The…, An absolute-path seed resolves off the graph's location, not the cwd (#2706).…, An absolute seed that is NOT under the derived repo root must report a clean… (+24 more)

### Community 90 - "attach_hyperedges"
Cohesion: 0.14
Nodes (17): attach_hyperedges(), Store hyperedges in the graph's metadata dict., _node(), Hyperedges must survive the dual-slot persistence round-trip (#2485). to_json…, _roundtrip(), test_full_wipeout_emits_one_aggregate_warning(), test_nested_only_slot_is_read_and_reexported_to_both_slots(), test_top_level_slot_roundtrips_unchanged() (+9 more)

### Community 91 - "hooks.py"
Cohesion: 0.10
Nodes (32): _git_root(), _has_merge_attr(), _install_hook(), _load_graphifyrc(), _merge_attr_line(), _merge_driver_status(), Path, Load key/value options from <root>/.graphifyrc if present. Supported options:… (+24 more)

### Community 92 - "ingest.py"
Cohesion: 0.11
Nodes (32): _detect_url_type(), _download_binary(), _fetch_arxiv(), _fetch_html(), _fetch_tweet(), _fetch_webpage(), _html_to_markdown(), ingest() (+24 more)

### Community 93 - "test_querylog.py"
Cohesion: 0.12
Nodes (31): _log_path(), log_query(), _log_responses(), nodes_from_result(), Any, Path, Query logging for graphify — append-only JSONL, fail-silent., Append one JSONL record to the query log. Never raises. (+23 more)

### Community 94 - "_score_nodes"
Cohesion: 0.06
Nodes (39): Combined query scorer returning the existing ranked `(score, node_id)` list.…, _score_nodes(), _make_random_scoring_graph(), parametrize, A multi-word query equal to a whole label must resolve uniquely. Regression for…, Searching for '路由' should match a node with label containing '路由'., Test-only oracle for the legacy per-term `_pick_seeds(terms=...)` loop. Re-…, Reproducible broad-match DiGraph: short constructed labels + edge noise. Labels… (+31 more)

### Community 95 - "HttpClient"
Cohesion: 0.10
Nodes (25): __global__, AuthedHttpClient, token_, Connection, resource, string, T, HttpClient (+17 more)

### Community 96 - "test_no_dedup_flag.py"
Cohesion: 0.27
Nodes (14): _assert_spied(), _capture_dedup(), _corpus(), `graphify extract --no-dedup` (#2881). The incremental merge path hardcoded…, Run the CLI and return its exit code (0 when main() simply returns)., Record the `dedup` kwarg both build entry points are called with. Patching…, Fail loudly if the spy never fired, so no assertion is vacuous., _run() (+6 more)

### Community 97 - "callflow_html.py"
Cohesion: 0.09
Nodes (31): build_community_index(), _community_text(), derive_sections_from_communities(), _describe_node(), generate_overview_cards(), html_anchor_id(), _keyword_score(), label_for_community() (+23 more)

### Community 98 - "test_obsidian_vault_migration.py"
Cohesion: 0.11
Nodes (31): _adopt_pre_manifest_notes(), existing_graph_node_count(), _is_graphify_note(), Path, Node count of an existing graph.json. Returns: - an ``int`` node count when the…, Whether a vault note carries graphify's own frontmatter signature. Every note…, Names of notes in *out* that graphify itself wrote before manifests existed.…, test_existing_graph_node_count() (+23 more)

### Community 99 - "prs.py"
Cohesion: 0.30
Nodes (22): default_graph_json(), Default ``graph.json`` path under the configured output dir. The package-wide…, bold(), _c(), _ci_icon(), cmd_prs(), cyan(), dim() (+14 more)

### Community 100 - "_query_terms"
Cohesion: 0.09
Nodes (23): _has_chinese(), _is_searchable(), _query_terms(), Segment Chinese text and keep the original term for exact matching., True if term is Chinese, non-English, or an English word longer than 2 chars., Split a query into searchable terms, segmenting Chinese text, then drop…, _segment_chinese(), Chinese text should use the cached jieba module and keep the original term. (+15 more)

### Community 101 - "test_explain_cli.py"
Cohesion: 0.12
Nodes (31): Regression tests for `graphify explain` arrow direction (#853)., No sidecar => no Lesson line; output identical to pre-feature., BUG1: an explain connection shows the edge's call-SITE line (in the caller's…, A node with n_callers callers, spread across `files` (default: 3 files, so…, Baseline: the cut count is still announced (pre-existing behavior)., #2009: past the top-20 cutoff, the remaining callers must still be accounted…, Regression guard: nodes at or below the 20-connection cutoff keep the pre-#2009…, Pin the exact `> 20` cutoff itself. The other #2009 tests use 30 and 5… (+23 more)

### Community 102 - "test_hooks.py"
Cohesion: 0.07
Nodes (30): _detached_launch(), Return a POSIX-sh line that runs ``rebuild_body`` as a detached background…, Tests for hooks.py - git hook install/uninstall., Test 1: .graphifyrc parsing for valid and invalid values., Hook script must skip shebang extraction for .exe binaries (Windows)., The detection fallback must emit a message to stderr rather than bare exit 0. A…, graphify hook-check must not emit additionalContext — Codex Desktop rejects it., The shared rebuild bodies are embedded verbatim into the launcher, so they too… (+22 more)

### Community 103 - "parametrize"
Cohesion: 0.07
Nodes (31): _pinned_python(), Return sys.executable if its path is shell-safe, else an empty string. Applies…, _launcher_payload(), parametrize, The rebuild must survive a marker written by Windows PowerShell 5.1 (#3028).…, Git for Windows' bundled shell ships no `nohup`/`setsid`, so the old `nohup ...…, The replacement detaches via Python: start_new_session on POSIX and…, Git for Windows/MSYS hooks can expose fragile pipe handles to spawned… (+23 more)

### Community 104 - "test_minhash.py"
Cohesion: 0.11
Nodes (23): _lsh_integrate(), _mh_coeffs(), MinHash, MinHashLSH, _optimal_lsh_params(), MinHash + band-LSH — datasketch-compatible drop-in (no scipy). datasketch.lsh…, MinHash sketch — same API as datasketch.MinHash for the subset used here., Numerical integration — replaces scipy.integrate.quad for LSH param search. (+15 more)

### Community 105 - "build_merge"
Cohesion: 0.06
Nodes (61): build_merge(), Load existing graph.json and return it merged with ``new_chunks``. Does NOT…, _he_ids(), Path, skipif, Incremental --update: hyperedge preservation (#1574) and root-less prune…, A symlinked scan root (macOS /var -> /private/var, symlinked home/worktree)…, #1796: a file present in BOTH new_chunks (re-extracted) and prune_sources must… (+53 more)

### Community 106 - "skipif"
Cohesion: 0.10
Nodes (31): _assert_harness_can_reject(), _broken_uv_machine(), _detect_run(), _extract_case_pattern(), skipif, Run the emitted _PYTHON_DETECT under a real sh in a controlled environment —…, #2852's machine: the only graphify-importable python lives in the uv tool venv;…, Create a fake uv tool env python under <home>/.local/share/uv/tools; ok=False… (+23 more)

### Community 107 - "render_all"
Cohesion: 0.08
Nodes (31): #1939: a skill's cache read and write must both name the extraction prompt they…, Regression for #1461: every skill body that describes Step 3 extraction must…, The committed codex/windows artifacts match a fresh render and expected/., The committed artifacts and the expected/ snapshot match a fresh render. This…, Rendering twice yields byte-identical output (no timestamps/versions)., Generated artifacts use LF newlines and end in exactly one newline., No generated artifact carries the package version string., A full render carries the always-on files; a --platform render does not. (+23 more)

### Community 108 - "test_unverified_semantic_shrink.py"
Cohesion: 0.11
Nodes (30): _ast_node(), Path, Tests for unverified semantic document node shrink protection (#3203). When an…, 10 -> 10 semantic nodes with completely different IDs is not flagged as a…, Semantic growth (3 -> 4) is unaffected., Multiple chunks for the same source are summed before comparison (2 + 2 = 4 >=…, Growth in B (3 -> 20) cannot mask unverified shrink in A (6 -> 2)., merge_raw_extraction also flags unverified semantic shrink. (+22 more)

### Community 109 - "extract_dm"
Cohesion: 0.22
Nodes (17): extract_dm(), Extract types, procs, includes, and calls from a .dm/.dme file., _needs_dm, _calls(), test_dm_ambiguous_member_call_left_unresolved(), test_dm_call_edges_have_call_context(), test_dm_emits_include_edge(), test_dm_emits_new_as_instantiates() (+9 more)

### Community 110 - "run_language_resolvers"
Cohesion: 0.12
Nodes (27): LanguageResolver, Path, Registry for cross-file, language-specific resolution passes. Some…, One cross-file, language-specific resolution pass. ``resolve`` has the…, Append a resolver to the global registry and return it (for inline use)., Return a copy of the registered resolvers, in registration order., Run every resolver whose suffix appears in ``paths``. Behaviorally identical to…, register() (+19 more)

### Community 111 - "_query_graph_text"
Cohesion: 0.09
Nodes (23): _query_graph_text(), _make_callers_graph(), _make_noisy_graph(), FooBarService error handling' should expand from FooBarService, not from error-…, A service, three callers wired via context='call' edges, and a decoy whose…, Who calls X?' must seed on X, not on a decoy that merely prefix-matches the…, All-intent fallback: a query that is ONLY intent words keeps the seed…, Demotion only strips the GUARANTEE: a node literally named 'calls' whose score… (+15 more)

### Community 112 - "test_indirect_call_function_expression_shadow.py"
Cohesion: 0.12
Nodes (29): _extract_js_dir(), _indirect(), An untracked `function (…) {…}` expression's bindings must shadow indirect_call…, Locals, not just parameters, are scoped to the expression's body., Control: the arrow path was already correct and must stay correct., The bindings are scoped to the expression: a same-named module callable…, Two function expressions in one initializer are SEPARATE scopes: the first…, Widening the shadow set must not blanket-suppress inside the body: an… (+21 more)

### Community 113 - "graphify Whisper video/audio transcription"
Cohesion: 0.07
Nodes (30): graphify transcribe reference (droid), graphify detect step (.graphify_detect.json), Issue #1392 (stdout corrupts transcript JSON), Rationale: write transcript JSON from Python, not shell '>' redirect, because Whisper's stdout progress output would corrupt the JSON file, graphify Step 3B semantic subagent dispatch, graphify Whisper video/audio transcription, graphify transcribe reference (kilo), graphify detect step (.graphify_detect.json) (+22 more)

### Community 114 - "write_callflow_html"
Cohesion: 0.09
Nodes (28): build_section_node_map(), CallflowOptions, classify_edges(), detect_lang(), html_comment_text(), infer_project_name(), load_labels(), load_report() (+20 more)

### Community 115 - "test_go_qualified_resolution.py"
Cohesion: 0.16
Nodes (28): _case_only_sibling_corpus(), _extract(), _ids(), Path, Regression coverage for package-qualified Go calls and type references., An aliased internal qualified type points to its package definition., Changed callers still resolve calls and types defined in unchanged files., Exported wrapper + unexported worker of the same name, plus a decoy. (+20 more)

### Community 116 - "test_install_roundtrip.py"
Cohesion: 0.08
Nodes (28): _copy_in_tmp(), fake_progressive_bundle(), _has_real_bundle(), _install_via_entrypoint(), parametrize, Full per-platform install + uninstall round-trip suite. Every platform graphify…, amp's project-scope skill lands under .agents/skills, an Amp search root., VS Code Copilot Chat round trip at ~/.copilot/skills/graphify + instructions… (+20 more)

### Community 117 - "test_path_cli.py"
Cohesion: 0.10
Nodes (28): _arrow_line(), _diamond_graph(), _flipped_marker_graph(), Regression tests for `graphify path` arrow direction (#849) and determinism +…, No full-token candidate -> behavior identical to the old scored[0] pick., Two equal-length routes A->P->B and A->Q->B — a tie the traversal must resolve…, #2074: the same graph must yield the same route regardless of PYTHONHASHSEED.…, #2074: the printed relation must be the edge's ACTUAL stored relation, never a… (+20 more)

### Community 118 - "storage.py"
Cohesion: 0.08
Nodes (37): handle_delete(), handle_get(), handle_list(), handle_search(), Fetch a document by ID and return it., Delete a document by ID., List all document IDs in storage., Simple keyword search over the index. Returns documents whose keyword list… (+29 more)

### Community 119 - "test_csharp_interface_dispatch.py"
Cohesion: 0.13
Nodes (26): _is_csharp(), _method_label(), Member-level interface dispatch for C# (#3003). A C# call through a…, True when the node is a declaration that lives in a C# file. Every end of a…, Return a method node's bare name, for matching. Case is kept: C# is case…, Link each single-implementer interface method to its implementation. Purely…, resolve_csharp_interface_dispatch(), _extract() (+18 more)

### Community 120 - "extract_vue"
Cohesion: 0.15
Nodes (25): extract_vue(), _normalize_ts_import_types(), Rewrite TypeScript `import(...)` type arguments in call expressions to standard…, Extract imports, symbols, and type refs from a ``.vue`` SFC. Masks the…, Blank everything outside ``<script>`` bodies, keeping ``\\r``/``\\n``. Replaces…, _vue_mask_non_script(), Path, Tests for ``.vue`` SFC extraction. Feeding a whole SFC to the JS grammar… (+17 more)

### Community 121 - "test_labeling.py"
Cohesion: 0.16
Nodes (25): generate_community_labels(), label_communities(), _placeholder_community_labels(), Return a complete ``{cid: name}`` map using ``backend`` for naming. Communities…, CLI entry point: resolve a backend, name communities, and degrade to…, _graph(), Tests for LLM-backed community labeling (issue #1097). Backend calls are mocked…, god_nodes() returns list[dict] with an 'id' key, not bare ids. (+17 more)

### Community 122 - "test_prs.py"
Cohesion: 0.21
Nodes (9): _classify(), format_prs_text(), Plain-text PR summary for MCP output (no ANSI)., make_pr(), datetime, Tests for graphify/prs.py., Build a minimal PRInfo with sensible defaults., TestClassify (+1 more)

### Community 123 - "test_hook_guard.py"
Cohesion: 0.15
Nodes (27): _cli(), _env(), _invoke(), parametrize, Rigorous edge-case coverage for the `graphify hook-guard` subcommand (#522).…, test_dispatch_always_exits_zero(), test_dispatch_missing_mode_exits_zero_silent(), test_dispatch_unknown_mode_exits_zero_silent() (+19 more)

### Community 124 - "test_read_hook.py"
Cohesion: 0.12
Nodes (27): _env(), The Read|Glob PreToolUse guard nudges toward the graph instead of raw reads.…, Config files must stay silent: '.json' must not match the '.js' extension., A real trailing extension must win on multi-dot names (the segment split):…, Backslash-separated paths split on the real final segment, then its ext., An extension that sits on a directory component, not the final segment, must…, A nudge is additionalContext only - the guard must exit 0, never deny., Reading the graph's own report must not start a go-read-the-graph loop. (+19 more)

### Community 125 - "_make_symbol_doc"
Cohesion: 0.07
Nodes (28): _make_symbol_doc(), Helper to build a minimal SCIP document with one symbol., is_reference → relation 'scip_ref'., is_definition → relation 'scip_def'., is_implementation → relation 'scip_impl' (takes priority over is_definition)., is_type_definition → relation 'scip_typed'., Implementation > TypeDefinition > Definition > Reference., When none of is_* flags are set, relation defaults to 'scip_ref'. (+20 more)

### Community 126 - "test_swift_cross_file_calls.py"
Cohesion: 0.22
Nodes (27): _edge_labels(), _extension_fixture(), _issue_fixture(), _label(), Path, #1604: `let x = Type.shared` cached into a local var, then `x.method()` on a…, A singleton, a caller, and a cross-file `extension` of that singleton., Return {(source_label, relation, target_label)} for the given relations. (+19 more)

### Community 127 - "sample.swift"
Cohesion: 0.09
Nodes (17): Bool, Foundation, CacheManager, createProcessor(), NetworkError, connectionFailed, failed, timeout (+9 more)

### Community 128 - "test_callflow_html.py"
Cohesion: 0.12
Nodes (28): first_list(), generate_call_table_rows(), load_graph(), _node_link_payload(), Return the first list from a set of possible schema locations., Generate call table row scaffolding for a section's nodes. The Caller/Callee…, Read current graphify graph.json via NetworkX's node-link parser., Load graph.json. Returns normalized (nodes, edges, hyperedges, metadata). (+20 more)

### Community 129 - "_parse_apm_fallback"
Cohesion: 0.27
Nodes (11): _parse_apm_fallback(), Minimal line parser for apm.yml when PyYAML is unavailable: a top-level…, The apm.yml fallback parser must return the manifest's version. ``_parse_apm``…, `version:` nested under dependencies belongs to a dep, not the package., test_a_manifest_with_no_name_is_rejected(), test_a_manifest_without_a_version_still_parses(), test_a_version_inside_the_dependencies_block_is_not_the_package_version(), test_fallback_returns_the_version() (+3 more)

### Community 130 - "scip_ingest.py"
Cohesion: 0.11
Nodes (26): _build_scip_metadata(), _coerce_str(), _emit_relationships(), _emit_symbol_node(), _first_occurrence_line(), _is_true(), Any, scip_ingest.py — SCIP JSON ingestion (simplified subset). Reads a simplified… (+18 more)

### Community 131 - "DataProcessor"
Cohesion: 0.09
Nodes (13): java.util.List, Override, ErrorCode, GAME_DONE, OK, ExtendedService, HttpClient, BaseProcessor (+5 more)

### Community 132 - "introspect_cargo"
Cohesion: 0.15
Nodes (24): introspect_cargo(), _load_toml(), _member_manifest_paths(), Any, Path, Cargo manifest introspection for workspace-internal crate dependencies., Return crate nodes and internal dependency edges from Cargo manifests., Real workspace: pin raw graph fields while excluding registry-only deps. (+16 more)

### Community 133 - "test_dedup_remaps_hyperedges.py"
Cohesion: 0.13
Nodes (25): Rewire hyperedge member ids onto dedup survivors, in place. Members come in…, _remap_hyperedge_members(), _extraction(), _members(), _node(), parametrize, Dedup must rewire hyperedge members onto survivors, not drop them. `build()`…, A dedup remap built from union-find is fully flattened (path-compressed), so a… (+17 more)

### Community 134 - "test_ignore_file_encoding.py"
Cohesion: 0.13
Nodes (25): Read an ignore file, preferring UTF-8 but never silently dropping a rule. These…, _read_ignore_text(), _corpus(), parametrize, r"""An ignore file that is not valid UTF-8 must not silently lose its rules.…, The actual regression: every rule survives, even if a third encoding renders it…, The existing NFC/NFD guarantee must survive the new decode path., A UTF-16 (BOM) .graphifyignore — what PowerShell Set-Content and Notepad… (+17 more)

### Community 135 - "resolve_bash_source_edges"
Cohesion: 0.09
Nodes (26): _file_node_id_for_path(), Path, Resolve Bash source/import edges and source-backed function calls. Defensive…, resolve_bash_source_edges(), Path, When a callee function is defined in multiple sourced files, skip it., Non-bash raw_calls inside sourced-file per_file entries are ignored., A `bash_sources` entry missing `target_path` must not raise KeyError. (+18 more)

### Community 136 - "build_tree"
Cohesion: 0.16
Nodes (24): build_tree(), _common_root(), emit_html(), _make_truncation_leaf(), Any, Path, tree_html — emit a D3 v7 collapsible-tree HTML view of a graph. A self-…, Build a ``{name, total_count, children}`` hierarchy. Each leaf is either a code… (+16 more)

### Community 137 - "_fixture"
Cohesion: 0.23
Nodes (26): cache_root(), tmp_file(), _fixture(), _invoke(), _is_deny(), Strict-mode hook-guard: opt-in block-then-nudge + #1840 gating. The strict…, A project with graphify-out/graph.json + manifest and one source file.…, _read() (+18 more)

### Community 138 - "test_extract_code_only_cli.py"
Cohesion: 0.14
Nodes (25): _mixed_repo(), Path, `graphify extract --code-only` indexes code without an LLM key (#1734). A mixed…, #1971 persistence: once --no-gitignore is set, a later flag-less `graphify…, #2106 traceability: a file dropped by the sensitive-file filter is reported by…, #2923 regression: --code-only --force must not drop the existing semantic…, #2923 follow-up: --code-only --force preserves surviving semantic nodes but…, #3125 regression: `extract --code-only --force` over an existing graph must… (+17 more)

### Community 139 - "_corpus"
Cohesion: 0.10
Nodes (26): _assert_no_dangling(), _corpus(), _nodes_with_label(), Run the full extract() pipeline on fixture files (absolute, resolved paths so…, Foo.h (class) + Foo.cpp (Foo::bar def) + Main.cpp must yield exactly ONE Foo…, `void bar();` in Foo.h and `void Foo::bar() {}` in Foo.cpp must collapse to ONE…, The decl/def merge keeps the header node, so `source_file` names the…, A symbol that was never merged must not grow the new attributes — they mark a… (+18 more)

### Community 140 - "e"
Cohesion: 0.09
Nodes (33): Processor, e(), handle_enrich(), handle_upload(), API module - exposes the document pipeline over HTTP. Thin layer over parser,…, Accept a list of file paths, run the full pipeline on each, and return a…, Re-enrich a document to pick up new cross-references., batch_parse() (+25 more)

### Community 141 - "_semantic_id_remap"
Cohesion: 0.10
Nodes (24): Re-derive non-AST node ids from ``source_file`` using the canonical full-path…, _semantic_id_remap(), parametrize, MCP ingest stamps every node with L1 (JSON has no line info), so global ids…, End-to-end: a freshly extracted graph containing a .mcp.json — nested or at the…, Re-key contract: a relative source_file is migrated; an absolute one is left…, #2618: an absolute source_file is left alone whichever OS wrote it., The legacy-ID probe derives a stem from source_file, so it must skip an… (+16 more)

### Community 142 - "google_workspace.py"
Cohesion: 0.14
Nodes (23): convert_google_workspace_file(), _extract_file_id_from_url(), _extract_resource_key(), google_workspace_enabled(), Any, Path, Optional Google Workspace shortcut export support. Google Drive for desktop…, Export a Google Workspace shortcut to a Markdown sidecar. Returns the converted… (+15 more)

### Community 143 - "test_symbol_resolution.py"
Cohesion: 0.05
Nodes (75): build_label_index(), build_python_symbol_index(), existing_edge_pairs(), find_unique_python_symbol(), ImportedSymbol, iter_raw_calls(), _module_stem(), node_is_resolvable_symbol() (+67 more)

### Community 144 - "test_incremental.py"
Cohesion: 0.13
Nodes (24): _edges(), _make_docs_corpus(), CompletedProcess, Path, Integration tests for incremental graphify extract behavior., #2169: an incremental --no-cluster extract of ONE changed file must merge into…, #2169: an incremental --code-only --no-cluster run over a mixed corpus must…, #2213 (defect 1, shared root with #2211): a Python relative import's… (+16 more)

### Community 145 - "test_jsconfig_baseurl.py"
Cohesion: 0.22
Nodes (24): _cid(), Path, _rails_tree(), Regression tests: jsconfig.json / baseUrl module resolution (#2153).…, Editing `paths` mid-session must retarget the alias, not keep the old map., Same contract for the separately cached `baseUrl` root (#2153)., A webpacker-shaped project: config at the root, modules under baseUrl., Canonical root-relative file-node id of a cross-file import target (#2169). (+16 more)

### Community 146 - "multigraph_compat.py"
Cohesion: 0.17
Nodes (18): _build_probe_graph(), CapabilityCheck, _check(), MultigraphCapabilityResult, _probe_duplicate_key_overwrite_semantics(), _probe_keyed_parallel_edges(), probe_multigraph_capabilities(), _probe_node_link_round_trip() (+10 more)

### Community 147 - "_shrink_payload"
Cohesion: 0.12
Nodes (16): Build a minimal graph-data dict with *n* placeholder nodes., Default case: smaller new graph + no force + no declared deletions = refuse., force=True bypasses the guard regardless of node delta., Caller declared deletions → shrink is expected → guard skipped silently., First-run case: no existing graph → guard inert., new > existing is always fine., When refusing, the temp graph file gets cleaned up so it can't leak across runs., Mirror of the above: if the caller declared deletions, the tmp file is NOT… (+8 more)

### Community 148 - "_clear_backend_keys"
Cohesion: 0.14
Nodes (24): _clear_backend_keys(), _failing_sql(), _manifest_row(), _node_sources(), _ok_sql(), parametrize, Seed a graph with nodes for x.py, drop x.py from the manifest (pre-#1897…, Post-#1897 state: the excluded file IS manifest-listed. It must be pruned from… (+16 more)

### Community 149 - "_make_corpus"
Cohesion: 0.09
Nodes (24): _make_corpus(), When every semantic chunk errors (e.g. backend SDK not installed), the CLI must…, Minimal corpus: one Go code file + one Markdown doc. Both file types are needed…, Sanity counter-test: a successful chunk run keeps exit 0. Confirms the new…, #1948 x #1950 interaction: a doc stamped complete on a prior run that TRUNCATES…, #1897: fresh extraction returns nodes with ROOT-RELATIVE source_file, while the…, #1920 end-to-end: a fresh extraction whose only output for a doc is a hyperedge…, extract_corpus_parallel stand-in that records each dispatch. (+16 more)

### Community 150 - "test_js_dynamic_imports.py"
Cohesion: 0.20
Nodes (23): _edges_to(), Path, `import('…')` in plain .ts/.js must produce exactly one edge per fact (#2575).…, At module scope `caller_nid` IS the file node, so the rescue is genuinely…, The rescue pass must not disturb the AST pass it runs beside., A backtick specifier with no `${` is as static as a quoted one — the AST path…, `fooimport('./x')` is a call to `fooimport`, not a dynamic import., ordinary calls inside a nested named function attribute to that inner function… (+15 more)

### Community 151 - "test_kotlin_grammar.py"
Cohesion: 0.25
Nodes (23): _edges(), _extract(), _find(), Kotlin grammar-node-type mismatches (#2526, #2550, #2551). PyPI tree-sitter-…, Golden guard: ordinary multi-line Kotlin produces the same nodes/edges as…, test_kotlin_aliased_import_resolves_to_original_symbol(), test_kotlin_class_property_initializer_calls(), test_kotlin_companion_property_initializer_attributes_to_class() (+15 more)

### Community 152 - "test_prune_sweeps_orphans.py"
Cohesion: 0.17
Nodes (23): _corpus_graph(), _extraction(), _prune(), Pruning a source file must not leave its external-import nodes behind.…, Scoped to what this prune orphans. A source-less node that was already isolated…, Only source-less nodes are swept. A node with a real source_file is prunable…, The sweep lives inside the prune branch; a plain merge must not touch isolated…, The #479 shrink guard raises on unexplained node loss. Swept orphans are… (+15 more)

### Community 153 - "graphify github-and-merge reference (kiro)"
Cohesion: 0.11
Nodes (24): graphify github-and-merge reference (kilo), graphify clone <github-url>, graphify extract per-subfolder (monorepo pattern), graphify merge-graphs, graphify query command, Rationale: running the skill pipeline separately per subfolder would clobber a shared graphify-out/ dir, so use the CLI directly per subfolder (it nests graphify-out/ inside the scanned path), graphify github-and-merge reference (kiro), graphify clone <github-url> (+16 more)

### Community 154 - "test_hook_out_of_project_paths.py"
Cohesion: 0.17
Nodes (22): _is_cwd_relative(), r"""Whether *value* is anchored at the current working directory. The hook's…, _fake_os_name(), _invoke(), _project(), parametrize, skipif, r"""The read hook's out-of-project guard must not treat a rooted-but-driveless… (+14 more)

### Community 155 - "test_atomic_writes.py"
Cohesion: 0.16
Nodes (17): Atomically write ``text`` (UTF-8) to ``path``. See :func:`_atomic_replace`., write_text_atomic(), skipif, Tests for atomic JSON writes (graph.json / manifest.json). A crash, kill, or…, On Windows os.replace raises PermissionError when the destination is briefly…, The Windows analogue of the mode-preservation contract. There is no POSIX mode…, test_save_manifest_writes_atomically(), test_to_json_writes_atomically_no_tmp_leftover() (+9 more)

### Community 156 - "test_semantic_cleanup.py"
Cohesion: 0.19
Nodes (22): Return validation errors for an untrusted semantic extraction fragment. Empty…, validate_semantic_fragment(), Tests for graphify.semantic_cleanup.validate_semantic_fragment (#825)., #1561: an alias-keyed hyperedge must not be rejected for a missing `nodes` list…, An unknown/synonym file_type is NOT a validation failure: build_from_json…, LLM output with file_type='rationale' must pass validation so the cleanup pass…, LLM output with file_type='concept' must pass validation for the same reason., test_validate_accepts_node_ids_keyed_hyperedge() (+14 more)

### Community 157 - "_rewire_unique_stub_nodes"
Cohesion: 0.07
Nodes (32): _is_top_level_function_definition(), _lang_family(), _lang_is_case_insensitive(), _merge_swift_extensions(), _node_label_key(), True when the file's language resolves identifiers case-insensitively (#1581)., Interop family of the file's language, or None when unknown/not code., A free/top-level function def (label ``name()``), not a method or type. Methods… (+24 more)

### Community 158 - "test_js_dynamic_import_affected.py"
Cohesion: 0.19
Nodes (22): _build(), _fid(), _file_edges(), DiGraph, Path, `affected` must traverse a dynamic `import('…')` written inside a function —…, `import * as ns` binds the module, not the function that defers the load., `other` is a sibling export; the edge into `load()` that used to rescue this is… (+14 more)

### Community 159 - "_write_raw_doc"
Cohesion: 0.13
Nodes (21): _overlay_corpus(), _overlay_graph(), Path, Write a memory doc with a controlled date so ordering is deterministic to…, Write a minimal graph.json under ``out`` with the given node dicts., A corpus with: a PREFERRED node (2 useful), a TENTATIVE node (1 useful), a…, reflect with a graph writes .graphify_learning.json next to graph.json with the…, Two reflect runs on identical input + fixed `now` produce a byte-identical… (+13 more)

### Community 160 - "test_search_hook.py"
Cohesion: 0.15
Nodes (22): _env(), The Bash PreToolUse guard nudges toward the graph before grep/find searches.…, The guard resolves the graph via GRAPHIFY_OUT, not a hardcoded path., A Bash tool_input carries `command`; the Grep-shape detection must not fire…, Feed a Grep-tool-shaped payload (pattern/path/glob, no command) to the guard., _run(), _run_grep_tool(), _search_matcher() (+14 more)

### Community 161 - "generate_section_flowchart"
Cohesion: 0.12
Nodes (22): generate_overview_graph(), generate_section_flowchart(), mermaid_class_defs(), mermaid_init(), mermaid_section_id(), node_kind(), node_label(), node_mermaid_id() (+14 more)

### Community 162 - "test_manifest_ingest.py"
Cohesion: 0.11
Nodes (33): _coerce_deps(), extract_package_manifest(), is_package_manifest_path(), _parse_apm(), _parse_cargo(), _parse_pyproject(), _pep508_name(), _pkg_id() (+25 more)

### Community 163 - "_pick_seeds"
Cohesion: 0.09
Nodes (22): _pick_seeds(), Select BFS seed nodes, stopping when score drops too far below the top.…, End-to-end for #1900: a German question over a graph with German heading-noise…, FooBarService at 1000 vs error nodes at 1.0 → only 1 seed chosen., When all scores are within 20% of the top, keep up to 3 seeds., Never return more than max_k seeds even when all scores are close., G/best_seed_by_term are optional and default to None: existing callers see…, Reproduces #1445: a vague natural-language query where one term's incidental… (+14 more)

### Community 164 - "edge_data"
Cohesion: 0.15
Nodes (31): edge_data(), Return one edge attribute dict for (u, v), tolerating MultiGraph. For…, _edge(), _extraction(), parametrize, A collapsed edge must keep the specific relation, not the alphabetical one.…, Deliberately NOT ranked against each other — `contains` vs `calls` is a cross-…, The fix chooses WHICH edge survives; it must not add or drop any. (+23 more)

### Community 165 - "Path"
Cohesion: 0.07
Nodes (31): _md_extract(), Path, `extension Foo` in a separate file from `class Foo` must resolve to a single…, _get_extractor should route .psd1 to extract_powershell_manifest., A '## heading' inside a fenced block must not produce a heading node (#1077).…, #3077: foo, foo!, foo?, and foo= must all survive extraction with distinct IDs., Write *src* to a temp .md file and extract it., Headings must be filterable. file_type is 'document' for both, so a consumer… (+23 more)

### Community 166 - "build"
Cohesion: 0.05
Nodes (53): build(), _coerce_non_string_ids(), _fold_node_aliases(), Merge multiple extraction results into one graph. directed=True produces a…, Fold legacy node field aliases onto canonical keys, in place (#2194). ``name``…, Coerce numeric node ids and edge/hyperedge references to str, in place (#2326).…, #1007: manifest stores absolute paths, graph nodes store relative paths.…, #1007: prune_sources with Windows-style backslash absolute paths must still… (+45 more)

### Community 167 - "test_python_decorators.py"
Cohesion: 0.26
Nodes (21): _class_nid(), _deco_edges(), _func_nid(), _method_nid(), Path, Regression tests: Python decorator references (#2154). Applying a Python…, Decorator-reference edge targets emitted from owner_nid., _stem() (+13 more)

### Community 168 - "graphify query "<question>" (CLI) / query_graph (MCP)"
Cohesion: 0.26
Nodes (21): graphify-out/GRAPH_REPORT.md, graphify benchmark (token reduction), graphify explain "<concept>" / get_node (MCP), graphify export falkordb (--falkordb / --falkordb-push), graphify export graphml (--graphml), graphify.serve MCP server (--mcp), graphify export neo4j (--neo4j / --neo4j-push), graphify path "<A>" "<B>" / shortest_path (MCP) (+13 more)

### Community 169 - "Graphify Skill Spec (Claude Code)"
Cohesion: 0.10
Nodes (21): AGENTS.md Always-On Routing Snippet, Antigravity Rules Always-On Snippet, CLAUDE.md Always-On Routing Snippet, GEMINI.md Always-On Routing Snippet, Kiro Steering Always-On Snippet, VS Code Copilot Instructions Always-On Snippet, Amp Adapter Skill, Claw Adapter Skill (+13 more)

### Community 170 - "generate_section_cards"
Cohesion: 0.12
Nodes (21): derive_flow_chain(), edge_score(), generate_section_cards(), node_degree_scores(), node_importance(), preferred_edges(), Counter, Aggregate inter-section edge counts and relation names. (+13 more)

### Community 171 - "_collision_rank"
Cohesion: 0.10
Nodes (21): _collision_rank(), _defines_id(), _id_prefixes(), _lifecycle_penalty(), Path, _rank_path(), The ID prefixes a node extracted from ``source_file`` may legitimately mint. An…, True when the node's own source_file is the file its ID encodes. A doc that… (+13 more)

### Community 172 - "extract_ocaml"
Cohesion: 0.21
Nodes (20): extract_ocaml(), Path, Extract modules, values, functions, types, variant constructors, `open`…, _labels(), Path, Tests for the OCaml extractor (graphify/extractors/ocaml.py)., A qualified call whose qualifier IS a module defined in this file still…, A qualified call `M.f` to an EXTERNAL module (not defined in this file) must… (+12 more)

### Community 173 - "save_query_result"
Cohesion: 0.15
Nodes (20): Save a Q&A result as markdown so it gets extracted into the graph on next…, save_query_result(), Tests for graphify.ingest.save_query_result, An outcome signal is written to both frontmatter (for `reflect`) and an ##…, Backward compatible: a result without an outcome looks exactly as before., test_answer_in_body(), test_correction_in_frontmatter_and_body(), test_file_created() (+12 more)

### Community 174 - "test_evidence_binding.py"
Cohesion: 0.17
Nodes (20): _bind_node_evidence(), _label_identifiers(), Identifier tokens from a node label, stripped of a trailing call/args…, Downgrade code-typed nodes whose symbol name has no evidence in the source the…, _by_label(), Tests for semantic evidence-binding in graphify.llm. A code node the model…, Drive extract_files_direct with a faked backend returning ``nodes``., _run() (+12 more)

### Community 175 - "test_csharp_partial_classes.py"
Cohesion: 0.19
Nodes (20): _extract(), _find(), _nodes_labeled(), C# partial classes split across files (#2332). `partial class Foo` declared in…, Nested partial types are excluded: their ids omit the enclosing type name, so…, Map each Widget class node -> set of member-method labels hanging off it., #2411: same fully-qualified name under TWO .csproj projects is two genuinely…, Adding a .csproj must not break the #2332 merge within one project. (+12 more)

### Community 176 - "_two_community_graph"
Cohesion: 0.10
Nodes (21): parametrize, Two disconnected components -> two stable communities, each hub-labelled by its…, #2853: relabeling a large graph must keep a current aggregated HTML., A skipped aggregate must not race with or falsely claim an HTML write., A failed render must not destroy the previous HTML file., An interruption after graph.json advances must remain repairable., A refused write must not erase retry state owned by an earlier run., A completed HTML replacement must remain a successful command. (+13 more)

### Community 177 - "test_settings_merge.py"
Cohesion: 0.21
Nodes (19): ALL_INSTALLERS, Path, Regression tests for issue #2167: hook installers must merge into existing…, A UTF-8 BOM must not trigger the parse-error path that used to clobber., An unparseable existing file must abort the install, byte-identical on disk., Valid JSON that is not an object (e.g. a list) must also refuse, not crash., A malformed hooks value (not a dict) refuses instead of raising/clobbering., A legacy non-dict entry in the managed section must not crash the filter (the… (+11 more)

### Community 178 - "convert_office_file"
Cohesion: 0.14
Nodes (19): convert_office_file(), Convert a .docx or .xlsx to a markdown sidecar in out_dir. Returns the path of…, The sidecar name must be identical whether the source path arrives in NFC or…, A second conversion of an unchanged source must not rewrite the sidecar, so its…, #2059: the sidecar name must depend on the scan-root-RELATIVE path, not the…, Two same-stem Office files in different subdirs must still get distinct sidecar…, A source outside the scan root (--include, custom layouts) falls back to the…, test_convert_office_file_does_not_rewrite_existing_sidecar() (+11 more)

### Community 179 - "sanitize_semantic_fragment"
Cohesion: 0.10
Nodes (20): Clean up a semantic extraction fragment in-place. Operations: 1. Removes nodes…, sanitize_semantic_fragment(), A node with file_type='rationale' is removed wholesale., Sentence-like rationale node connected via `rationale_for` → attribute on…, F3: a node with file_type='document' (allowed) that is BOTH sentence-like AND…, A short named node with a period (e.g. abbreviation) is NOT sentence-like., F4: hyperedges referencing removed nodes are repaired or dropped., A hyperedge referencing only nodes not present in the fragment is dropped. (+12 more)

### Community 180 - "test_query_names_its_graph.py"
Cohesion: 0.17
Nodes (19): _display_graph_path(), Render a graph path for the query header. Relative to the CWD when it sits…, _graph(), _header(), A query answer must say which graph it came from. `graphify-out/` resolves…, A display helper must not be the reason a query fails., The end-to-end point: the parent and the subproject must not look alike., The case the issue is about: the answer came from somewhere else. (+11 more)

### Community 181 - "typescript_advanced.ts"
Cohesion: 0.11
Nodes (13): Injectable, Module, DEFAULT_ROLES, IUserRepository, USER_CONFIG, USER_REPOSITORY, UserId, UserModule (+5 more)

### Community 182 - "test_cpp_objc_cross_file_calls.py"
Cohesion: 0.28
Nodes (19): _call_edges(), _label(), Path, Cross-file member-call and include resolution for C++ (#1547) and ObjC (#1556).…, {(source_label, relation, target_label, confidence)} for the given relations., The headline #1547 fix: a paired class no longer islands — Main.cpp's use of…, test_cpp_cross_file_member_call_connects_with_relative_paths(), test_cpp_godnode_guard_ambiguous_and_unknown_receiver() (+11 more)

### Community 183 - "test_go_builtin_call_targets.py"
Cohesion: 0.19
Nodes (19): builtin_shadow_repo(), _edges_between(), _extract_go(), _label(), _nodes_by_file(), Go predeclared functions must not bind to same-named user symbols.…, The guard is a no-op for genuine user symbols. Uses a plain package-level call:…, Same-file binding needs the guard too, not just the cross-file pass.… (+11 more)

### Community 184 - "test_incomplete_build_guard.py"
Cohesion: 0.18
Nodes (19): _arm_extract(), _arm_no_cluster(), _make_docs_corpus(), Tests for the incomplete-build shrink-guard on `graphify extract`. A full build…, #2169: an INCREMENTAL --no-cluster run merges the existing graph forward, so…, A present-but-unparseable existing graph.json (corrupt or mid-write) could be…, #2169: an incremental --no-cluster run must hard-fail on an unparseable…, Patch export.to_json to record the ``force`` it was called with and return a… (+11 more)

### Community 185 - "test_install_upgrade.py"
Cohesion: 0.15
Nodes (19): _assert_no_report_first(), _assert_query_first(), Installer-level regression tests for upgrade-in-place behavior (issue #580).…, The Claude install must also rewrite a stale .claude/settings.json hook payload…, Same upgrade behavior for AGENTS.md (Codex / OpenCode / Aider / Trae)., Same upgrade behavior for GEMINI.md., Same upgrade behavior for .github/copilot-instructions.md (VS Code)., Same upgrade behavior for .cursor/rules/graphify.mdc. The Cursor rule file is… (+11 more)

### Community 186 - "test_java_type_resolution.py"
Cohesion: 0.29
Nodes (19): _label_edges(), _node_by_id(), Path, test_java_ambiguous_implements_disambiguated_by_import(), test_java_ambiguous_reference_disambiguated_by_import(), test_java_builtin_library_types_not_emitted_as_references(), test_java_cross_file_constructor_call_resolves(), test_java_cross_file_implements_resolves_to_real_def() (+11 more)

### Community 187 - "_run"
Cohesion: 0.10
Nodes (20): CompletedProcess, argparse `choices` rejects an unknown outcome before save_query_result runs., --answer-file lets callers pass a long/multiline answer via a file instead of a…, Neither --answer nor --answer-file -> clean argparse error, not a crash., First run with no graphify-out/memory/ still succeeds and writes a valid doc., With a real graph.json present, reflect auto-detects it and groups lessons…, Through reflect()/CLI with a real graph.json: a cited node that isn't in the…, `reflect --if-stale` skips the rebuild when LESSONS.md is already current, and… (+12 more)

### Community 188 - "sample.php"
Cohesion: 0.14
Nodes (10): App\Auth\Authenticator, App\Cache\CacheManager, Authenticator, HasName, ApiClient, BaseProcessor, DataProcessor, Loggable (+2 more)

### Community 189 - "Reference: Extraction Spec (subagent prompt)"
Cohesion: 0.16
Nodes (19): graphify agents install (AGENTS.md Integration), graphify amp install (AGENTS.md Integration for Amp), graphify claude install (CLAUDE.md Integration), graphify hook install/uninstall/status (Post-Commit Hook), Issue #1392: PROJECT_ROOT vs .graphify_root scan dir / stdout JSON corruption, Commit Hook and CLAUDE.md Integration Reference (Windows Skill), Commit Hook and AGENTS.md Integration Reference (Agents Skill, Expected), Commit Hook and AGENTS.md Integration Reference (Amp Skill, Expected) (+11 more)

### Community 190 - "test_carried_hyperedge_remap.py"
Cohesion: 0.27
Nodes (12): _baseline(), _hyperedges(), Path, Carried-forward hyperedges must follow the dedup survivor remap (#3102).…, A graph written WITHOUT dedup, so the pair is still two nodes on disk and the…, The edge endpoint and the hyperedge member came from the same merged-away node;…, test_a_carried_hyperedge_is_remapped_onto_the_dedup_survivor(), test_a_hyperedge_re_emitted_by_the_new_chunk_is_not_duplicated() (+4 more)

### Community 191 - "test_inherited_field_receivers.py"
Cohesion: 0.16
Nodes (18): _bind_member_field_tables(), Bind the exported per-file field tables (#3151) to class node ids. Entries are…, _graph(), skipif, Fields declared on a superclass type receivers in a subclass (#3151). The…, A bare lowercase receiver with no known type must stay unresolved — only…, The issue's first repro: PBase declares the field, Pair extends it in the same…, The issue's second repro: `Direct.run` resolved, `Sub.run` did not — one call… (+10 more)

### Community 192 - "extract_dart"
Cohesion: 0.13
Nodes (11): extract_dart(), Path, Extract classes, mixins, functions, imports, generic calls, and annotations…, Test that the universal parser successfully extracts generic relationships,…, Test complex Dart 3+ syntax and precise Riverpod/Bloc mappings., Test that the parser successfully handles namespaces in extends/implements, and…, Test typedefs, mixin on, factories, constructor DI types, and universal…, Test all 5 roadmap bug fixes (Bug A, B, C, D, E). (+3 more)

### Community 193 - "_hooks_dir"
Cohesion: 0.12
Nodes (19): _hooks_dir(), Raise if a hooks path looks like a Windows absolute path (#1385). On POSIX/WSL…, Return the git hooks directory, respecting core.hooksPath if set (e.g. Husky).…, _reject_windows_path(), _append_duplicate_config_entries(), Path, A Windows-style core.hooksPath must raise (loud failure), not silently create a…, A legitimate POSIX core.hooksPath (Husky-style) must still install. (+11 more)

### Community 194 - "test_paths.py"
Cohesion: 0.16
Nodes (18): disambiguate_ambiguous_candidates(), _is_test_path(), _path_proximity_winner(), Classify a source path as a test path (case-insensitive, segment-aware). Shared…, Pick the candidate whose source file is closest to the call site.…, Resolve an ambiguous bare-name call to one candidate, or ``None``. Shared god-…, parametrize, Tests for graphify.paths — the shared test-path classifier (#1553). (+10 more)

### Community 195 - "test_cross_extension_reexport_self_cycle.py"
Cohesion: 0.23
Nodes (18): _node_id_by_label(), Path, Same-basename cross-extension re-exports must not collapse to a self-cycle…, With three same-basename siblings that all collapse to the base id ``foo``…, Building the byte-identical repo at two different absolute locations must yield…, The hint is emitted only on JS/TS-family edges, and those suffixes bypass the…, _reexport_like_edges(), test_build_drops_persisted_target_file_from_a_pre_fix_graph() (+10 more)

### Community 196 - "test_csharp_object_creation.py"
Cohesion: 0.26
Nodes (18): _extract(), _find(), C# `new Foo(...)` links the constructing method to Foo. The C# config only…, test_ambiguous_type_name_produces_no_edge(), test_argument_position_links_to_constructed_type(), test_cross_file_publisher_reaches_the_message_class(), test_explicitly_declared_local_links_to_constructed_type(), test_generic_construction_names_the_outer_type() (+10 more)

### Community 197 - "test_extract_cli.py"
Cohesion: 0.12
Nodes (18): _code_only_corpus(), Tests for `graphify extract` CLI dispatch path in graphify.__main__., Run 1 builds a graph where OTHER.md contributes two nodes. Run 2 changes only…, #2445: an AST-pass failure on a fresh build must not be presented as a…, Unit test for the #1897 helper: relative (fresh) and absolute (cache-hit)…, #1920: a doc whose only chunk output is a hyperedge (3+ nodes sharing a…, A corpus with only code — no docs/papers/images., A code-only corpus must run with no LLM API key. Regression: graphify extract… (+10 more)

### Community 198 - "_claude_artifacts"
Cohesion: 0.11
Nodes (19): _claude_artifacts(), The default code-corpus run must be fully described inside the core., No reference fragment may duplicate the core build pipeline., Every references/<name>.md the core points at is actually rendered., The query section heading is the lean-core stub; query.md re-homes the rest., claude renders exactly the eight on-demand fragments from the design., The fence-aware heading scanner must skip '#' lines inside code fences., Decision A: the file_type enum is the full six-value superset. (+11 more)

### Community 199 - "test_ts_inheritance.py"
Cohesion: 0.23
Nodes (18): _has_inherits(), Path, Regression tests for issue #1095: TypeScript inheritance capture. Two gaps on…, Regression guard: the originally-working imported-class case must stay., `class Dog extends Animal {}` in a plain .js file must emit an inherits edge.…, The JavaScript grammar path must retain import-guided resolution., A runtime base expression has no statically resolvable parent symbol., test_class_extends_same_file() (+10 more)

### Community 200 - "test_watch_manifest_location.py"
Cohesion: 0.13
Nodes (18): _corpus(), parametrize, Path, #2316: `graphify update <target>` must write manifest.json into the TARGET's…, The severe half of #2316: it is data loss, not just a misplaced file.…, #777/#1964 portability, broken here by the CWD-derived ``root=``.…, Same CWD-anchoring class as #2316, but it writes wrong data, not a wrong path.…, End of the chain: the point of the manifest is the next incremental run. A… (+10 more)

### Community 201 - "UserControl"
Cohesion: 0.14
Nodes (14): Email, RefreshCommand, ObservableObject, RelayCommand, Task, ToolkitViewModel, Email, RefreshCommand (+6 more)

### Community 202 - "PRInfo"
Cohesion: 0.22
Nodes (6): attach_graph_impact(), fetch_pr_files(), _load_graph_json(), PRInfo, Path, Fetch PR file lists concurrently, compute graph impact, return community labels.

### Community 203 - "Graph"
Cohesion: 0.21
Nodes (13): HashMap, Self, build_graph(), Graph, GraphEvent, GraphPair, Logger, String (+5 more)

### Community 204 - "sample.kt"
Cohesion: 0.14
Nodes (14): MutableList, ChatType, GROUP, NORMAL, SYSTEM, createClient(), T, BaseProcessor (+6 more)

### Community 205 - "TestSubprocessEncoding"
Cohesion: 0.07
Nodes (18): Regression tests for UnicodeEncodeError on Windows cp1252 console. On Windows…, Writing a file with → ✅ ≥ then passing its content through _call_claude_cli…, _call_llm with backend='claude-cli' must also use encoding='utf-8'., extract_corpus_parallel must surface chunk failures loudly — either via non-…, When chunks fail, extract_corpus_parallel must record failed_chunks > 0 in its…, A summary line must appear on stderr when ≥1 chunk fails., When all chunks succeed, failed_chunks must be 0 and no failure summary should…, Exercises the same code path as the rsl-siege-manager reproduction without… (+10 more)

### Community 206 - "test_indirect_call_external_import_shadow.py"
Cohesion: 0.22
Nodes (17): _extract_js_dir(), An import from outside the corpus must shadow indirect_call resolution.…, A `paths` entry pointing a package at its own installed copy resolves to a real…, The counter-test that bounds the fix: an import of a file INSIDE the corpus is…, Widening the shadow set must not blanket-suppress a file that also happens to…, The precise collision the fix must survive: a name that is BOTH imported…, Reported shape: an icon imported from a UI kit must not become a fabricated…, `import { Search as Find }` binds `Find` in this file, not `Search`. The shadow… (+9 more)

### Community 207 - "test_semantic_cache_out_root.py"
Cohesion: 0.14
Nodes (19): _count_cache_files(), Path, Regression tests for #1990 and #1991. #1990 — `graphify extract --out` saves…, When root=corpus and cache_root=out, source_file resolution must use corpus as…, Passing root=out_root (the old broken behaviour) silently writes 0 entries; the…, When cache_root is omitted, cache files still land under root (unchanged)., extract_corpus_parallel must accept a cache_root kwarg without raising (import…, Count .json files under a cache dir (recursively, excluding .tmp). (+11 more)

### Community 208 - "test_ts_decorators.py"
Cohesion: 0.30
Nodes (17): _class_nid(), _has_deco(), _method_nid(), Path, Regression tests: TypeScript/JavaScript decorator references. `@Component`,…, An external decorator (definition absent from the corpus — the common framework…, True if owner_nid references the (cross-file, bare-stub) decorator symbol., test_class_decorator_on_exported_class() (+9 more)

### Community 209 - "Window"
Cohesion: 0.15
Nodes (12): GraphifyDemo, RoutedEventArgs, RootPanel, SaveButton, UserNameBox, Window, UserName, MainWindow (+4 more)

### Community 210 - "cluster.py"
Cohesion: 0.23
Nodes (15): community_member_sigs(), label_communities_by_hub(), Community detection on NetworkX graphs. Uses Leiden (graspologic) if available,…, Deterministic, LLM-free community labels: name each community after its…, Per-community membership fingerprints: ``{cid: sha256(sorted member ids)}``.…, _g(), Deterministic, LLM-free community labels — `label_communities_by_hub`. Names…, test_absent_members_fall_back_to_placeholder() (+7 more)

### Community 211 - "extract_terraform"
Cohesion: 0.19
Nodes (17): extract_terraform(), Path, Extract Terraform/HCL blocks and the references between them via tree-sitter.…, Facade / registry identity guards for the per-language extractor split (#1212).…, _labels(), Path, Tests for the Terraform/HCL extractor (graphify/extract.py, issue #187)., _rel_pairs() (+9 more)

### Community 212 - "_platform_skill_destination"
Cohesion: 0.08
Nodes (36): _copy_skill_file(), _platform_skill_destination(), Copy a packaged skill file and write its version stamp. For progressive…, Return the skill destination for a platform and scope., _check_skill_version(), Path, Warn if the installed skill is from an older graphify version.…, Parse a version string into a comparable integer tuple (``0.9.2`` -> ``(0, 9,… (+28 more)

### Community 213 - "_detect_default_branch"
Cohesion: 0.27
Nodes (6): _detect_default_branch(), fetch_prs(), _gh(), Auto-detect the repo's default branch via gh, then git, then fall back to…, gh returns data but with no defaultBranchRef — should still fall back., TestDetectDefaultBranch

### Community 214 - "test_wiki_link_filename_parity.py"
Cohesion: 0.21
Nodes (16): Make a label safe for use as a filename across platforms AND as a markdown link…, _safe_filename(), test_wiki_safe_filename_honours_an_explicit_limit(), _assert_every_link_resolves(), parametrize, Regression tests for issue #2597: a wiki link's target must BE the on-disk…, _targets(), test_distinct_labels_collapsing_to_one_slug_stay_distinct() (+8 more)

### Community 215 - "main"
Cohesion: 0.12
Nodes (16): Namespace, The file_type enum is the six-value superset in every rendered artifact., The guard's line scanner flags 4- and 5-value pipe enums, not the superset., On a shallow checkout (no origin/v8) the validators skip with exit 0. CI sets…, test_git_show_validators_skip_cleanly_without_origin_v8(), test_schema_singleton_catches_legacy_enums(), test_schema_singleton_passes_across_all_platforms(), legacy_enum_lines() (+8 more)

### Community 216 - "test_java_member_calls.py"
Cohesion: 0.36
Nodes (16): _calls(), _find(), Path, Java receiver-typed member-call resolution. Java ``method_invocation`` nodes…, #3151: a field declared on the superclass now types `this.<field>` in the…, test_ambiguous_receiver_type_emits_no_edge(), test_explicit_type_receiver_resolves_to_owned_method(), test_field_receiver_resolves_to_declared_type() (+8 more)

### Community 217 - "test_merge_graphs_cli.py"
Cohesion: 0.24
Nodes (16): Path, `graphify merge-graphs` tolerates inputs that disagree on graph type (#1606).…, For a FIXED input order, the offset assignment must be deterministic: merging…, _run(), test_distinct_repo_tags_unit(), test_merge_graphs_carries_hyperedges_from_all_inputs(), test_merge_graphs_community_offset_is_byte_reproducible(), test_merge_graphs_hyperedges_dedup_on_shared_prefixed_id() (+8 more)

### Community 218 - "test_typescript_enum_members.py"
Cohesion: 0.32
Nodes (16): _extract(), _find(), _labels(), TypeScript enum members get a node and a `case_of` edge, like Java's (#1719).…, test_a_bare_member_becomes_a_node(), test_a_class_property_identifier_is_not_read_as_an_enum_member(), test_a_const_enum_emits_members(), test_a_quoted_member_uses_its_name_not_the_literal() (+8 more)

### Community 219 - "Window"
Cohesion: 0.14
Nodes (15): MoneyConverter, TaxConverter, Invoice.Tax, Order.Total, User.Name, ModeText, RootPanel, SaveButton (+7 more)

### Community 220 - "string"
Cohesion: 0.21
Nodes (8): double, Get-Data(), Process-Items(), string, Circle, DataProcessor, Shape, void

### Community 221 - "test_falkordb_integration.py"
Cohesion: 0.29
Nodes (7): _connect(), db(), Integration test for push_to_falkordb against a real FalkorDB instance. Runs…, Return a connected FalkorDB client, or skip if none is reachable. ``ping()``…, MERGE-based push is safe to re-run - counts must not grow., test_push_to_falkordb_creates_expected_graph(), test_push_to_falkordb_is_idempotent()

### Community 222 - "file_hash"
Cohesion: 0.07
Nodes (30): file_hash(), SHA256 of file contents + path relative to root. Uses a stat-based fastpath…, A .md file with no frontmatter is hashed by its full content., Non-.md files are still hashed by their full content., cached_files reports deep-namespace entries too., A same-length edit must change the digest even when the filesystem reports an…, The guard must not disable the cache: once a file's mtime tick has closed, the…, Editing content above a mid-document ``----`` break must change the hash --… (+22 more)

### Community 223 - "_stale_graph_sources"
Cohesion: 0.25
Nodes (15): Source files graph.json still references but the current scan no longer…, _stale_graph_sources(), #2210: incremental extract's graph-layer prune must not evict ALIVE files.…, Fail-closed: an alive in-root file missing from the corpus without provable…, (a) NFD spelling on disk vs NFC spelling in the graph: NOT stale., (b) fail-closed: a legacy bare-basename source_file whose file is alive at…, (c) a source_file with no file on disk anywhere IS pruned., #1909 must keep working: an alive file excluded by ignore rules is provably… (+7 more)

### Community 224 - "_is_regular_file"
Cohesion: 0.20
Nodes (15): _is_regular_file(), True only for regular files (symlinks followed). Named pipes, sockets and…, A repository may contain files that are not regular files. ``clone <github-…, The shape that hangs the whole run., A link to a FIFO blocks exactly like the FIFO, so stat must follow it., test_broken_symlink_is_rejected_without_raising(), test_char_device_is_rejected(), test_directory_named_like_a_source_file_is_rejected() (+7 more)

### Community 225 - "_make_scip_node_id"
Cohesion: 0.12
Nodes (16): _make_scip_node_id(), Derive a stable Graphify node ID from a SCIP symbol identifier. Uses SHA-1…, Symbol with # uses suffix after last #., Symbol without # uses the full symbol (sanitised) as suffix., Non-alphanumeric characters are replaced with underscores., Same inputs always produce the same id., Different source_file produces different hash., Different symbol produces different hash. (+8 more)

### Community 226 - "test_indirect_call_nested_closure_shadow.py"
Cohesion: 0.22
Nodes (15): _extract_js_dir(), Indirect-call argument shadowing across untracked JS/TS closures (#2241). An…, A const-assigned arrow IS separately tracked (its own caller_nid, own…, Blast-radius traversal must not include a caller that only reached the target…, The fix must hold on a warm-cache re-extraction, not just a cold run — the…, Reported shape (#2241): a one-letter test helper `r` must not become a…, The same nested-arrow shape must still capture a REAL by-name reference that is…, Shadowing must compound through two levels of untracked inline closures: an… (+7 more)

### Community 227 - "test_inferred_confidence_rubric.py"
Cohesion: 0.17
Nodes (13): _extract(), _inferred(), parametrize, Every INFERRED edge the AST extractor emits must carry a rubric score.…, The other half of the rubric must not drift while fixing this one., The fix is scoped to INFERRED; the other two tiers keep their values., 0.8 was the value in the tree and is not on the scale. Catch it and the…, A function passed by name as an argument — the indirect_call path. (+5 more)

### Community 228 - "test_objc_category_interfaces.py"
Cohesion: 0.26
Nodes (15): _calls(), _label(), _nodes_labelled(), Path, ObjC category / class-extension interfaces must fold into the base class…, Two unrelated `Thing` classes in different directories must not merge. The id…, {(source_label, target_label, confidence)} over `calls` edges., The headline case: `-useIt` declared in a category still resolves. Before,… (+7 more)

### Community 229 - "test_objc_property_ivar_receivers.py"
Cohesion: 0.33
Nodes (15): _call_edges(), _label(), Path, ObjC property/ivar receivers must type through the class's field table (#1556).…, The no-fabrication decoy: `[Foo.shared doIt]` next to a REAL class FooShared. A…, {(source_label, relation, target_label, confidence)} for the given relations., test_objc_ambiguous_field_type_emits_no_edge(), test_objc_dotted_class_receiver_fabricates_nothing() (+7 more)

### Community 230 - "test_agents_platform.py"
Cohesion: 0.10
Nodes (26): parametrize, Tests for the generic `agents` platform and its `skills` alias (#1432).…, `graphify uninstall --platform agents|skills` (global) clears ~/.agents/skills.…, `graphify uninstall --project` (no platform) removes the agents project skill…, `graphify install --project --platform agents` writes ./.agents/skills and…, `graphify agents install` is the amp-twin: skill at ~/.agents/skills PLUS a `##…, Running `graphify agents install` twice leaves a single AGENTS.md section., `graphify skills install`/`uninstall` behaves exactly like the agents form:… (+18 more)

### Community 231 - "test_type_only_import_cycles.py"
Cohesion: 0.23
Nodes (15): _cycles(), _extract(), _module_edges(), Type-only imports must not manufacture Import Cycles (#3123). `import type` /…, One runtime leg + one type-only leg: no runtime cycle exists., `import type from './x.js'` imports a value whose name is `type` — erased by…, `import { type B, C }` still imports C at runtime., test_a_cycle_with_one_type_only_leg_is_not_a_cycle() (+7 more)

### Community 232 - "test_uninstall_scope.py"
Cohesion: 0.19
Nodes (15): _plant_skill_tree(), parametrize, Path, Scope regression tests for the uninstall API trap (issue #2215).…, `graphify uninstall --project` (codebuddy branch) must not delete ~/.codebuddy…, Create <root>/<dot_dir>/skills/graphify/{SKILL.md, references/x.md,…, fn(project_dir) removes only the project skill tree (#2215 trap closed)., fn() with no args keeps the historical CLI behavior: global skill removed. (+7 more)

### Community 233 - "Platform"
Cohesion: 0.16
Nodes (14): _normalise(), Platform, One render unit parsed from platforms.toml., Resolve the rendered-name -> source-fragment map for this split platform., The prose file name the lean-core hooks pointer names for this host., Read a fragment file under fragments/, normalised to LF newlines., Force LF newlines and exactly one trailing newline., Render the YAML frontmatter from the platform's name and description. Only… (+6 more)

### Community 234 - "sample.json"
Cohesion: 0.13
Nodes (14): axios, react, dependencies, axios, react, devDependencies, typescript, name (+6 more)

### Community 235 - "AccountService"
Cohesion: 0.15
Nodes (7): delete, insert, update, AccountService, AccountStatus, Account, Notifiable

### Community 236 - "_extract_sql_or_skip"
Cohesion: 0.08
Nodes (25): _extract_sql_or_skip(), #2577: a name bound by WITH ... AS (...) is scoped to its statement, not a…, ALTER TABLE ... FOREIGN KEY ... REFERENCES produces a references edge., Schema-qualified table names (Schema.Table) are preserved., ALTER TABLE with schema-qualified names produces correct edges., PL/pgSQL bodies make tree-sitter-sql emit ERROR nodes; the functions must still…, A cleanly-parsed LANGUAGE sql function in the same file is emitted once., #2180: quoted identifiers must not defeat the ERROR-node name recovery.… (+17 more)

### Community 237 - "test_objc_field_table_remap.py"
Cohesion: 0.22
Nodes (14): Rewrite objc_field_types["tables"] KEYS through an id remap (#3150). The #2591…, _remap_objc_field_tables(), needs_objc, _calls(), The ObjC field->type table must survive the id remaps (#3150).…, The CLI shape: absolute inputs, common prefix stripped by the #1529 remap. This…, The shape the original #2591 tests used — must keep working., Warm-cache CLI run: the shard is written on the first pass and replayed on the… (+6 more)

### Community 238 - "_resolve_js_import_target"
Cohesion: 0.09
Nodes (24): _dynamic_import_js(), _find_body(), _find_require_call(), _js_collect_pattern_idents(), _js_extra_walk(), _js_import_binds_external(), _js_local_bound_names(), _js_member_assignment_target() (+16 more)

### Community 239 - "exceptions.py"
Cohesion: 0.12
Nodes (23): ConnectTimeout, DecodingError, HTTPError, PoolTimeout, ProtocolError, ProxyError, httpx-like exception hierarchy. All exceptions inherit from HTTPError at the…, An error occurred while issuing a request. (+15 more)

### Community 240 - "TDataProcessor"
Cohesion: 0.16
Nodes (7): IProcessor, TObject, SampleUnit, TBaseProcessor, TDataProcessor, Process(), Reset()

### Community 241 - "Path"
Cohesion: 0.14
Nodes (15): _graph_ids(), _portability_corpus(), Path, allowed_source_files=None must leave the result untouched (same contract as…, A corpus covering every id/path carrier a cache entry can hold. Deliberately…, Node ids + edge endpoint pairs — the granularity #2257 is about. Deliberately…, #2257: extract corpus under root A (populating the cache), copy the tree AND…, A relative ``root`` (what save_semantic_cache forwards) must not be used as an… (+7 more)

### Community 242 - "test_cross_repo_shared_types.py"
Cohesion: 0.28
Nodes (14): _merge(), Path, `merge-graphs` links a type declaration two repos share (#3007). Node ids are…, The join key is namespace+name, deliberately NOT structural. Two repos whose…, _run(), test_a_type_with_no_namespace_is_not_linked(), test_non_type_nodes_are_not_linked(), test_same_name_in_different_namespaces_is_not_linked() (+6 more)

### Community 243 - "test_csharp_call_site_generic_args.py"
Cohesion: 0.20
Nodes (14): _all_refs(), C# generic type arguments at CALL SITES. Properties, returns, and parameters…, A plain call site (no explicit type args) must not regress., End-to-end: the exact two-file repro from #2911 produces all six edges., Extract, returning {(source_label, target_label)} for `references` edges., Extract, returning [(source_label, target_label, context)] for every…, The Microsoft.Extensions.DependencyInjection shape that the issue calls out., _refs() (+6 more)

### Community 244 - "test_csharp_enum_members.py"
Cohesion: 0.32
Nodes (14): _extract(), _find(), _labels(), C# enum members get a node and a `case_of` edge, like Java's (#1719).…, test_a_member_is_not_a_method(), test_a_namespaced_enum_still_emits_members(), test_a_property_and_an_enum_member_sharing_a_name_stay_separate(), test_an_empty_enum_emits_no_members() (+6 more)

### Community 245 - "test_csharp_field_generic_args.py"
Cohesion: 0.21
Nodes (14): C# generic type arguments in FIELD position. The field_declaration handler read…, The non-generic path must be unchanged., Extract, returning {(source_label, target_label)} for `references` edges., A field and a property of the same type must produce the same references., `T item` must not create a node for the type parameter itself., _refs(), test_bare_type_parameter_is_not_fabricated(), test_field_generic_argument_produces_edge() (+6 more)

### Community 246 - "Specific Issues Found"
Cohesion: 0.08
Nodes (23): 1. Node/Edge Quality - Score: 6/10, 2. Edge Accuracy - Score: 5/10, 3. Community Quality - Score: 6/10, 4. Surprising Connections - Score: 4/10, 5. God Nodes - Score: 7/10, 6. Overall Usefulness - Score: 6/10, Additional Observations, Corpus size and density (+15 more)

### Community 247 - "test_merge_chunks_validation.py"
Cohesion: 0.27
Nodes (14): Tests that `graphify merge-chunks` validates untrusted subagent chunk JSON.…, A valid fragment may legitimately contain no entities; it still counts., _run_merge(), test_merge_chunks_accepts_synonym_file_type(), test_merge_chunks_accepts_unicode_id(), test_merge_chunks_accepts_valid_empty_chunk(), test_merge_chunks_fails_closed_on_unmatched_glob(), test_merge_chunks_fails_closed_when_every_chunk_is_invalid() (+6 more)

### Community 248 - "README.md"
Cohesion: 0.06
Nodes (46): AGENTS.md (repo), graphify dogfoods itself on its own repo, Confidence label system (ARCHITECTURE.md), Stages share no state, no side effects outside graphify-out/, Extraction pipeline (detect→extract→build→cluster→analyze→report→export), Discrete INFERRED confidence_score rubric (#2813), AST/semantic ghost-duplicate auto-merge (v0.8.33, #1145), Incremental --update root= fixes (#1361, #1392, #1366) (+38 more)

### Community 249 - "clear_cache"
Cohesion: 0.22
Nodes (13): clear_cache(), Delete all cache entries (ast/, semantic/, semantic-deep/, and legacy flat…, _count_by_ext(), _format_languages(), main(), Path, Run extraction, return (elapsed_seconds, node_count, edge_count)., Count files by extension. (+5 more)

### Community 250 - "README.he-IL.md"
Cohesion: 0.09
Nodes (22): אילו קבצים הוא מטפל, בחרו את הפלטפורמה שלכם, גרמו לעוזר שלכם להשתמש בגרף תמיד, דרישות מקדימות, הקמת סביבת פיתוח, הרצת בדיקות, התעלמות מקבצים, התקנה (+14 more)

### Community 251 - "wiki.py"
Cohesion: 0.26
Nodes (12): _community_article(), _cross_community_links(), _god_node_article(), _index_md(), _md_link(), Render a link to another wiki article as a portable relative markdown link.…, Return (community_label, edge_count) pairs for cross-community connections,…, A god-node article says when a relation group was cut (#3127).… (+4 more)

### Community 252 - "sample.sv"
Cohesion: 0.18
Nodes (12): leaf, math_pkg, leaf, Payload, BaseProcessor, Config, DataProcessor, build (+4 more)

### Community 253 - "test_csharp_member_nodes.py"
Cohesion: 0.35
Nodes (13): _extract(), _find(), _labels(), C# properties get a node, like C++ data members (#3006). `_CSHARP_CONFIG`…, test_a_backing_field_does_not_take_the_property_node(), test_a_field_alone_makes_no_member_node_but_keeps_its_type_reference(), test_a_generic_parameter_typed_property_still_gets_a_node(), test_a_primitive_property_still_gets_a_node() (+5 more)

### Community 254 - "test_extract_cache_location.py"
Cohesion: 0.24
Nodes (13): _make_corpus(), Path, #1774 — extract() must never write its AST cache into the analyzed source tree.…, The location/anchor split must keep content-hash keys anchored on the corpus…, The stat-index location is chosen once per process via a module global (#1747).…, Fresh-process regression for the stat-index leak specifically: even for a…, A second extract() of the same corpus must hit the CWD cache the first wrote —…, _reset_stat_index() (+5 more)

### Community 255 - "_run_extract"
Cohesion: 0.14
Nodes (14): #1939: cache-check --prompt-file only counts entries produced by that same…, #2927 end-to-end: a semantic extraction where a dispatched doc produces edges…, #2927 healing: a manifest poisoned BEFORE #2927 (carrying a live semantic_hash…, #1948 caller-side guard: an incremental run that only re-dispatches the CHANGED…, cache-check --mode deep consults cache/semantic-deep/; without the flag it…, #1925: `graphify extract --code-only` with a MISSING manifest.json must not…, _run_extract(), test_cache_check_mode_deep_reads_deep_namespace() (+6 more)

### Community 256 - "test_hollow_chunks_arm_shrink_guard.py"
Cohesion: 0.31
Nodes (13): _arm(), _corpus(), Hollow, unparseable and omitting chunks must count as incomplete (#3105). The…, The ordinary complete run is unchanged: a full build legitimately shrinks…, Refusal must leave the omitted files un-stamped so the next run retries them —…, After every retry a hollow chunk is returned (not raised) with its files marked…, _record_force(), _run() (+5 more)

### Community 257 - "test_indirect_call_arrow_single_param_shadow.py"
Cohesion: 0.25
Nodes (13): _extract_js_dir(), _indirect(), A single unparenthesised arrow parameter must shadow indirect_call args.…, The reported shape: a minified bundle's private `k` must not become a…, Control: the `parameters` path was already correct and must stay correct., `async x => …` is the same node with the same singular field., The parameter is scoped to its arrow: a same-named module callable referenced…, Widening the shadow set must not blanket-suppress inside arrows: an unshadowed… (+5 more)

### Community 258 - "test_indirect_call_catch_binding_shadow.py"
Cohesion: 0.25
Nodes (13): _extract_js_dir(), `catch (e)` bindings must shadow indirect_call args — inside the clause only.…, ES2019 `catch { }` is a real catch_clause with no `parameter` field — the…, Reported shape: a minified bundle's private `k` must not become a fabricated…, `catch ({ cause })` binds through the same field via a pattern — the…, The binding is scoped to the clause: a same-named module callable referenced…, Widening the shadow set must not blanket-suppress indirect_call inside a catch…, _rels() (+5 more)

### Community 259 - "_vault_extract"
Cohesion: 0.14
Nodes (14): Serial extract() anchored at *vault*, returning (node_ids, ref_edges, page-id…, A subfolder note's [[wikilink]] to a root-level doc resolves vault-wide when…, [[folder/name]] from a subfolder matches on the full segment suffix., On a bare-name collision the shallowest match wins — Obsidian resolves a bare…, An existing sibling target keeps lexical resolution — the fallback only fires…, Inline [text](missing.md) links get no vault fallback: a missing relative…, A wikilink typed in NFD finds a file named in NFC (and spaces survive):…, test_markdown_inline_link_keeps_relative_semantics() (+6 more)

### Community 260 - "test_node_id_canonical.py"
Cohesion: 0.27
Nodes (13): _assert_no_slug(), Path, Node-id / edge-endpoint canonicalization: no absolute-path (machine/temp slug)…, #2262: a .tsx component with a JSX-returning nested arrow component defined…, General invariant: extracting a mixed corpus (python module-level dispatch +…, #2231: a module-TOP-LEVEL dispatch table (`HANDLERS = {'a': handle_a}`) records…, #2243 (bash): `source ./b.sh` mints the target from the resolved absolute path.…, _real() (+5 more)

### Community 261 - "test_ts_namespace.py"
Cohesion: 0.30
Nodes (13): _has_node(), _node_label(), Path, Regression tests: TypeScript namespace/module container nodes. `namespace Foo…, The container node must not cost us the members the default recurse reached., The handler is TS-only; plain JS has no namespace syntax to confuse it., test_ambient_string_module_quotes_stripped(), test_module_keyword_is_node() (+5 more)

### Community 262 - "test_ts_receiver_member_calls.py"
Cohesion: 0.25
Nodes (13): _calls(), _cross_file_edges(), TS/JS receiver-typed member calls beyond `this.field` (#1630). The #1316…, Edges (any relation) whose source node lives in src_file and target in tgt_file., test_array_typed_receiver_emits_no_edge(), test_closure_over_typed_param_receiver(), test_genuinely_imported_type_still_resolves_inferred(), test_local_new_binding_receiver() (+5 more)

### Community 263 - "README.fa-IR.md"
Cohesion: 0.09
Nodes (21): اجرای تست‌ها, استفاده مستقیم از گراف, افزونه‌های اختیاری, انتخاب پلتفرم, بیشتر بدانید, تنظیمات تیمی, جریان کار Git, حریم خصوصی (+13 more)

### Community 264 - "Geometry"
Cohesion: 0.21
Nodes (11): Base, Base.Threads, Float64, LinearAlgebra, ParentModule, area(), describe(), Circle (+3 more)

### Community 265 - "sample.razor"
Cohesion: 0.15
Nodes (12): ComponentBase, CounterRecord, DataGrid, ICounterService, Microsoft.AspNetCore.Components, MyApp.Services, NavigationManager, route:/counter (+4 more)

### Community 266 - "geometry"
Cohesion: 0.22
Nodes (11): constants, geometry, double_val(), circle_area(), geometry, main, point, origin() (+3 more)

### Community 267 - "sample.go"
Cohesion: 0.26
Nodes (9): BaseProcessor, DataProcessor, Logger, Reader, ReaderLogger, Result, Server, main() (+1 more)

### Community 268 - "affected_nodes"
Cohesion: 0.15
Nodes (21): affected_nodes(), AffectedHit, _as_repo_relative(), _bare_name(), format_affected(), _format_location(), _node_label(), _normalize_label() (+13 more)

### Community 269 - "mcp_ingest.py"
Cohesion: 0.24
Nodes (12): _add_edge(), _add_node(), _detect_package_from_args(), _emit_server(), Any, mcp_ingest.py — Extract MCP (Model Context Protocol) server configuration…, Emit nodes/edges for one entry under ``mcpServers``., Return the first arg that looks like an npm or pypi package id, else None.… (+4 more)

### Community 270 - "DataProcessor"
Cohesion: 0.27
Nodes (8): List, HttpClient, DataProcessor, Owner, Workers, IProcessor, Processor, Result

### Community 271 - "Animal"
Cohesion: 0.21
Nodes (12): NSObject, NSString, SampleDelegate, Animal, -initWithName, -speak, <Base>, -baseMethod (+4 more)

### Community 272 - "sample.dmf"
Cohesion: 0.15
Nodes (12): elem "info" [CHILD], elem "infowindow" [MAIN], elem "map" [MAP], elem "mapwindow" [MAIN], elem "output" [OUTPUT], elem "outputwindow" [MAIN], elem "stat" [INFO], elem "statwindow" [MAIN] (+4 more)

### Community 273 - "ScopedCallsUnit"
Cohesion: 0.23
Nodes (12): TObject, ScopedCallsUnit, TBaseWidget, Prepare(), TDerivedWidget, Run(), TFirstWidget, Configure() (+4 more)

### Community 274 - "test_extraction_spec_ids.py"
Cohesion: 0.24
Nodes (12): _ast_symbol_id(), _examples(), parametrize, Path, Drift guard for the node-ID spec shown to LLM semantic subagents.…, Reproduce the symbol ID the AST extractor emits for a file + symbol, using the…, Guard the guard: if the spec moves or the example format changes so nothing…, The canonical spec warns against the filename-only and full-path ID forms. Lock… (+4 more)

### Community 275 - "test_objc_member_calls.py"
Cohesion: 0.28
Nodes (12): _edges(), _label(), Path, ObjC receiver typing must not treat a ``@protocol`` as a message receiver…, {(source_label, target_label, confidence)} for edges of one relation., No class named Reload exists, so `[Reload reload]` is untypable -> ZERO edges.…, A protocol and a class may share a name; the class must still resolve.…, The exclusion is scoped to receiver typing: adoption edges are unaffected. (+4 more)

### Community 276 - "test_query_cli.py"
Cohesion: 0.22
Nodes (12): Tests for graphify query CLI context filtering., #F4: query CLI must refuse to parse a graph.json that exceeds the cap., A single directed `calls` edge on an (on-disk) undirected graph.json, the…, `graphify query` must render `calls` edges caller->callee regardless of which…, Same edge, seeded from the caller side — must stay correct too., test_query_cli_explicit_context_filter(), test_query_cli_heuristic_context_filter(), test_query_cli_preserves_calls_direction_when_seeded_on_callee() (+4 more)

### Community 277 - "test_src_layout_import_resolution.py"
Cohesion: 0.20
Nodes (13): _resolve_python_module_path(), _import_edges(), Path, #2072: Python import resolution must not depend on the scan root. A src-layout…, A dotted-module id claimed by two different files (two src roots with the same…, #2072 review: the alias map is Python-only, but a non-Python import edge whose…, (relation, source, target) for import edges, present-endpoints only., Headline (#2072): the same project yields the same import edges whether scanned… (+5 more)

### Community 278 - "Always-On graphify Rules for AGENTS.md (Expected Output)"
Cohesion: 0.55
Nodes (12): GRAPH_REPORT.md, graphify explain Command, graphify path Command, graphify query Command, graphify update Command, graphify-out/wiki/index.md, Always-On graphify Rules for AGENTS.md (Expected Output), Always-On graphify Rules for Antigravity (Expected Output) (+4 more)

### Community 279 - "graphify hook (git post-commit hook)"
Cohesion: 0.32
Nodes (12): Native AGENTS.md Integration (Trae), Native CLAUDE.md Integration (graphify claude install), graphify hook (git post-commit hook), Opencode: Commit Hook & CLAUDE.md Integration Reference, Pi: Commit Hook & CLAUDE.md Integration Reference, Trae: Commit Hook & AGENTS.md Integration Reference, VS Code: Commit Hook & CLAUDE.md Integration Reference, graphify claude install (CLAUDE.md integration) (+4 more)

### Community 280 - "test_injection_sentinel_coverage.py"
Cohesion: 0.27
Nodes (11): _neutralise_injection_sentinels(), Defang known chat-template / jailbreak control tokens in untrusted text.…, Wrap one file's content in a labelled, hash-stamped untrusted-data block. The…, _wrap_untrusted(), parametrize, Every chat-template control token is defanged, not an enumerated few (#3183).…, test_a_llama3_turn_forgery_cannot_reach_the_model_intact(), test_case_variants_are_covered() (+3 more)

### Community 281 - "README.uk-UA.md"
Cohesion: 0.09
Nodes (21): Використання графу напряму, Вимоги, Вирішення проблем, Встановлення, Додаткові пакети (опціонально), Дізнатися більше, Запуск тестів, Змусьте асистента завжди використовувати граф (+13 more)

### Community 282 - "_communities_from_graph"
Cohesion: 0.18
Nodes (9): _communities_from_graph(), _GraphContextCache, Thread-safe graph contexts: one pinned default plus an LRU of projects., Build one entry for an already-resolved path and known file key.…, Return a fresh context, retaining project contexts by LRU order.…, Reconstruct community dict from community property stored on nodes., test_communities_from_graph_basic(), test_communities_from_graph_isolated() (+1 more)

### Community 283 - "barrel_reexport.ts"
Cohesion: 0.23
Nodes (5): LOCAL_CONST, readCookie(), writeCookie(), basePathRewrite(), getFullUrl()

### Community 284 - "test_architecture_doc.py"
Cohesion: 0.18
Nodes (11): _documented_symbols(), parametrize, ARCHITECTURE.md's module table must name symbols that actually exist (#2640).…, (module, function) for every function named in the module table., Guard the parser itself: a regex that silently matches nothing would make every…, `extract(path)` was documented for a function whose first parameter is a list;…, The omitted `root=` is the parameter whose absence yields non-canonical ids and…, test_architecture_documents_extract_as_taking_a_list() (+3 more)

### Community 285 - "extract_json"
Cohesion: 0.10
Nodes (21): extract_json(), _is_config_json(), Path, True if a .json file is a recognized config/manifest worth AST-extracting.…, Extract structure and dependency edges from a *config/manifest* .json file.…, A data-shaped .json (eval fixture / dataset) must NOT emit per-key nodes., A JSON file whose root is an array is data, never a config/manifest., tsconfig.json must still be AST-extracted even without telltale keys. (+13 more)

### Community 286 - "_inferred_uses"
Cohesion: 0.17
Nodes (12): _inferred_uses(), (source, target) pairs of every INFERRED cross-file `uses` edge., A cross-file INFERRED `uses` edge binds to the symbol that actually references…, Positive control: a class that genuinely uses the imported symbol still gets…, `from helpers import Helper as H` attributes via the local alias `H`, so a body…, Each symbol that references the import gets its own edge, and only those…, A reference at true module top level has no enclosing symbol to anchor on, so…, test_inferred_uses_edge_attributes_to_the_referencing_symbol() (+4 more)

### Community 287 - "test_indirect_dispatch_getattr.py"
Cohesion: 0.38
Nodes (11): _extract(), _ind(), Reflective dispatch via getattr string literals — #1566 slice 3. ``getattr(obj,…, test_dynamic_getattr_names_emit_nothing(), test_getattr_feeds_affected(), test_getattr_non_callable_name_emits_nothing(), test_getattr_string_literal_emits_indirect_call(), test_getattr_string_not_shadowed_by_param() (+3 more)

### Community 288 - "test_install_strings.py"
Cohesion: 0.17
Nodes (8): Regression tests for install-time instruction strings. These strings live in…, The fix demotes GRAPH_REPORT.md, it doesn't delete the reference. Most install…, All ten install surfaces must point the assistant at `graphify query` as the…, The pre-fix instructions told assistants to read GRAPH_REPORT.md as their first…, test_every_install_surface_recommends_graphify_query(), test_no_install_surface_demands_reading_the_full_report_first(), test_report_is_still_referenced_as_fallback(), test_skill_registration_uses_host_generic_instruction()

### Community 289 - "test_js_callback_calls.py"
Cohesion: 0.35
Nodes (11): _extract(), _indirect(), Calls inside a callback passed to a module-level call must not be dropped…, test_callback_body_call_is_not_double_counted(), test_callback_body_calls_are_captured(), test_callback_member_call_is_origin_gated(), test_multi_closure_direct_calls_still_captured(), test_own_closure_local_still_suppresses_indirect_call() (+3 more)

### Community 290 - "test_scala_self_type.py"
Cohesion: 0.38
Nodes (11): _build(), Scala self-type annotations (`self: Logging with Database =>`, `this: T =>`). A…, _rels(), test_affected_includes_self_type_dependents(), test_class_without_self_type_emits_no_requires_edge(), test_requires_edges_carry_no_context(), test_self_type_binder_only_emits_no_requires_edge(), test_self_type_coexists_with_unrelated_extends() (+3 more)

### Community 291 - "test_ts_generators.py"
Cohesion: 0.36
Nodes (11): _contains(), _has_node(), Path, Regression tests: TypeScript/JavaScript generator functions as nodes. Before…, A call inside a generator's body should be attributed to the generator, proving…, test_async_generator_declaration_is_node(), test_generator_body_calls_are_attributed(), test_generator_declaration_is_node_js() (+3 more)

### Community 292 - "test_ts_import_type_arguments.py"
Cohesion: 0.50
Nodes (11): _assert_silent(), _extract(), _labels(), Path, #3154: TypeScript `import(...)` types used in call-expression type arguments.…, test_ts_call_generic_controls_remain_clean(), test_ts_call_import_member_type_keeps_subsequent_declarations(), test_ts_call_import_types_source_locations_are_exact() (+3 more)

### Community 293 - "test_typescript_module_extensions.py"
Cohesion: 0.26
Nodes (7): _extract(), _labels(), Path, TypeScript module extensions (`.mts` / `.cts`) are treated as code. `.mts`…, test_cts_uses_the_typescript_grammar(), test_mts_uses_the_typescript_grammar(), test_uppercase_typescript_extensions_use_typescript_grammar()

### Community 294 - "Graphify Exports & Benchmark Reference (claude)"
Cohesion: 0.18
Nodes (12): Graphify Exports & Benchmark Reference (claude), FalkorDB Export (--falkordb / --falkordb-push) — rationale: prefer --falkordb-push because FalkorDB's GRAPH.QUERY runs one statement at a time, unlike Neo4j's cypher-shell bulk import, GraphML Export (graphify export graphml, --graphml), MCP Server Export (--mcp, graphify.serve, exposes query_graph/get_node/get_neighbors/get_community/god_nodes/graph_stats/shortest_path) — rationale: Claude Desktop config must use the absolute python interpreter path since it can't run $(...) and uv tool install's system python3 can't import graphify, Neo4j Export (--neo4j / --neo4j-push, Cypher, MERGE-idempotent), SVG Export (graphify export svg, --svg), Token Reduction Benchmark (graphify benchmark, gated on total_words > 5000) — rationale: below that threshold graph value is structural clarity, not token compression, Wiki Export (graphify export wiki, --wiki) (+4 more)

### Community 295 - "manifest.json"
Cohesion: 0.10
Nodes (20): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0001_initial_schema.py, hash, mtime, I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\config.py, hash, mtime, I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\__init__.py, hash (+12 more)

### Community 296 - "Demo.ViewModels"
Cohesion: 0.18
Nodes (6): Demo.ViewModels, PrismOrderViewModel, SettingsViewModel, UserControl, SettingsView, UserControl

### Community 297 - "/graphify add <url> Command"
Cohesion: 0.36
Nodes (11): /graphify add <url> Command, Opencode: Add-Watch Reference, Pi: Add-Watch Reference, Trae: Add-Watch Reference, VS Code: Add-Watch Reference, Windows: Add-Watch Reference, --watch Folder Watcher, --watch folder watcher (+3 more)

### Community 298 - "_bash_invokes_search"
Cohesion: 0.31
Nodes (10): _bash_invokes_search(), Whether a Bash command actually RUNS a search tool (#3121). The old test was a…, parametrize, The Bash search guard fires on executed commands, not on prose (#3121).…, test_a_heredoc_body_mentioning_search_tools_stays_quiet(), test_a_search_after_a_heredoc_still_fires(), test_an_unterminated_heredoc_cannot_fire_from_its_body(), test_prose_and_lookalikes_stay_quiet() (+2 more)

### Community 299 - "compute_pr_impact"
Cohesion: 0.35
Nodes (4): compute_pr_impact(), Return (communities_touched, nodes_affected) for a set of changed files. Builds…, 3 nodes across 2 communities, 2 distinct source files., TestComputePrImpact

### Community 300 - "parse_memory_doc"
Cohesion: 0.18
Nodes (11): parse_memory_doc(), Parse the frontmatter of a memory doc into a dict, or None if it has none.…, Reverse the double-quoted escaping that ingest._yaml_str applies., _yaml_unescape(), parse_memory_doc reads back exactly what save_query_result wrote, including an…, A plain markdown file with no frontmatter is skipped, not crashed on., save -> parse preserves tricky characters in the question, the correction, and…, test_parse_handles_crlf() (+3 more)

### Community 301 - "TMainForm"
Cohesion: 0.18
Nodes (5): TButton, TPanel, TMainForm, TMemo, TStatusBar

### Community 302 - "test_cjs_module_extension.py"
Cohesion: 0.22
Nodes (5): _extract(), _labels(), Path, CommonJS module extension (`.cjs`) is treated as code. `.cjs` is the explicit-…, test_cjs_extracts_like_js()

### Community 303 - "test_indirect_dispatch_assign_return.py"
Cohesion: 0.42
Nodes (10): _extract(), _ind(), Indirect dispatch via assignment + return references — #1566 slice 2. A…, test_assignment_and_return_emit_indirect_call(), test_assignment_feeds_affected(), test_local_shadow_emits_nothing(), test_module_level_assignment_emits_indirect_call(), test_multiple_assignment_emits_for_each() (+2 more)

### Community 304 - "test_kotlin_object_literal.py"
Cohesion: 0.45
Nodes (10): _edges(), _extract(), _find(), Kotlin anonymous-object members (#2347). `object : Foo { ... }` (node type…, Keep-the-bar: named `object` declarations and plain classes extract exactly as…, test_named_object_and_plain_class_unchanged(), test_object_literal_implements_supertype(), test_object_literal_member_calls_sibling_member() (+2 more)

### Community 305 - "test_partial_extraction_warning.py"
Cohesion: 0.31
Nodes (9): _partial_parse_fixture(), The partial-extraction warning must be actionable and must not misdirect. It…, A file the parser ACCEPTS only through ERROR recovery — an unclosed table…, The line number was the one actionable thing the old message had; it must…, _run(), test_a_clean_file_is_silent(), test_warning_carries_no_hardcoded_issue_number(), test_warning_names_the_file_and_how_much_survived() (+1 more)

### Community 306 - "test_pascal_call_scoping.py"
Cohesion: 0.47
Nodes (10): _class_node_id(), _extractors(), _has_call(), _method_node_id(), parametrize, Regression tests for scoped call resolution in the Pascal/Delphi extractor.…, test_calls_do_not_cross_unrelated_classes(), test_calls_resolve_via_ancestor_chain() (+2 more)

### Community 307 - "test_php_object_creation.py"
Cohesion: 0.29
Nodes (10): _extract(), PHP `new Foo(...)` links the constructing method to Foo (#3115).…, `$bus->dispatch(new Bar(2))` - construction as control flow., `new $cls()` names nothing; `new self()` / `new static()` name no OTHER class -…, test_cross_file_dispatcher_reaches_the_command_class(), test_dynamic_and_self_construction_produce_no_junk(), test_existing_static_call_edges_are_unchanged(), test_new_in_argument_position_links_the_message_bus_shape() (+2 more)

### Community 308 - "test_php_type_resolution.py"
Cohesion: 0.53
Nodes (10): _class_defs(), _node_by_id(), Path, test_php_ambiguous_base_disambiguated_by_use(), test_php_external_namespaced_base_does_not_collapse_onto_internal_class(), test_php_fully_qualified_base_resolves(), test_php_import_resolves_when_target_name_prefixes_sibling_classes(), test_php_plain_no_namespace_inheritance_preserved() (+2 more)

### Community 309 - "test_wheel_packaging.py"
Cohesion: 0.25
Nodes (10): _expected_artifacts(), _has_build(), parametrize, Path, Packaging guard (#1121 follow-up): the 5 skillgen guards check the *repo tree*,…, Every distinct skill body a platform installs (the SKILL.md is copied from one…, Every committed skill body + references/*.md (per host) + always_on/*.md block., _skill_bodies() (+2 more)

### Community 310 - "_inline_links"
Cohesion: 0.18
Nodes (11): _inline_links(), Yield (display, target) for each inline markdown link, skipping external URLs.…, Every inline markdown link target across the whole wiki must point at a file…, Labels with spaces, &, #, and parentheses must produce a link whose target IS…, A god node links its neighbours, but only communities and god nodes get article…, When two labels collide on disk and the second article gets a numeric suffix…, test_to_wiki_no_labels_uses_fallback(), test_wiki_links_resolve_to_real_files() (+3 more)

### Community 311 - "utils.py"
Cohesion: 0.11
Nodes (18): Invoke-Main(), build_url_with_params(), flatten_queryparams(), is_known_encoding(), normalize_header_key(), obfuscate_sensitive_headers(), parse_content_type(), primitive_value_to_str() (+10 more)

### Community 312 - "extract_csharp"
Cohesion: 0.11
Nodes (19): extract_csharp(), Extract C# type declarations, methods, namespaces, and usings from a .cs file., #2040 for C#: the nested type now gets a real `contains` edge from its…, _references(), test_csharp_call_edges_have_call_context(), test_csharp_field_type_references_have_field_context(), test_csharp_finds_class(), test_csharp_finds_interface() (+11 more)

### Community 313 - "compilerOptions"
Cohesion: 0.20
Nodes (9): src, @tsconfig/strictest/tsconfig.json, compilerOptions, module, outDir, strict, target, extends (+1 more)

### Community 314 - "extract_fortran"
Cohesion: 0.11
Nodes (19): _cpp_preprocess(), extract_fortran(), Path, Run cpp -w -P on a capital-F Fortran file and return preprocessed bytes. Falls…, Extract programs, modules, subroutines, functions, use statements, and calls…, `y = f(x)` function invocations must emit a calls edge. Function calls are…, test_fortran_capital_F_parses_preprocessed(), test_fortran_case_insensitive_names() (+11 more)

### Community 315 - "test_indirect_call_for_of_binding_shadow.py"
Cohesion: 0.33
Nodes (9): _extract_js_dir(), _indirect(), A `for...of` / `for...in` loop binding must shadow indirect_call references.…, The reported shape: a `for...of` binding `entry` used in an object-shorthand…, A destructured loop binding (`for (const { entry } of xs)`) must shadow the…, Widening the shadow set must not blanket-suppress: a same-named callable…, test_for_of_binding_does_not_fabricate_indirect_call(), test_for_of_destructuring_binding_shadows() (+1 more)

### Community 316 - "test_phantom_cross_package_call.py"
Cohesion: 0.56
Nodes (9): _calls(), Path, #1659 — a JS/TS call with no local definition and no import must not bind to a…, test_imported_cross_file_call_still_resolves(), test_many_files_do_not_collapse_onto_one_export(), test_non_js_single_candidate_cross_file_still_resolves(), test_same_file_call_unaffected(), test_unimported_cross_package_call_emits_no_edge() (+1 more)

### Community 317 - "test_python_import_resolution.py"
Cohesion: 0.56
Nodes (9): _has_edge(), _node_id(), Path, test_ordinary_relative_import_still_resolves(), test_overdeep_relative_import_is_unresolved_not_fatal(), test_python_package_reexport_resolves_import_and_call_to_origin_symbol(), test_python_parameter_return_and_generic_contexts(), test_relative_subpackage_import_from_targets_package_init() (+1 more)

### Community 318 - "monolith_roundtrip"
Cohesion: 0.20
Nodes (10): Each monolith is diff-clean vs v8 except the file_type enum unification., Every line that differs from pristine v8 is a sanctioned change-class. The…, test_monolith_roundtrip_passes_for_aider_and_devin(), test_monoliths_change_only_sanctioned_lines(), _is_sanctioned_monolith_diff(), _is_trigger_line(), monolith_roundtrip(), Whether a single added/removed monolith line is an allowed change. (+2 more)

### Community 319 - "render_always_on"
Cohesion: 0.24
Nodes (10): render_always_on yields exactly the six always-on instruction files., Each always_on/*.md reproduces its former __main__.py constant byte for byte.…, test_always_on_renders_six_blocks(), test_always_on_roundtrip_is_byte_faithful(), _always_on_constants(), always_on_roundtrip(), Parse the always-on string constants out of a __main__.py blob. Reads the…, Assert each always_on/*.md reproduces its former constant byte for byte. The… (+2 more)

### Community 320 - "test_ts_parse_warning.py"
Cohesion: 0.47
Nodes (9): _assert_silent(), _extract(), _labels(), #2610/#2599: the #2551 partial-parse warning must not fire on VALID TS/TSX.…, test_ts_generics_as_and_jsx_logical_and_are_silent(), test_ts_genuinely_broken_file_still_warns(), test_ts_interface_member_named_in_prefix_is_silent(), test_ts_midfile_breakage_warns_and_keeps_intact_functions() (+1 more)

### Community 321 - "Extra Exports and Benchmark Reference (Agents Skill, Expected)"
Cohesion: 0.42
Nodes (9): graphify benchmark Command, graphify export falkordb Command, graphify export graphml Command, graphify export neo4j Command, graphify export svg Command, graphify export wiki Command, graphify.serve MCP Server, Extra Exports and Benchmark Reference (Agents Skill, Expected) (+1 more)

### Community 322 - "sample.csproj"
Cohesion: 0.22
Nodes (6): net8.0, FluentValidation (11.9.0), MediatR (12.2.0), Microsoft.AspNetCore.Authentication.JwtBearer (8.0.0), Swashbuckle.AspNetCore (6.5.0), Microsoft.NET.Sdk.Web

### Community 323 - "graphify clone Command"
Cohesion: 0.56
Nodes (9): graphify clone Command, graphify merge-graphs Command, Opencode: GitHub Clone & Cross-Repo Merge Reference, Pi: GitHub Clone & Cross-Repo Merge Reference, Trae: GitHub Clone & Cross-Repo Merge Reference, VS Code: GitHub Clone & Cross-Repo Merge Reference, Trae reference: GitHub clone and cross-repo merge, VS Code reference: GitHub clone and cross-repo merge (+1 more)

### Community 324 - "extract_robot"
Cohesion: 0.17
Nodes (17): extract_robot(), _kw_id(), Path, Resolve a Settings-section import path relative to the importing file.…, Node ID for a keyword, normalized the way Robot Framework matches keyword…, Extract suites, test cases, user keywords, imports, and keyword calls from…, _resolve_robot_import(), _needs_robot (+9 more)

### Community 325 - "gemini_install"
Cohesion: 0.15
Nodes (16): gemini_install(), Idempotently update or append a graphify-owned section in shared files. If no…, Copy skill file, write GEMINI.md section, and install BeforeTool hook., _replace_or_append_section(), test_gemini_install_idempotent(), test_gemini_install_merges_existing_gemini_md(), test_gemini_install_writes_gemini_md(), test_gemini_install_writes_hook() (+8 more)

### Community 327 - "_shortest_path_text"
Cohesion: 0.32
Nodes (8): Body of the `shortest_path` MCP tool (module-level so tests can call it without…, _shortest_path_text(), _directed_chain(), DiGraph, alpha --calls--> beta --calls--> gamma, as _load_graph would load it (directed…, test_shortest_path_tool_directed_backwards_is_no_path(), test_shortest_path_tool_directed_respects_direction(), test_shortest_path_tool_undirected_opt_in()

### Community 328 - "conftest.py"
Cohesion: 0.22
Nodes (8): _can_symlink(), Any, pytest_collection_modifyitems(), Whether this machine can create symlinks at all (#2642). Probed rather than…, Skip a test that must create symlinks when the platform won't allow it. Take…, Every test gets a throwaway HOME so installers/uninstallers can never touch the…, requires_symlinks(), _sandbox_home()

### Community 329 - "dynamic_import.ts"
Cohesion: 0.31
Nodes (6): loadStatic(), pollMessages(), processInbound(), ./mayaEngine.js, ./queue.js, ./staticHelper

### Community 330 - "Widget"
Cohesion: 0.28
Nodes (4): Widget, -refresh, -render, String

### Community 331 - "TBaseGadget"
Cohesion: 0.28
Nodes (7): BaseGadget, TObject, TBaseGadget, Prepare(), DerivedGadget, TDerivedGadget, Run()

### Community 332 - "sample.scala"
Cohesion: 0.39
Nodes (7): BaseClient, HttpClientFactory, Int, String, Config, HttpClient, Loggable

### Community 333 - "sample_calls.py"
Cohesion: 0.39
Nodes (5): Analyzer, compute_score(), normalize(), Fixture: functions and methods that call each other - for call-graph extraction…, run_analysis()

### Community 334 - "test_cross_language_call_resolution.py"
Cohesion: 0.58
Nodes (8): _call_edges(), Path, Cross-language call resolution — a call in one language must never bind by name…, test_jvm_interop_kotlin_call_to_java_still_resolves(), test_python_call_does_not_bind_to_kotlin_function(), test_same_language_callback_still_resolves(), test_tsx_callback_does_not_bind_to_kotlin_method(), _write()

### Community 335 - "test_god_nodes_cli.py"
Cohesion: 0.47
Nodes (8): `graphify god-nodes` CLI subcommand (#2004 part 2). god_nodes has long been an…, _run(), test_god_nodes_cli_json(), test_god_nodes_cli_missing_graph_errors(), test_god_nodes_cli_text_output(), test_god_nodes_cli_top_limits(), test_god_nodes_cli_underscore_alias(), _write_graph()

### Community 336 - "test_import_self_loops.py"
Cohesion: 0.47
Nodes (8): _built_import_self_loops(), _import_self_loops(), parametrize, Path, test_python_external_import_matching_current_basename_has_no_self_loop(), test_recursive_call_self_loop_is_preserved(), test_rust_import_matching_current_basename_has_no_self_loop(), _write()

### Community 337 - "_many_communities"
Cohesion: 0.25
Nodes (9): _many_communities(), _peak_tracker(), Concurrency must not change the result: same cid->name map either way., ollama/claude-cli must stay serial regardless of --max-concurrency., test_label_communities_accumulates_token_usage(), test_label_communities_batch_size_controls_batch_count(), test_label_communities_forces_serial_for_ollama(), test_label_communities_parallel_matches_sequential() (+1 more)

### Community 338 - "generate"
Cohesion: 0.08
Nodes (45): _is_file_node(), Return True if this node is a file-level hub node (e.g. 'client', 'models') or…, generate(), _learning_section(), _portable_root_label(), Portable label for the report header — the project directory basename.…, Mirrors export.safe_name so community hub filenames and report wikilinks always…, Append the ``## Work-memory lessons`` section, or nothing when empty. (+37 more)

### Community 339 - "test_swift_computed_properties.py"
Cohesion: 0.47
Nodes (4): _labels(), Regression tests for #2181. Swift computed properties (`var body: some View { ……, _rel(), TestSwiftComputedProperties

### Community 340 - "test_ts_new_expression_calls.py"
Cohesion: 0.47
Nodes (8): _calls(), Path, TS/JS/TSX `new Foo(...)` constructor calls emit `calls` edges (#3116). In tree-…, test_js_new_expression_emits_calls_edge(), test_ts_member_new_expression_raw_calls(), test_ts_new_expression_emits_calls_edge_in_file(), test_ts_new_expression_resolves_cross_file(), test_tsx_new_expression_emits_calls_edge()

### Community 341 - "Shell: PowerShell Interpreter Detection"
Cohesion: 0.29
Nodes (8): graspologic ANSI escape sequences break PowerShell 5.1 scrolling, Issue #3028: PowerShell BOM breaks hook rebuild (WinError 123), Issue #831: uv/pipx-aware Python detection, PowerShell Scrolling Troubleshooting, Shell: Interpreter Guard (POSIX), Shell: Interpreter Guard (PowerShell), Shell: POSIX Interpreter Detection, Shell: PowerShell Interpreter Detection

### Community 342 - "saxpy"
Cohesion: 0.29
Nodes (7): constant, kernel, dot3(), device, saxpy(), Vec3, uint

### Community 343 - "semantic_cleanup.py"
Cohesion: 0.25
Nodes (7): _normalize_hyperedge_members(), Canonicalize a hyperedge's member list onto the `nodes` key, in place. If…, _append_rationale_attr(), _is_sentence_like_rationale_label(), Return True if *label* looks like prose / rationale text rather than an entity…, Append one or more rationale strings to *node*'s ``rationale`` attribute. If…, _validate_semantic_id()

### Community 344 - "first_present"
Cohesion: 0.29
Nodes (8): endpoint_id(), first_present(), normalize_edge(), normalize_node(), Return the first non-empty value for any candidate key., Normalize edge endpoints that may be strings or node-like objects., Normalize a graphify node across common graph.json schema variants., Normalize graphify edges while preserving original fields.

### Community 345 - "format_node_refs"
Cohesion: 0.25
Nodes (8): format_node_refs(), humanize_label(), node_display_name(), Readable node label for tables and summaries., Render node references as readable labels instead of internal IDs., Truncate without splitting Mermaid syntax., Convert graph labels into short labels people can scan in a diagram., truncate_text()

### Community 346 - "safe_file_path"
Cohesion: 0.25
Nodes (8): generate_section_intro(), group_nodes_by_file(), is_zh(), Group selected nodes by source file for Mermaid subgraphs., Generate the section introductory paragraph., Return a short, safe display path., Return true when localized strings should be Chinese., safe_file_path()

### Community 347 - "llm.py"
Cohesion: 0.04
Nodes (69): _anthropic_content(), _azure_client(), _backend_env_keys(), _backend_pkg_hint(), _balanced_object(), _bedrock_content(), _bedrock_inference_config(), _call_azure() (+61 more)

### Community 348 - "extract_go"
Cohesion: 0.11
Nodes (19): extract_go(), Path, Extract functions, methods, type declarations, and imports from a .go file., Methods on the same receiver type must share one canonical type node., Type node id should be scoped to directory, not file stem., test_go_receiver_methods_share_type_node(), test_go_receiver_uses_pkg_scope(), _edges_with_relation() (+11 more)

### Community 349 - "lessons_fresh"
Cohesion: 0.25
Nodes (8): lessons_fresh(), True if ``out_path`` exists and is at least as new as every input that feeds it…, parametrize, test_lessons_fresh_false_when_graph_newer(), test_lessons_fresh_false_when_graph_sidecar_newer(), test_lessons_fresh_false_when_memory_newer(), test_lessons_fresh_missing_output_is_not_fresh(), test_lessons_fresh_true_when_output_newer_than_inputs()

### Community 350 - "load_memory_docs"
Cohesion: 0.25
Nodes (8): load_memory_docs(), Parse every memory doc under ``memory_dir``, sorted by date then filename. Each…, Determinism hinges on this sort: docs come back oldest-first, filename as…, dead_ends/corrections are appended in doc order, so their determinism rides on…, test_dead_ends_and_corrections_follow_doc_order(), test_load_memory_docs_missing_dir_is_empty(), test_load_memory_docs_orders_by_date_then_filename(), test_load_memory_docs_skips_foreign_and_sorts()

### Community 351 - "load_validated_semantic_fragment"
Cohesion: 0.25
Nodes (8): load_validated_semantic_fragment(), Path, Load and validate a semantic chunk, rejecting oversize files before parsing.…, Invalid JSON returns an error instead of raising., Oversize files are rejected by stat() — payload is never parsed., test_load_validated_semantic_fragment_accepts_valid(), test_load_validated_semantic_fragment_rejects_invalid_json(), test_load_validated_semantic_fragment_rejects_oversize_before_parse()

### Community 352 - "Whisper-based Transcription (transcribe_all)"
Cohesion: 0.36
Nodes (8): Opencode: Transcribe Video/Audio Reference, Pi: Transcribe Video/Audio Reference, Trae: Transcribe Video/Audio Reference, VS Code: Transcribe Video/Audio Reference, Whisper-based Transcription (transcribe_all), Trae reference: transcribe video and audio, VS Code reference: transcribe video and audio, Windows reference: transcribe video and audio

### Community 353 - "gen_demo_path.py"
Cohesion: 0.29
Nodes (6): kt(), op0(), pairs of (keyTime, value) -> (values_str, keyTimes_str)., initial opacity for a revealable element (1 when baking a static frame)., opacity reveal at time t (s), hold, fade out before loop., reveal()

### Community 354 - "sample.zig"
Cohesion: 0.32
Nodes (6): add(), Color, multiply(), main(), Point, Shape

### Community 356 - "test_antigravity_install.py"
Cohesion: 0.25
Nodes (5): Antigravity install lays down its full always-on layer, not just the skill.…, The workflow must not hardcode a SKILL.md location. One constant serves both…, Global install shares the constant, so it must stay path-free too., test_antigravity_global_install_workflow_names_no_skill_path(), test_antigravity_workflow_names_no_skill_path()

### Community 357 - "test_case_sensitive_resolution.py"
Cohesion: 0.54
Nodes (7): _extract(), _labels(), Cross-file name resolution respects case in case-sensitive languages (#1581).…, test_case_sensitive_cross_file_ref_respects_case(), test_exact_case_cross_file_still_resolves(), test_php_case_insensitive_resolution_preserved(), test_python_Path_does_not_resolve_to_shell_PATH()

### Community 358 - "test_gemini_hook.py"
Cohesion: 0.33
Nodes (7): _env(), The Gemini CLI BeforeTool guard nudges toward the graph, shell-agnostically.…, _run(), test_allows_and_nudges_with_graph(), test_allows_without_nudge_when_no_graph(), test_matcher_and_command_shape(), test_never_blocks()

### Community 359 - "test_phantom_external_import.py"
Cohesion: 0.39
Nodes (7): Path, #1638 — an unresolved bare npm import must not alias onto an unrelated same-…, test_multiple_tsx_files_do_not_all_alias_onto_one_python_file(), test_no_phantom_edge_from_tsx_to_unrelated_python_file(), test_scoped_package_import_is_ref_namespaced(), test_unresolved_bare_import_is_ref_namespaced(), _write()

### Community 360 - "test_swift_builtin_noise.py"
Cohesion: 0.32
Nodes (7): _labels_by_id(), parametrize, Swift/Foundation/SwiftUI builtins must not become god nodes or bind to user…, Swift framework symbols must be filtered from god_nodes output. Constructs a…, test_god_nodes_excludes_swift_builtin_labels(), test_swift_builtin_receiver_does_not_bind_to_user_symbol(), test_swift_user_receiver_type_still_resolves()

### Community 361 - "test_swift_import_resolution.py"
Cohesion: 0.61
Nodes (7): _import_edges(), _module_nodes(), Path, test_swift_import_edges_survive_build(), test_swift_import_resolves_to_module_node(), test_swift_same_module_imported_twice_collapses_to_one_node(), _write()

### Community 362 - "Graphify GitHub Clone & Cross-Repo Merge Reference (claude)"
Cohesion: 0.29
Nodes (8): Graphify GitHub Clone & Cross-Repo Merge Reference (claude), Cross-Repo Graph Merge (graphify merge-graphs, nodes carry a repo attribute), GitHub Repo Clone (graphify clone, cached under ~/.graphify/repos/<owner>/<repo>), Monorepo Subfolder Merge (graphify extract per subfolder, then merge-graphs at project root) — rationale: the skill pipeline writes graphify-out/ to the cwd, so running the skill separately per subfolder clobbers the same output dir; the CLI's extract command instead nests graphify-out/ inside each scanned path, Graphify GitHub Clone & Cross-Repo Merge Reference (claw), Graphify GitHub Clone & Cross-Repo Merge Reference (codex), Graphify GitHub Clone & Cross-Repo Merge Reference (copilot), Graphify GitHub Clone & Cross-Repo Merge Reference (droid)

### Community 363 - "build_community_labels"
Cohesion: 0.43
Nodes (3): build_community_labels(), Return {community_id: [top_labels]} extracted from graph node data., TestBuildCommunityLabels

### Community 364 - "Foo"
Cohesion: 0.33
Nodes (3): Foo, bar, value

### Community 365 - "sample_php_listen.php"
Cohesion: 0.43
Nodes (6): EventServiceProvider, NotifyAdmins, OrderPlaced, SendWelcomeEmail, ShipOrder, UserRegistered

### Community 366 - "test_cpp_preprocess.py"
Cohesion: 0.38
Nodes (6): _capture_cpp_argv(), parametrize, The Fortran C-preprocessor path is hardened against argument injection (F5). A…, The guard only does work when the incoming path is RELATIVE. The test above…, test_cpp_preprocess_absolutises_a_relative_attacker_named_file(), test_cpp_preprocess_passes_absolute_path()

### Community 367 - "test_crossfile_identical_labels_stay_distinct_for_guarded_types"
Cohesion: 0.29
Nodes (7): parametrize, The node whose source_file is the file its ID encodes survives, whichever chunk…, Exact-ID dedup combines AST precision with semantic enrichment (#2091)., The #2182 fix is gated to high-entropy `concept` nodes with provenance on BOTH…, test_crossfile_identical_labels_stay_distinct_for_guarded_types(), test_defining_file_wins_over_referencing_file(), test_same_id_same_entity_retains_complementary_attributes()

### Community 368 - "test_home_sandbox.py"
Cohesion: 0.29
Nodes (3): Regression tests for the repo-wide HOME sandbox (issue #2168). The autouse…, Global skill deletes land inside the sandbox home, never the real one. Since…, test_global_uninstall_is_captured_by_sandbox()

### Community 369 - "extract_rust"
Cohesion: 0.13
Nodes (19): extract_rust(), Path, Extract functions, structs, enums, traits, impl methods, and use declarations…, _edge_labels(), _normalize_symbol_label(), Enum variant payload types must emit `references` edges. Tuple variants…, Tuple struct fields (`struct Wrapper(A, B);`) nest their positional types under…, test_go_embeds_struct_field() (+11 more)

### Community 370 - "BENCHMARKS.md"
Cohesion: 0.40
Nodes (5): ERPNext code-intelligence corpus, Benchmark fairness rules (shared model, judge validation), graphify benchmark harness (ingest→index→search→answer→grade), LOCOMO benchmark (n=300), LongMemEval-S benchmark (n=50)

### Community 371 - "_match_anchored_ignore_pattern"
Cohesion: 0.33
Nodes (6): _match_anchored_ignore_pattern(), _match_globstar_parts(), Recursive ``**``-aware segment match, memoized via an explicit dict. Lifted out…, Match an anchored gitignore pattern without letting ``*`` cross ``/``., `_match_anchored_ignore_pattern` must not leak a reference cycle per call, as…, test_globstar_matcher_leaves_no_reference_cycle()

### Community 372 - "_get_extractor"
Cohesion: 0.11
Nodes (18): _get_extractor(), Any, Return the correct extractor function for a file, or None if unsupported., Extensionless CLIs resolve their extractor from the shebang, mirroring…, test_extensionless_shebang_via_dispatch(), test_extensionless_without_usable_shebang_stays_unsupported(), test_extract_bash_via_dispatch(), test_extract_json_via_dispatch() (+10 more)

### Community 373 - "Cookies"
Cohesion: 0.12
Nodes (4): Cookies, Core data models: URL, Headers, Cookies, Request, Response. These are the…, Request, URL

### Community 374 - "sample.c"
Cohesion: 0.47
Nodes (5): Rectangle, main(), make_rect(), process(), validate()

### Community 375 - "Attention Is All You Need"
Cohesion: 0.33
Nodes (6): Attention Is All You Need Sample (Test Fixture), Attention Is All You Need, Feed-Forward Network, Layer Normalization, Multi-Head Attention, Transformer Architecture

### Community 376 - "sample.sh"
Cohesion: 0.53
Nodes (5): APP_ENV, build(), deploy(), sample.sh script, test_suite()

### Community 377 - "TSampleForm"
Cohesion: 0.33
Nodes (4): TPanel, TLabel, TSampleForm, TTimer

### Community 378 - "sample_php_container.php"
Cohesion: 0.67
Nodes (4): AppServiceProvider, CashierGateway, PaymentGateway, StripeGateway

### Community 379 - "SampleSpec"
Cohesion: 0.33
Nodes (4): SampleSpec, "should handle #input and return #expected", "should not change value when it's already correct", "should process valid input"

### Community 380 - "test_cli_broken_pipe.py"
Cohesion: 0.33
Nodes (5): CLI must not crash when a downstream reader closes the pipe early (#1807).…, `graphify --help | head -n1` must leave graphify exiting 0, not 255., A short, fully-buffered output (piped stdout is block-buffered) only flushes at…, test_help_survives_reader_closing_pipe_early(), test_small_buffered_output_survives_reader_that_reads_nothing()

### Community 381 - "extract_powershell_manifest"
Cohesion: 0.12
Nodes (17): extract_powershell_manifest(), Path, Extract module dependency edges from a PowerShell .psd1 manifest file. .psd1…, RootModule = 'MyModule.psm1' produces an imports_from edge to 'mymodule'., NestedModules = @('Helpers.psm1', 'Logger.psm1') produces edges for both., RequiredModules string form 'PSReadLine' produces an imports_from edge., RequiredModules hashtable form @{{ ModuleName='Pester' }} produces an…, ModuleVersion values ('5.0', '1.0.0') must NOT appear as import targets. (+9 more)

### Community 382 - "Graphify Commit Hook & CLAUDE.md Integration Reference (claude)"
Cohesion: 0.40
Nodes (6): Graphify Commit Hook & CLAUDE.md Integration Reference (claude), Native CLAUDE.md Integration (graphify claude install/uninstall) — makes graphify always-on in Claude Code sessions without manual /graphify, Post-Commit Hook (graphify hook install/uninstall/status) — rationale: no background process needed, triggers once per commit via git diff HEAD~1, works with any editor, Graphify Commit Hook & CLAUDE.md Integration Reference (claw), Graphify Commit Hook & CLAUDE.md Integration Reference (codex), Graphify Commit Hook & CLAUDE.md Integration Reference (copilot)

### Community 383 - "Graphify Add-URL & Watch Reference (claw)"
Cohesion: 0.40
Nodes (6): Graphify Add-URL & Watch Reference (claw), graphify add <url> (URL ingestion via graphify.ingest.ingest; supports YouTube/Twitter/arXiv/PDF/images/webpages), graphify --watch (background folder watcher, graphify.watch) — rationale: default 3s debounce waits for file activity to stop so a wave of parallel agent writes doesn't trigger a rebuild per file, Graphify Add-URL & Watch Reference (codex), Graphify Add-URL & Watch Reference (copilot), Graphify Add-URL & Watch Reference (droid)

### Community 384 - "graphify post-commit hook"
Cohesion: 0.33
Nodes (6): graphify hooks reference (droid), graphify CLAUDE.md integration, graph.json (graphify output artifact), GRAPH_REPORT.md (graphify output artifact), Rationale: post-commit hook needs no background process, triggers once per commit, works with any editor; doc/image changes ignored (require manual --update), graphify post-commit hook

### Community 385 - "graphify --watch folder watcher"
Cohesion: 0.47
Nodes (6): graphify add-watch reference (kilo), graphify add <url> ingestion, Rationale: 3s debounce prevents a wave of parallel agent writes from triggering a rebuild per file, Rationale: surface ingest errors to the user instead of silently continuing, graphify --update pipeline, graphify --watch folder watcher

### Community 386 - "graphify post-commit hook"
Cohesion: 0.33
Nodes (6): graphify hooks reference (kilo), graphify CLAUDE.md integration, graph.json (graphify output artifact), GRAPH_REPORT.md (graphify output artifact), Rationale: post-commit hook needs no background process, triggers once per commit, works with any editor; doc/image changes ignored (require manual --update), graphify post-commit hook

### Community 387 - "graphify --watch folder watcher"
Cohesion: 0.47
Nodes (6): graphify add-watch reference (kiro), graphify add <url> ingestion, Rationale: 3s debounce prevents a wave of parallel agent writes from triggering a rebuild per file, Rationale: surface ingest errors to the user instead of silently continuing, graphify --update pipeline, graphify --watch folder watcher

### Community 388 - "graphify post-commit hook"
Cohesion: 0.33
Nodes (6): graphify hooks reference (kiro), graphify CLAUDE.md integration, graph.json (graphify output artifact), GRAPH_REPORT.md (graphify output artifact), Rationale: post-commit hook needs no background process, triggers once per commit, works with any editor; doc/image changes ignored (require manual --update), graphify post-commit hook

### Community 389 - "graphify --watch folder watcher"
Cohesion: 0.47
Nodes (6): graphify add-watch reference (opencode), graphify add <url> ingestion, Rationale: 3s debounce prevents a wave of parallel agent writes from triggering a rebuild per file, Rationale: surface ingest errors to the user instead of silently continuing, graphify --update pipeline, graphify --watch folder watcher

### Community 390 - "graphify post-commit hook"
Cohesion: 0.33
Nodes (6): graphify hooks reference (opencode), graphify CLAUDE.md integration, graph.json (graphify output artifact), GRAPH_REPORT.md (graphify output artifact), Rationale: post-commit hook needs no background process, triggers once per commit, works with any editor; doc/image changes ignored (require manual --update), graphify post-commit hook

### Community 391 - "graphify --watch folder watcher"
Cohesion: 0.47
Nodes (6): graphify add-watch reference (pi), graphify add <url> ingestion, Rationale: 3s debounce prevents a wave of parallel agent writes from triggering a rebuild per file, Rationale: surface ingest errors to the user instead of silently continuing, graphify --update pipeline, graphify --watch folder watcher

### Community 392 - "graphify post-commit hook"
Cohesion: 0.33
Nodes (6): graphify hooks reference (pi), graphify CLAUDE.md integration, graph.json (graphify output artifact), GRAPH_REPORT.md (graphify output artifact), Rationale: post-commit hook needs no background process, triggers once per commit, works with any editor; doc/image changes ignored (require manual --update), graphify post-commit hook

### Community 393 - "GitHub Clone and Cross-Repo Merge Reference (Windows Skill)"
Cohesion: 0.80
Nodes (5): graphify clone Command, graphify merge-graphs Command, GitHub Clone and Cross-Repo Merge Reference (Windows Skill), GitHub Clone and Cross-Repo Merge Reference (Agents Skill, Expected), GitHub Clone and Cross-Repo Merge Reference (Amp Skill, Expected)

### Community 394 - "Add URL and Watch Folder Reference (Agents Skill, Expected)"
Cohesion: 0.80
Nodes (5): graphify.ingest.ingest Function, graphify --watch / graphify.watch Module, Add URL and Watch Folder Reference (Agents Skill, Expected), Add URL and Watch Folder Reference (Amp Skill, Expected), Add URL and Watch Folder Reference (Claude Skill, Expected)

### Community 395 - "Transcribe Video/Audio Reference (Windows Skill)"
Cohesion: 0.80
Nodes (5): graphify.transcribe.transcribe_all Function, Whisper-based Transcription, Transcribe Video/Audio Reference (Windows Skill), Transcribe Video/Audio Reference (Agents Skill, Expected), Transcribe Video/Audio Reference (Amp Skill, Expected)

### Community 396 - "SamplePackage"
Cohesion: 0.40
Nodes (5): FCL, LCL, sampleutils, sample, SamplePackage

### Community 397 - "CI workflow"
Cohesion: 0.40
Nodes (4): CI workflow, security-scan CI job (bandit, pip-audit), skillgen-check CI job, skillgen --check anti-drift hook

### Community 398 - "test_provider_registry.py"
Cohesion: 0.12
Nodes (16): A provider whose base_url uses a non-http(s) scheme is skipped on load (F1)., provider_base_url_ok rejects bad schemes and warns on plaintext-http egress…, Custom providers appear after all built-ins in detect_backend() priority., Missing pricing field defaults to zero so estimate_cost doesn't blow up., Built-in provider names are protected from being overridden., Full round-trip: add → list → show → remove via providers.json., A project-local ./.graphify/providers.json is NOT loaded by default (F1). It…, With explicit opt-in the project-local file is honoured (F1). (+8 more)

### Community 399 - "pascal_resolution.py"
Cohesion: 0.50
Nodes (4): _pascal_raw_calls(), Cross-file resolution for Pascal/Delphi calls to inherited methods. The per-…, Resolve Pascal/Delphi calls to a method inherited across file boundaries.…, resolve_pascal_inherited_calls()

### Community 400 - "test_semantic_similarity.py"
Cohesion: 0.18
Nodes (16): _make_extraction_with_semantic_edge(), _make_graph_with_semantic_edge(), _make_report_with_semantic_surprise(), _make_two_edge_graph(), Tests for semantically_similar_to edge support., Two nodes in separate files connected by a semantically_similar_to edge., Non-semantic edges must not get the [semantically similar] tag., Graph with one semantically_similar_to edge and one references edge, both… (+8 more)

### Community 401 - "QuranicWords Deploy Guide (Test Fixture)"
Cohesion: 0.40
Nodes (5): QuranicWords Deploy Guide (Test Fixture), Database Migration (Prisma ALTER TABLE), Docker-based Deploy (docker compose build), QuranicWords Backend, rollback(version) Function

### Community 402 - "TOtherGadget"
Cohesion: 0.40
Nodes (3): OtherGadget, TObject, TOtherGadget

### Community 403 - "sample_doctest.cpp"
Cohesion: 0.40
Nodes (3): "addition works", "handles \"quoted\" names", "subtraction works"

### Community 404 - "MyApp.Accounts.User"
Cohesion: 0.50
Nodes (3): MyApp.Accounts.User, create(), validate()

### Community 408 - "sample.sln"
Cohesion: 0.70
Nodes (3): Domain, WebApi, Tests

### Community 409 - "UserControl"
Cohesion: 0.40
Nodes (3): DesignViewModel, DesignView, UserControl

### Community 410 - "MainViewModel"
Cohesion: 0.40
Nodes (3): MainViewModel, MainWindow, Window

### Community 411 - "Graphify Transcribe Reference (claude)"
Cohesion: 0.40
Nodes (5): Graphify Transcribe Reference (claude), Whisper Video/Audio Transcription (graphify.transcribe.transcribe_all, domain-hint initial_prompt derived from god node labels) — rationale: the transcript JSON is written from Python (not a shell '>' redirect) because Whisper prints progress to stdout, which would corrupt a redirected JSON file (issue #1392), Graphify Transcribe Reference (claw), Graphify Transcribe Reference (codex), Graphify Transcribe Reference (copilot)

### Community 412 - "Dispatch fragment: parallel Agent tool dispatch (PowerShell paths)"
Cohesion: 0.50
Nodes (4): references/extraction-spec.md (subagent prompt spec), general-purpose subagent_type requirement, Parallel Agent tool dispatch pattern (single-message fan-out), Dispatch fragment: parallel Agent tool dispatch (PowerShell paths)

### Community 413 - "generate_header"
Cohesion: 0.50
Nodes (4): generate_header(), generate_nav(), Generate the sticky navigation bar., Generate the HTML header, title, subtitle, and nav.

### Community 414 - "Graphify Evaluation - Mixed Corpus (2026-04-04)"
Cohesion: 0.12
Nodes (16): 1. Corpus Detection, 2. AST Extraction (3 Python files), 3. Community Detection, 4. Query Tests (live BFS traversal), 5. Feedback Loop Test (answers filed back into library), 6. Arabic Image OCR (via Claude vision), 7. Issues Found, 8. Scores (+8 more)

### Community 415 - "test_file_label_disambiguation.py"
Cohesion: 0.18
Nodes (14): _disambiguate_file_node_labels(), Shortest trailing path suffix (basename + k parent dirs) of *sf* that is unique…, Relabel colliding-basename file nodes on a graph (#2032). Ids/edges are never…, _shortest_unique_suffix(), _file_node(), File-node labels are disambiguated when basenames collide (#2032). In…, The extract --no-cluster path writes the merged node dicts directly (bypassing…, Full pipeline: two entry-point index.ts files get distinguishable labels and… (+6 more)

### Community 416 - "graphify/extractors/ package"
Cohesion: 0.50
Nodes (4): _extract_generic shared core, extract.py monolith, graphify/extractors/ package, Extractor Migration Playbook

### Community 417 - "_community_label_lines"
Cohesion: 0.50
Nodes (4): _community_label_lines(), One prompt line per community (largest first), sampling up to ``top_k``…, The prompt line used to read "Community {cid}: ..." — the exact string of the…, test_label_prompt_lines_use_bare_cid_keys()

### Community 418 - "test_pipeline.py"
Cohesion: 0.23
Nodes (13): Path, End-to-end pipeline test: detect → extract → build → cluster → analyze → report…, Second run on unchanged corpus should produce identical node/edge counts., Run the full pipeline on the fixtures directory. Returns a dict of outputs., run_pipeline(), test_pipeline_all_nodes_have_community(), test_pipeline_detection_finds_code_and_docs(), test_pipeline_extraction_confidence_labels() (+5 more)

### Community 419 - "copilot skill: exports reference doc"
Cohesion: 0.83
Nodes (4): copilot skill: exports reference doc, Graph export formats (wiki/neo4j/falkordb/svg/graphml), graphify.serve stdio MCP server export, graphify benchmark token-reduction command

### Community 420 - "copilot skill: github-and-merge reference doc"
Cohesion: 0.83
Nodes (4): copilot skill: github-and-merge reference doc, graphify clone (GitHub repo clone), graphify merge-graphs (cross-repo/cross-folder merge), graphify extract per-subfolder (monorepo layout)

### Community 421 - "droid skill: exports reference doc"
Cohesion: 0.83
Nodes (4): droid skill: exports reference doc, Graph export formats (wiki/neo4j/falkordb/svg/graphml), graphify.serve stdio MCP server export, graphify benchmark token-reduction command

### Community 422 - "droid skill: github-and-merge reference doc"
Cohesion: 0.83
Nodes (4): droid skill: github-and-merge reference doc, graphify clone (GitHub repo clone), graphify merge-graphs (cross-repo/cross-folder merge), graphify extract per-subfolder (monorepo layout)

### Community 423 - "kilo skill: exports reference doc"
Cohesion: 0.83
Nodes (4): kilo skill: exports reference doc, Graph export formats (wiki/neo4j/falkordb/svg/graphml), graphify.serve stdio MCP server export, graphify benchmark token-reduction command

### Community 424 - "kilo skill: github-and-merge reference doc"
Cohesion: 0.83
Nodes (4): kilo skill: github-and-merge reference doc, graphify clone (GitHub repo clone), graphify merge-graphs (cross-repo/cross-folder merge), graphify extract per-subfolder (monorepo layout)

### Community 425 - "kiro skill: exports reference doc"
Cohesion: 0.83
Nodes (4): kiro skill: exports reference doc, Graph export formats (wiki/neo4j/falkordb/svg/graphml), graphify.serve stdio MCP server export, graphify benchmark token-reduction command

### Community 426 - "kiro skill: github-and-merge reference doc"
Cohesion: 0.83
Nodes (4): kiro skill: github-and-merge reference doc, graphify clone (GitHub repo clone), graphify merge-graphs (cross-repo/cross-folder merge), graphify extract per-subfolder (monorepo layout)

### Community 432 - "App"
Cohesion: 0.83
Nodes (3): App(), fmtCount(), fmtDate()

### Community 435 - "test_cli_help.py"
Cohesion: 0.50
Nodes (3): `graphify --help` must list user-facing commands that dispatch_command…, #3140: `graphify --help` must advertise prs, provider, and all export formats., test_help_lists_prs_provider_and_export_formats()

### Community 436 - "Communities"
Cohesion: 0.14
Nodes (13): Communities, Community 0 - "Community 0", Community 1 - "Community 1", Community 2 - "Community 2", Community 3 - "Community 3", Community 4 - "Community 4", Community 5 - "Community 5", Corpus Check (+5 more)

### Community 439 - "CLAUDE.md native graphify integration"
Cohesion: 1.00
Nodes (3): CLAUDE.md native graphify integration, Git post-commit hook auto-rebuild, codex skill: hooks reference doc

### Community 440 - "codex skill: transcribe reference doc"
Cohesion: 1.00
Nodes (3): codex skill: transcribe reference doc, LLM-composed Whisper domain-hint prompt, Whisper video/audio transcription (transcribe_all)

### Community 441 - "/graphify add <url> ingestion (ingest())"
Cohesion: 1.00
Nodes (3): /graphify add <url> ingestion (ingest()), copilot skill: add-watch reference doc, --watch background folder watcher (graphify.watch)

### Community 442 - "CLAUDE.md native graphify integration"
Cohesion: 1.00
Nodes (3): CLAUDE.md native graphify integration, Git post-commit hook auto-rebuild, copilot skill: hooks reference doc

### Community 443 - "copilot skill: transcribe reference doc"
Cohesion: 1.00
Nodes (3): copilot skill: transcribe reference doc, LLM-composed Whisper domain-hint prompt, Whisper video/audio transcription (transcribe_all)

### Community 444 - "/graphify add <url> ingestion (ingest())"
Cohesion: 1.00
Nodes (3): /graphify add <url> ingestion (ingest()), droid skill: add-watch reference doc, --watch background folder watcher (graphify.watch)

### Community 445 - "CLAUDE.md native graphify integration"
Cohesion: 1.00
Nodes (3): CLAUDE.md native graphify integration, Git post-commit hook auto-rebuild, droid skill: hooks reference doc

### Community 446 - "droid skill: transcribe reference doc"
Cohesion: 1.00
Nodes (3): droid skill: transcribe reference doc, LLM-composed Whisper domain-hint prompt, Whisper video/audio transcription (transcribe_all)

### Community 447 - "/graphify add <url> ingestion (ingest())"
Cohesion: 1.00
Nodes (3): /graphify add <url> ingestion (ingest()), kilo skill: add-watch reference doc, --watch background folder watcher (graphify.watch)

### Community 448 - "CLAUDE.md native graphify integration"
Cohesion: 1.00
Nodes (3): CLAUDE.md native graphify integration, Git post-commit hook auto-rebuild, kilo skill: hooks reference doc

### Community 449 - "kilo skill: transcribe reference doc"
Cohesion: 1.00
Nodes (3): kilo skill: transcribe reference doc, LLM-composed Whisper domain-hint prompt, Whisper video/audio transcription (transcribe_all)

### Community 450 - "/graphify add <url> ingestion (ingest())"
Cohesion: 1.00
Nodes (3): /graphify add <url> ingestion (ingest()), kiro skill: add-watch reference doc, --watch background folder watcher (graphify.watch)

### Community 451 - "CLAUDE.md native graphify integration"
Cohesion: 1.00
Nodes (3): CLAUDE.md native graphify integration, Git post-commit hook auto-rebuild, kiro skill: hooks reference doc

### Community 452 - "kiro skill: transcribe reference doc"
Cohesion: 1.00
Nodes (3): kiro skill: transcribe reference doc, LLM-composed Whisper domain-hint prompt, Whisper video/audio transcription (transcribe_all)

### Community 453 - "test_zig_enum_and_union_methods_are_extracted"
Cohesion: 0.67
Nodes (3): _needs_zig, Methods declared inside a Zig enum or tagged union must be captured. Only…, test_zig_enum_and_union_methods_are_extracted()

### Community 461 - "Benchmark: Karpathy Repos + Research Papers"
Cohesion: 0.14
Nodes (13): Benchmark: Karpathy Repos + Research Papers, Code-only (AST, no Claude), Communities detected (major), Full corpus (code + papers + images), God nodes (highest degree), Graph quality evaluation, Graph summary, Per-question breakdown (full corpus) (+5 more)

### Community 462 - "test_ingest_non_dict_input_returns_empty"
Cohesion: 0.67
Nodes (3): parametrize, Non-dict inputs are guarded and return empty nodes/edges., test_ingest_non_dict_input_returns_empty()

### Community 467 - "graphify"
Cohesion: 0.15
Nodes (13): `graph.json`을 LLM과 함께 사용하기, graphify, 개인정보 보호, 결과물, 기술 스택, 다음 계획, 동작 원리, 사용법 (+5 more)

### Community 525 - "Response"
Cohesion: 0.17
Nodes (3): HTTPStatusError, A 4xx or 5xx response was received., Response

### Community 526 - "Graph Report - worked/mixed-corpus/raw  (2026-04-05)"
Cohesion: 0.15
Nodes (12): Communities, Community 0 - "Community 0", Community 1 - "Community 1", Community 2 - "Community 2", Community 3 - "Community 3", Community 4 - "Community 4", Corpus Check, God Nodes (most connected - your core abstractions) (+4 more)

### Community 527 - "prompt_fingerprint"
Cohesion: 0.17
Nodes (12): prompt_fingerprint(), Return a short stable fingerprint of an extraction prompt. ``prompt`` is either…, The fingerprint is stable for identical prompts and differs when the prompt…, A CRLF checkout of the same spec must not look like a prompt change — otherwise…, Fingerprinted entries live under cache/semantic/p{fp}/, never flat., #2927 healing: a legacy on-disk cache entry containing edges but no nodes or…, #1920 / #2927: an existing on-disk cache entry with hyperedges but no nodes…, test_existing_hyperedge_only_cache_entry_remains_hit() (+4 more)

### Community 528 - "Case Study: rsl-siege-manager (Python + TypeScript monorepo)"
Cohesion: 0.17
Nodes (9): 1. Clone the corpus, 2. Install the CLI, 3. Run extraction, 4. Inspect, Case Study: rsl-siege-manager (Python + TypeScript monorepo), How to reproduce, Reference, What's in this directory (+1 more)

### Community 529 - "README.de-DE.md"
Cohesion: 0.18
Nodes (10): Assistenten immer den Graphen nutzen lassen (empfohlen), Auf graphify aufgebaut — Penpax, Datenschutz, Installation, Plattformunterstützung, So funktioniert es, Star-Verlauf, Tech-Stack (+2 more)

### Community 530 - "README.es-ES.md"
Cohesion: 0.18
Nodes (10): Construido sobre graphify — Penpax, Cómo funciona, Hacer que el asistente siempre use el grafo (recomendado), Historial de estrellas, Instalación, Privacidad, Qué obtienes, Soporte de plataformas (+2 more)

### Community 531 - "README.fr-FR.md"
Cohesion: 0.18
Nodes (10): Ce que vous obtenez, Comment ça fonctionne, Confidentialité, Construit sur graphify — Penpax, Historique des étoiles, Installation, Stack technique, Support des plateformes (+2 more)

### Community 532 - "graphify"
Cohesion: 0.18
Nodes (11): graphify, アシスタントに常にグラフを使わせる（推奨）, インストール, スター履歴, プライバシー, プラットフォームサポート, 仕組み, 使い方 (+3 more)

### Community 533 - "README.pt-BR.md"
Cohesion: 0.18
Nodes (10): Como funciona, Construído sobre graphify — Penpax, Fazer o assistente sempre usar o grafo (recomendado), Histórico de estrelas, Instalação, O que você obtém, Privacidade, Stack técnico (+2 more)

### Community 534 - "README.ru-RU.md"
Cohesion: 0.18
Nodes (10): Заставить ассистента всегда использовать граф (рекомендуется), Использование, История звёзд, Как это работает, Конфиденциальность, Поддержка платформ, Построено на graphify — Penpax, Технологический стек (+2 more)

### Community 535 - "README.uz-UZ.md"
Cohesion: 0.18
Nodes (10): Foydalanish, graphify ustida qurilgan — Penpax, Maxfiylik, Nima olasiz, O'rnatish, Platforma qo'llab-quvvatlash, Qanday ishlaydi, Texnologiyalar to'plami (+2 more)

### Community 536 - "README.ar-SA.md"
Cohesion: 0.20
Nodes (9): الاستخدام, التثبيت, الخصوصية, المكدس التقني, دعم المنصات, سجل النجوم, كيف يعمل, ما ستحصل عليه (+1 more)

### Community 537 - "graphify"
Cohesion: 0.20
Nodes (10): graphify, Worked examples, 你会得到什么, 安装, 工作原理, 平台支持, 技术栈, 用法 (+2 more)

### Community 538 - "NetworkError"
Cohesion: 0.20
Nodes (10): CloseError, ConnectError, NetworkError, A network error occurred., Failed to establish a connection., Failed to receive data from the network., Failed to send data through the network., Failed to close a connection. (+2 more)

### Community 539 - "README.hi-IN.md"
Cohesion: 0.22
Nodes (8): graphify पर बनाया — Penpax, Star इतिहास, आपको क्या मिलता है, इंस्टॉलेशन, उपयोग, गोपनीयता, प्लेटफॉर्म समर्थन, यह कैसे काम करता है

### Community 540 - "verilog.py"
Cohesion: 0.33
Nodes (7): _augment_systemverilog_semantics(), Verilog extractor. Moved verbatim from graphify/extract.py., First `simple_identifier` under node in pre-order, or None. tree-sitter-verilog…, _sv_collect_type_refs(), _sv_first_identifier(), _sv_split_type_list(), _sv_strip_comments()

### Community 541 - "Graph Report - .  (2026-05-13)"
Cohesion: 0.22
Nodes (9): Community Hubs (Navigation), Corpus Check, God Nodes (most connected - your core abstractions), Graph Freshness, Graph Report - .  (2026-05-13), Knowledge Gaps, Suggested Questions, Summary (+1 more)

### Community 542 - "Review: rsl-siege-manager"
Cohesion: 0.22
Nodes (9): Finding 1 — Test fixtures dominate "core abstractions" when tests are included, Finding 2 — Without tests, god nodes mix domain types with entry points and utilities, Finding 3 — Surprising connections cross language boundaries, Finding 4 — Community cohesion is uniformly low on this corpus, Finding 5 — Alembic migration docstrings surface as isolated nodes, Finding 6 — Suggested questions skew toward graph-property prompts, Review: rsl-siege-manager, Suggested follow-ups (+1 more)

### Community 543 - "_write_two_tier_graph"
Cohesion: 0.25
Nodes (8): A graph where docs/readme.md carries BOTH tiers (#2333 COEXIST): an AST layer…, #2333/#2336 (COEXIST): a semantic-only re-extract of a file replaces only that…, #2333/#2336 inverse: an AST-only re-extract of a file replaces only that file's…, #2333 raw-path mirror: merge_raw_extraction (extract --no-cluster incremental)…, test_build_merge_ast_reextract_preserves_semantic_layer(), test_build_merge_semantic_reextract_preserves_ast_layer(), test_merge_raw_extraction_tier_scoped(), _write_two_tier_graph()

### Community 544 - "_labels"
Cohesion: 0.25
Nodes (8): _labels(), test_go_finds_methods(), test_go_finds_struct(), test_rust_finds_impl_methods(), test_rust_finds_struct(), test_ts_finds_class(), test_ts_finds_function(), test_ts_finds_methods()

### Community 545 - "Graph Report - /home/safi/graphify-benchmark  (2026-04-04)"
Cohesion: 0.25
Nodes (7): Corpus Check, God Nodes (most connected - your core abstractions), Graph Report - /home/safi/graphify-benchmark  (2026-04-04), Knowledge Gaps, Suggested Questions, Summary, Surprising Connections (you probably didn't know these)

### Community 546 - "Corpus (52 files)"
Cohesion: 0.25
Nodes (7): Code — clone these 3 repos, Corpus (52 files), How to run, Images — save these 4, Karpathy Repos Benchmark, Papers — download these 5 PDFs, What to expect

### Community 547 - "README.da-DK.md"
Cohesion: 0.29
Nodes (6): Brug, Bygget på graphify — Penpax, Hvad du får, Installation, Privatliv, Sådan fungerer det

### Community 548 - "README.fil-PH.md"
Cohesion: 0.29
Nodes (6): Ano ang Makukuha Mo, Binuo sa ibabaw ng graphify — Penpax, Paano Gumagana, Pag-install, Paggamit, Privacy

### Community 549 - "README.hu-HU.md"
Cohesion: 0.29
Nodes (6): A graphify-ra épülve — Penpax, Adatvédelem, Használat, Hogyan működik, Mit kap, Telepítés

### Community 550 - "README.it-IT.md"
Cohesion: 0.29
Nodes (6): Come funziona, Cosa ottieni, Costruito su graphify — Penpax, Installazione, Privacy, Utilizzo

### Community 551 - "README.no-NO.md"
Cohesion: 0.29
Nodes (6): Bruk, Bygget på graphify — Penpax, Hva du får, Hvordan det fungerer, Installasjon, Personvern

### Community 552 - "README.pl-PL.md"
Cohesion: 0.29
Nodes (6): Co otrzymujesz, Instalacja, Jak to działa, Prywatność, Użycie, Zbudowane na graphify — Penpax

### Community 553 - "README.ro-RO.md"
Cohesion: 0.29
Nodes (6): Ce obțineți, Confidențialitate, Construit pe graphify — Penpax, Cum funcționează, Instalare, Utilizare

### Community 554 - "README.sv-SE.md"
Cohesion: 0.29
Nodes (6): Användning, Byggt på graphify — Penpax, Hur det fungerar, Installation, Integritet, Vad du får

### Community 555 - "README.th-TH.md"
Cohesion: 0.29
Nodes (6): การติดตั้ง, การใช้งาน, ความเป็นส่วนตัว, วิธีการทำงาน, สิ่งที่คุณได้รับ, สร้างบน graphify — Penpax

### Community 556 - "README.zh-TW.md"
Cohesion: 0.29
Nodes (6): 使用方式, 基於 graphify 構建 — Penpax, 安裝, 您會得到什麼, 運作原理, 隱私

### Community 557 - "_path_match"
Cohesion: 0.43
Nodes (3): _path_match(), True if graph_src and pr_file refer to the same file (path-boundary safe)., TestPathMatch

### Community 558 - "test_hyperedge_member_shapes.py"
Cohesion: 0.48
Nodes (6): _node(), Dict-shaped hyperedge member refs must never abort a build (#2486).…, test_dict_members_coerced_via_canonical_nodes_key(), test_dict_members_coerced_via_members_alias(), test_hyperedge_losing_all_members_is_dropped_not_fatal(), test_member_object_without_id_dropped_with_one_warning()

### Community 559 - "Research Notes"
Cohesion: 0.29
Nodes (6): On cross-reference detection, On keyword extraction, On storage, On the API layer, Open questions, Research Notes

### Community 561 - "_coerce_hyperedge_member_refs"
Cohesion: 0.33
Nodes (6): _coerce_hyperedge_member_refs(), _coerce_id(), _hashable(), Coerce a hyperedge member list to hashable scalar ids, deduped in order.…, Return a str for a numeric id, else the value unchanged. ``bool`` is excluded…, True when value can be a dict key / set member (same probe as the inline ``try:…

### Community 562 - "Document Pipeline Architecture"
Cohesion: 0.33
Nodes (5): Design decisions, Document Pipeline Architecture, Extending the pipeline, How data flows, Module responsibilities

### Community 563 - "Reproducible Example"
Cohesion: 0.33
Nodes (5): After it runs, How to run, Input files, Reproducible Example, What to expect

### Community 564 - "CookieConflict"
Cohesion: 0.40
Nodes (5): CookieConflict, InvalidURL, Exception, URL is improperly formed or cannot be parsed., Attempted to look up a cookie by name but multiple cookies exist.

### Community 565 - "httpx Corpus Benchmark"
Cohesion: 0.40
Nodes (4): Corpus (6 files), How to run, httpx Corpus Benchmark, What to expect

### Community 566 - "Mixed Corpus Benchmark"
Cohesion: 0.40
Nodes (4): Corpus (5 files), How to run, Mixed Corpus Benchmark, What to expect

### Community 567 - "_default_model_for_backend"
Cohesion: 0.50
Nodes (4): _default_model_for_backend(), Return configured model override or backend default model., Return (backend, model) using GRAPHIFY_TRIAGE_BACKEND or first available key., _resolve_triage_backend()

### Community 569 - "_call_pairs"
Cohesion: 0.50
Nodes (4): _call_pairs(), test_go_emits_calls(), test_rust_emits_calls(), test_ts_emits_calls()

### Community 570 - "test_mask_sql_comments_monotone_against_frozen_baseline"
Cohesion: 0.50
Nodes (4): _frozen_mask_2026_08_24(), Blank comment and string-literal spans, preserving every offset. One output…, Differential fuzz: the live mask must never EXPOSE a character the frozen…, test_mask_sql_comments_monotone_against_frozen_baseline()

### Community 571 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\env.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\env.py, hash, mtime

### Community 572 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0002_add_preview_columns.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0002_add_preview_columns.py, hash, mtime

### Community 573 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0003_make_siege_date_nullable.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0003_make_siege_date_nullable.py, hash, mtime

### Community 574 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0004_add_post_priority_config.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0004_add_post_priority_config.py, hash, mtime

### Community 575 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0005_add_description_to_post_priority_config.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0005_add_description_to_post_priority_config.py, hash, mtime

### Community 576 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0006_power_level_and_drop_sort_value.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0006_power_level_and_drop_sort_value.py, hash, mtime

### Community 577 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0007_fix_group_number_max.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0007_fix_group_number_max.py, hash, mtime

### Community 578 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0008_add_matched_condition_id_to_position.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0008_add_matched_condition_id_to_position.py, hash, mtime

### Community 579 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0009_add_discord_id_to_member.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0009_add_discord_id_to_member.py, hash, mtime

### Community 580 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0010_add_last_seen_changelog_at_to_member.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0010_add_last_seen_changelog_at_to_member.py, hash, mtime

### Community 581 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0011_add_post_suggest_preview.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\alembic\\versions\\0011_add_post_suggest_preview.py, hash, mtime

### Community 582 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\attack_day.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\attack_day.py, hash, mtime

### Community 583 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\auth.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\auth.py, hash, mtime

### Community 584 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\autofill.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\autofill.py, hash, mtime

### Community 585 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\board.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\board.py, hash, mtime

### Community 586 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\buildings.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\buildings.py, hash, mtime

### Community 587 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\changelog.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\changelog.py, hash, mtime

### Community 588 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\comparison.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\comparison.py, hash, mtime

### Community 589 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\discord_sync.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\discord_sync.py, hash, mtime

### Community 590 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\health.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\health.py, hash, mtime

### Community 591 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\images.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\images.py, hash, mtime

### Community 592 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\lifecycle.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\lifecycle.py, hash, mtime

### Community 593 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\members.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\members.py, hash, mtime

### Community 594 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\notifications.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\notifications.py, hash, mtime

### Community 595 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\post_priority_config.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\post_priority_config.py, hash, mtime

### Community 596 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\post_suggestions.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\post_suggestions.py, hash, mtime

### Community 597 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\posts.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\posts.py, hash, mtime

### Community 598 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\reference.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\reference.py, hash, mtime

### Community 599 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\siege_members.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\siege_members.py, hash, mtime

### Community 600 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\sieges.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\sieges.py, hash, mtime

### Community 601 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\validation.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\validation.py, hash, mtime

### Community 602 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\version.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\api\\version.py, hash, mtime

### Community 603 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\config.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\config.py, hash, mtime

### Community 604 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\db\\base.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\db\\base.py, hash, mtime

### Community 605 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\db\\__init__.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\db\\__init__.py, hash, mtime

### Community 606 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\db\\seeds.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\db\\seeds.py, hash, mtime

### Community 607 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\db\\session.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\db\\session.py, hash, mtime

### Community 608 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\dependencies\\auth.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\dependencies\\auth.py, hash, mtime

### Community 609 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\dependencies\\__init__.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\dependencies\\__init__.py, hash, mtime

### Community 610 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\__init__.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\__init__.py, hash, mtime

### Community 611 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\main.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\main.py, hash, mtime

### Community 612 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\middleware.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\middleware.py, hash, mtime

### Community 613 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\building_group.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\building_group.py, hash, mtime

### Community 614 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\building.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\building.py, hash, mtime

### Community 615 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\building_type_config.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\building_type_config.py, hash, mtime

### Community 616 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\enums.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\enums.py, hash, mtime

### Community 617 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\__init__.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\__init__.py, hash, mtime

### Community 618 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\member_post_preference.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\member_post_preference.py, hash, mtime

### Community 619 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\member.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\member.py, hash, mtime

### Community 620 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\notification_batch.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\notification_batch.py, hash, mtime

### Community 621 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\notification_batch_result.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\notification_batch_result.py, hash, mtime

### Community 622 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\position.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\position.py, hash, mtime

### Community 623 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\post_active_condition.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\post_active_condition.py, hash, mtime

### Community 624 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\post_condition.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\post_condition.py, hash, mtime

### Community 625 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\post_priority_config.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\post_priority_config.py, hash, mtime

### Community 626 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\post.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\post.py, hash, mtime

### Community 627 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\siege_member.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\siege_member.py, hash, mtime

### Community 628 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\siege.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\models\\siege.py, hash, mtime

### Community 629 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\rate_limit.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\rate_limit.py, hash, mtime

### Community 630 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\attack_day.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\attack_day.py, hash, mtime

### Community 631 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\autofill.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\autofill.py, hash, mtime

### Community 632 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\board.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\board.py, hash, mtime

### Community 633 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\building.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\building.py, hash, mtime

### Community 634 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\changelog.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\changelog.py, hash, mtime

### Community 635 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\common.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\common.py, hash, mtime

### Community 636 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\comparison.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\comparison.py, hash, mtime

### Community 637 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\__init__.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\__init__.py, hash, mtime

### Community 638 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\member.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\member.py, hash, mtime

### Community 639 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\post_condition.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\post_condition.py, hash, mtime

### Community 640 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\post.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\post.py, hash, mtime

### Community 641 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\post_suggestions.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\post_suggestions.py, hash, mtime

### Community 642 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\siege_member.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\siege_member.py, hash, mtime

### Community 643 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\siege.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\siege.py, hash, mtime

### Community 644 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\validation.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\validation.py, hash, mtime

### Community 645 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\version.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\schemas\\version.py, hash, mtime

### Community 646 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\attack_day.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\attack_day.py, hash, mtime

### Community 647 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\autofill.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\autofill.py, hash, mtime

### Community 648 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\board.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\board.py, hash, mtime

### Community 649 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\bot_client.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\bot_client.py, hash, mtime

### Community 650 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\building_capacity.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\building_capacity.py, hash, mtime

### Community 651 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\buildings.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\buildings.py, hash, mtime

### Community 652 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\comparison.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\comparison.py, hash, mtime

### Community 653 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\discord_sync.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\discord_sync.py, hash, mtime

### Community 654 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\image_gen.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\image_gen.py, hash, mtime

### Community 655 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\lifecycle.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\lifecycle.py, hash, mtime

### Community 656 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\members.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\members.py, hash, mtime

### Community 657 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\notification_message.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\notification_message.py, hash, mtime

### Community 658 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\post_suggestions.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\post_suggestions.py, hash, mtime

### Community 659 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\posts.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\posts.py, hash, mtime

### Community 660 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\reference.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\reference.py, hash, mtime

### Community 661 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\siege_members.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\siege_members.py, hash, mtime

### Community 662 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\sieges.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\sieges.py, hash, mtime

### Community 663 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\validation.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\services\\validation.py, hash, mtime

### Community 664 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\telemetry.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\app\\telemetry.py, hash, mtime

### Community 665 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\scripts\\seed_demo.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\scripts\\seed_demo.py, hash, mtime

### Community 666 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\scripts\\seed.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\scripts\\seed.py, hash, mtime

### Community 667 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\conftest.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\conftest.py, hash, mtime

### Community 668 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\__init__.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\__init__.py, hash, mtime

### Community 669 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_attack_day.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_attack_day.py, hash, mtime

### Community 670 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_auth.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_auth.py, hash, mtime

### Community 671 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_auth_rate_limit.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_auth_rate_limit.py, hash, mtime

### Community 672 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_autofill.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_autofill.py, hash, mtime

### Community 673 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_board.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_board.py, hash, mtime

### Community 674 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_bot_client.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_bot_client.py, hash, mtime

### Community 675 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_buildings.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_buildings.py, hash, mtime

### Community 676 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_changelog.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_changelog.py, hash, mtime

### Community 677 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_comparison.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_comparison.py, hash, mtime

### Community 678 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_config_endpoint.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_config_endpoint.py, hash, mtime

### Community 679 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_config.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_config.py, hash, mtime

### Community 680 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_cors.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_cors.py, hash, mtime

### Community 681 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_discord_sync.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_discord_sync.py, hash, mtime

### Community 682 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_enums.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_enums.py, hash, mtime

### Community 683 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_health.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_health.py, hash, mtime

### Community 684 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_image_gen.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_image_gen.py, hash, mtime

### Community 685 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_lifecycle_integration.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_lifecycle_integration.py, hash, mtime

### Community 686 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_lifecycle.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_lifecycle.py, hash, mtime

### Community 687 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_member_changelog_column.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_member_changelog_column.py, hash, mtime

### Community 688 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_members.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_members.py, hash, mtime

### Community 689 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_notification_message.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_notification_message.py, hash, mtime

### Community 690 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_notifications.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_notifications.py, hash, mtime

### Community 691 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_post_suggestions_integration.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_post_suggestions_integration.py, hash, mtime

### Community 692 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_post_suggestions.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_post_suggestions.py, hash, mtime

### Community 693 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_posts.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_posts.py, hash, mtime

### Community 694 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_reference.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_reference.py, hash, mtime

### Community 695 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_schema.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_schema.py, hash, mtime

### Community 696 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_seed_canonical.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_seed_canonical.py, hash, mtime

### Community 697 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_seed_demo.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_seed_demo.py, hash, mtime

### Community 698 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_sieges.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_sieges.py, hash, mtime

### Community 699 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_telemetry.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_telemetry.py, hash, mtime

### Community 700 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_validation.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_validation.py, hash, mtime

### Community 701 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_version.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\backend\\tests\\test_version.py, hash, mtime

### Community 702 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\config.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\config.py, hash, mtime

### Community 703 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\discord_client.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\discord_client.py, hash, mtime

### Community 704 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\http_api.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\http_api.py, hash, mtime

### Community 705 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\__init__.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\__init__.py, hash, mtime

### Community 706 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\telemetry.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\app\\telemetry.py, hash, mtime

### Community 707 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\conftest.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\conftest.py, hash, mtime

### Community 708 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\__init__.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\__init__.py, hash, mtime

### Community 709 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\test_discord_client.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\test_discord_client.py, hash, mtime

### Community 710 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\test_get_guild_member.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\test_get_guild_member.py, hash, mtime

### Community 711 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\test_http_api.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\test_http_api.py, hash, mtime

### Community 712 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\test_telemetry.py"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\bot\\tests\\test_telemetry.py, hash, mtime

### Community 713 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\e2e\\board.spec.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\e2e\\board.spec.ts, hash, mtime

### Community 714 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\e2e\\siege-lifecycle.spec.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\e2e\\siege-lifecycle.spec.ts, hash, mtime

### Community 715 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\e2e\\smoke.spec.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\e2e\\smoke.spec.ts, hash, mtime

### Community 716 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\eslint.config.js"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\eslint.config.js, hash, mtime

### Community 717 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\playwright.config.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\playwright.config.ts, hash, mtime

### Community 718 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\postcss.config.js"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\postcss.config.js, hash, mtime

### Community 719 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\board.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\board.ts, hash, mtime

### Community 720 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\changelog.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\changelog.ts, hash, mtime

### Community 721 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\client.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\client.ts, hash, mtime

### Community 722 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\config.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\config.ts, hash, mtime

### Community 723 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\members.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\members.ts, hash, mtime

### Community 724 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\notifications.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\api\\notifications.ts, hash, mtime

### Community 725 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\App.tsx"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\App.tsx, hash, mtime

### Community 726 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\main.tsx"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\main.tsx, hash, mtime

### Community 727 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\vite-env.d.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\src\\vite-env.d.ts, hash, mtime

### Community 728 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\tailwind.config.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\tailwind.config.ts, hash, mtime

### Community 729 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\vite.config.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\vite.config.ts, hash, mtime

### Community 730 - "I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\vitest.config.ts"
Cohesion: 0.67
Nodes (3): I:\\games\\raid\\siege-web\\.worktrees\\experiment-graphify-dry-run-doc\\frontend\\vitest.config.ts, hash, mtime

## Ambiguous Edges - Review These
- `ingest()` → `Opencode: Add-Watch Reference`  [AMBIGUOUS]
  graphify/skills/opencode/references/add-watch.md · relation: references
- `serve.py` → `Opencode: Exports & Benchmark Reference`  [AMBIGUOUS]
  graphify/skills/opencode/references/exports.md · relation: references
- `transcribe_all()` → `Opencode: Transcribe Video/Audio Reference`  [AMBIGUOUS]
  graphify/skills/opencode/references/transcribe.md · relation: references
- `watch.py` → `Opencode: Add-Watch Reference`  [AMBIGUOUS]
  graphify/skills/opencode/references/add-watch.md · relation: references
- `graphify Step 3B semantic subagent dispatch` → `graphify Whisper video/audio transcription`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__droid__references__transcribe.md · relation: references
- `graphify Step 3B semantic subagent dispatch` → `graphify Whisper video/audio transcription`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__kilo__references__transcribe.md · relation: references
- `graphify Step 3B semantic subagent dispatch` → `graphify Whisper video/audio transcription`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__kiro__references__transcribe.md · relation: references
- `graphify Step 3B semantic subagent dispatch` → `graphify Whisper video/audio transcription`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__opencode__references__transcribe.md · relation: references
- `graphify Step 3B semantic subagent dispatch` → `graphify Whisper video/audio transcription`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__pi__references__transcribe.md · relation: references
- `graphify merge-graphs` → `graphify query command`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__kilo__references__github-and-merge.md · relation: references
- `graphify merge-graphs` → `graphify query command`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__kiro__references__github-and-merge.md · relation: references
- `graphify merge-graphs` → `graphify query command`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__opencode__references__github-and-merge.md · relation: references
- `graphify merge-graphs` → `graphify query command`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__pi__references__github-and-merge.md · relation: references
- `Dispatch: Agent Tool (Disk-based)` → `Kilo-Specific Rules`  [AMBIGUOUS]
  tools/skillgen/fragments/extra/kilo-rules.md · relation: conceptually_related_to
- `graphify/command-kilo.md` → `graphify/skill-agents.md`  [AMBIGUOUS]
  graphify/command-kilo.md · relation: references
- `graph.json (graphify output artifact)` → `graphify post-commit hook`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__droid__references__hooks.md · relation: references
- `GRAPH_REPORT.md (graphify output artifact)` → `graphify post-commit hook`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__droid__references__hooks.md · relation: references
- `graphify --update pipeline` → `graphify --watch folder watcher`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__kilo__references__add-watch.md · relation: references
- `graph.json (graphify output artifact)` → `graphify post-commit hook`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__kilo__references__hooks.md · relation: references
- `GRAPH_REPORT.md (graphify output artifact)` → `graphify post-commit hook`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__kilo__references__hooks.md · relation: references
- `graphify --update pipeline` → `graphify --watch folder watcher`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__kiro__references__add-watch.md · relation: references
- `graph.json (graphify output artifact)` → `graphify post-commit hook`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__kiro__references__hooks.md · relation: references
- `GRAPH_REPORT.md (graphify output artifact)` → `graphify post-commit hook`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__kiro__references__hooks.md · relation: references
- `graphify --update pipeline` → `graphify --watch folder watcher`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__opencode__references__add-watch.md · relation: references
- `graph.json (graphify output artifact)` → `graphify post-commit hook`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__opencode__references__hooks.md · relation: references
- `GRAPH_REPORT.md (graphify output artifact)` → `graphify post-commit hook`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__opencode__references__hooks.md · relation: references
- `graphify --update pipeline` → `graphify --watch folder watcher`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__pi__references__add-watch.md · relation: references
- `graph.json (graphify output artifact)` → `graphify post-commit hook`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__pi__references__hooks.md · relation: references
- `GRAPH_REPORT.md (graphify output artifact)` → `graphify post-commit hook`  [AMBIGUOUS]
  tools/skillgen/expected/graphify__skills__pi__references__hooks.md · relation: references
- `graphify skill reference: hooks.md (claude)` → `graphify skill reference: hooks.md (claw)`  [AMBIGUOUS]
  graphify/skills/claw/references/hooks.md · relation: semantically_similar_to

## Knowledge Gaps
- **1116 isolated node(s):** `LOCAL_CONST`, `Invoice.Tax`, `TaxConverter`, `StackPanel`, `User.Name` (+1111 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 5225 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **70 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `ingest()` and `Opencode: Add-Watch Reference`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **What is the exact relationship between `serve.py` and `Opencode: Exports & Benchmark Reference`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **What is the exact relationship between `transcribe_all()` and `Opencode: Transcribe Video/Audio Reference`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **What is the exact relationship between `watch.py` and `Opencode: Add-Watch Reference`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **What is the exact relationship between `graphify Step 3B semantic subagent dispatch` and `graphify Whisper video/audio transcription`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **What is the exact relationship between `graphify Step 3B semantic subagent dispatch` and `graphify Whisper video/audio transcription`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **What is the exact relationship between `graphify Step 3B semantic subagent dispatch` and `graphify Whisper video/audio transcription`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
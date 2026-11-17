# Changelog

User-visible changes to the aPaper app. Unreleased entries are dated by integration; release headings use verified publication dates.

## [Unreleased]

### 2026-11-17

#### Fixed

- Resume saved scoped Knowledge work after restarting, recover eligible failed jobs when current model dependencies become available, and retry transient model failures within each task's existing budget without enabling automatic discovery or reopening paused or cancelled work.
- Record failures in Knowledge supplements and reprocessing rounds correctly, preserving existing Knowledge and the specific reason for failure.
- Use shared capsule controls for Knowledge retry actions and clarify authorization failures without duplicate sentence punctuation in all five app languages.
- Keep scrolling inside the hovered floating island, including its header and padding, without moving the background page at scroll boundaries.
- Let Zotero imports use their existing identifiers or titles for metadata lookup, replace imported values with verified provider results, and retain the imported record quietly when no verified result is available. Prevent stalled lookups from remaining in progress indefinitely.
- Show nested folder submenus for Move To and Copy To, with parent folders remaining selectable.
- Keep Knowledge startup reads in a loading state during bounded recovery, discard cancelled startup results, and show localized failures instead of internal storage codes.
- Remove generic warning strips from inspector panel headers and hide the legacy Zotero folder membership repair entry.
- Keep the authorization page open when revisiting onboarding, and align Back and Continue with their navigation arrows.
- Simplify workspace permission controls to Allow and Authorized consistently in onboarding and General settings.
- Prevent concurrent aPaper instances from opening the same research workspace, with a localized Retry prompt.
- Preserve SQLite transaction locks during catalog identity checks.
- Restore question editing on failed or stopped Paper Mentor replies so users can edit and resubmit or retry the original question.
- Place Import Paper immediately below Rename in library folder context menus.
- Keep verified Dogzee model groups usable when an optional key-name migration cannot validate the provider's editable token response.
- Restore Knowledge Steward sedimentation cards and current task progress from saved conversations after reopening, and reconnect waiting requests to their background worker after restart.
- Use consistent inline feedback for failed agent responses and annotation actions.
- Use the shared adaptive dialog layout and action buttons for organization history and change reviews.
- Avoid displaying Unix timestamps as elapsed response times when an agent's start time is missing.

### 2026-11-16

#### Added

- Give research figures and generated views a shared app-style visual vocabulary, with verified source excerpts, remembered view state, and bounded choices prepared in the owning conversation composer.
- Add Import Paper actions to the library blank-area and folder context menus, with folder imports going directly into that folder.
- Let the Research Assistant copy original attachments into project files, open attached folders for editing, manage the project list, and read, write, move, or delete resources across registered projects.

#### Changed

- Apply model-specific reasoning presets when importing providers, including Dogzee models, and keep Model Settings and all conversation pickers consistent; unknown models use the full default effort list, including Maximum, with localized labels in all five app languages.

#### Fixed

- Preserve Kimi reasoning continuations with the model’s supported request fields while keeping internal reasoning separate from visible answers.
- Allow Workbench commands to load common Homebrew, MacPorts, Python, Java, TeX, and font dependencies, give package and plotting tools writable caches inside their isolated run directory, and avoid terminating commands when a cache file disappears during quota sampling.
- Include hidden files and datasets in project command workspaces, refresh affected project resources after assistant edits, and let system Python and Ruby resolve their runtimes. Report installed and successfully tested interpreters separately, with actionable command failure diagnostics.
- Avoid repeating the unconfigured model message beneath the Research Assistant setup card.
- Start a requested Knowledge reprocess or supplement for a paper as its own request even while background Knowledge processing is off, instead of failing with "Workspace Knowledge read unavailable"; say that the request was not queued when the processor genuinely cannot open.
- Show a Knowledge request that only reuses earlier results as "Processed earlier" with those earlier counts, instead of as a completed round with zero results, and open the operated papers’ current Knowledge through "View results", preserving Cards or Graph mode and focusing a single paper’s root card.
- Treat an empty entity response in the recognized source-summary text path at 8,000 Unicode scalar values or more as a retryable failure explained on the card, instead of recording that the paper has no new knowledge; empty results for short excerpts and for the relation stage are still accepted.
- Load the complete paged graph for a selected paper instead of the limited card neighborhood, while keeping its Library selection and root-card focus when switching views.
- Keep Back and other left-side content controls clickable while the sidebar is collapsed; reveal the temporary sidebar only after a brief dwell at the window edge and cancel stale reveals on resize, focus changes, or explicit sidebar actions.
- Use the shared dialog header and controls for Recent Organization and its change review, with consistent Restore, Undo, and Close buttons; align Knowledge retry actions with the app’s capsule controls.
- Keep conversation lists responsive with many sessions by presenting rows lazily and publishing latest-question summaries in batches.
- Avoid rerendering unchanged response blocks as the active answer streams, while keeping citation actions current.
- Avoid repeating Knowledge graph validation and serialization when the same presentation is delivered again.
- Keep the pointer stable while moving over interactive nodes, citation links, web sources, and buttons in agent responses.
- Render bold text consistently around adjacent Chinese punctuation in all three agents, including streamed responses and conversation history.
- Show that the app is up to date after a successful update check finds no applicable release; continue to report network and metadata errors separately.

## Public distribution documentation


### Unreleased documentation changes

- Introduce aPaper 0.1.0 through a complete product overview, with English release notes and linked Chinese, Japanese and Korean editions.
- Standardize future release notes around new features, improvements and bug fixes.

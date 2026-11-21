# Changelog

User-visible changes to the aPaper app. Unreleased entries are dated by integration; release headings use verified publication dates.

## [0.1.3] - 2026-11-21

### 2026-11-21

#### Fixed

- Show the selected update package size and skip known-incompatible delta updates before download.
- Prevent update metadata checks from crashing when an appcast contains structured delta metadata.
- Recover the linked Dogzee management token when local credentials are missing, including optional account-service bindings.

### 2026-11-20

#### Fixed

- Request Documents access only after authorization, skip the step when access is already granted, and keep setup language state outside workspace data.

#### Changed

- Size the Quick Research shortcut button to its label.

## [0.1.2] - 2026-11-19

### 2026-11-19

#### Fixed

- Keep the reader’s parallel translation controls, settings, and model binding visible for every target language. When the original PDF already uses the target language, skip translation, keep the button in its default style, and show a floating-island notice. Reserve the red icon and badge for translation errors.
- Ask for confirmation before deleting a reader annotation.
- Hide passwords again when switching between sign-in, registration, and password reset, and keep each password field's visibility independent.
- Restore cached Ergouzi models at launch while refreshing in the background. Report local configuration failures separately from service response errors. After unlinking, remove Ergouzi providers and select a configured alternative when available.
- Show sending and error feedback when requesting Ergouzi registration and password reset codes. After a successful request, show a 30-second resend countdown in the button. Request a human check only when the service requires it.
- Save and check the first custom model provider even when an older binding uses a reasoning level its model no longer supports. Show specific feedback for invalid keys, model lists, and local configuration failures.
- Read PDFs whose text lives in form objects or that declare their cross-reference table unusually, such as some CNKI downloads, in Paper Mentor, the Knowledge Steward and the Research Assistant, and read the pages of PDFs that carry embedded files without sending the embedded files to the model.
- Remove a failed, rejected or pending attachment at any time, and stop a message from being sent while a rejected attachment is still in its draft, instead of answering as if the file had been read.
- Open a supplementary paper in the reader's second pane with an ordinary click, and open PDFs, Word documents, spreadsheets and text files from Paper Mentor or the Research Assistant beside the current paper or manuscript without changing the editor, build entry or compiled PDF.
- Show attached images, and sources opened from Knowledge details, in a viewer over the current window with the workspace blurred behind it, one close button and a compact tool strip. Images can be zoomed, panned, marked up, cropped and saved as a separate copy without changing the original; documents can be zoomed in and out.
- Keep the attachment and source viewer in front of everything in its window: opening a source from Knowledge details puts the details away and brings them back unchanged, with the same selection, scroll position and focus, when the viewer closes; Escape closes only the viewer.
- Show images and PDF pages directly on the blurred window without a white panel behind them, open PDF previews with the whole page in view, place the viewer's tool strip at the bottom of the window like the reader's, and zoom around the pointer with Command or Control and the scroll wheel.
- Send the images and PDFs you add to a quoted follow-up with that follow-up in the Research Assistant and the Knowledge Steward, and accept a follow-up with files while the main reply is still running, instead of refusing it or moving the files to the main draft.
- Remove an attachment with a click anywhere near its cross, instead of opening its preview when the click lands just beside the small cross.
- Keep each queued message's files with that message, so the next draft starts empty, and stop a follow-up from being sent as text alone while one of its files was rejected.
- Keep a quoted follow-up and its streaming reply, and the continuation after answering a question from the Research Assistant, below the earlier answer instead of above it.
- Load a Research Assistant reply's change card when the reply continued after you answered one of its questions, so it matches the full change review.
- Let Retry run again in the Research Assistant after a retry could not start, instead of silently ignoring later clicks and disabling Save and Build.
- Keep citation numbers fully visible beside punctuation, at narrow widths and in fallback formula and diagram blocks, and stop malformed blocks from printing raw diagnostics.

#### Changed

- Start new installations with an empty model setup. When updating, remove the old unconfigured placeholder and keep existing providers and model selections. Reset a saved reasoning level to Automatic if its model no longer supports it.
- Use a capsule control for the Quick Research menu bar shortcut. Press Escape while recording or click the clear button to remove the saved shortcut.

### 2026-11-18

#### Fixed

- Show models as loading while aPaper restores your Ergouzi subscription at launch, instead of briefly saying that no model is configured.
- Let Paper Mentor read, search and quote PDFs you attach to a conversation as evidence. Their citations open the PDF in the in-app preview at the quoted page with the passage highlighted, and show as unavailable once the attachment is removed.
- Outline figure, table and formula regions in Workbench review notes instead of shading them as selected text, and say when a citation could only be located to its page.
- Let a quoted follow-up research and stream its reply while the main Paper Mentor conversation is still answering, and the other way round. Each keeps its own progress, Stop and waiting messages, and stopping or failing one leaves the other running.
- Send follow-up questions about quoted text reliably and keep the main conversation usable when a follow-up fails, stops or is left waiting; waiting messages stay until you send, retry or remove them.
- Preview attached images, PDFs, text, Markdown, Word and RTF documents, spreadsheets and slides inside the app from any agent sidebar without leaving the current paper, with zoom and pan for images and an explicit option to open the file in its default app.
- Let Paper Mentor read and correct a Library paper's bibliographic details through the metadata editor's rules; the reply states what changed, and the Library and Reader update at once.
- Show the drop state only on the attachments panel while dragging files into an agent sidebar, instead of outlining the whole sidebar.
- Show citations whose source paper is no longer in the Library as unavailable instead of as grey sources that cannot be opened, and restore citations that were waiting for the Library to load.
- Require agreeing to aPaper's terms before continuing without signing in, with the same checkbox and guidance as signing in.
- Accept files dropped anywhere in the Paper Mentor, Knowledge Steward or Research Assistant sidebar, including over rendered answers, adding them to the current draft without sending.
- Show a message's images above its documents and question as one aligned group in every agent sidebar, keeping image proportions and wrapping to the sidebar width.
- Stack sentence-length answer choices one per row, using two columns only for short balanced pairs in a wide sidebar, with calmer styling and no stretched last item.
- Clear the composer immediately on the first send after launch, including after input-method composition, and show each message's own attachments without repeating earlier files on later messages.

## [0.1.1] - 2026-11-17

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

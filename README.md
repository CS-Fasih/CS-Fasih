<!DOCTYPE html><html><head><meta charset="utf-8"><title>README preview — CS-Fasih</title>
<style>/*dark */
.markdown-body {
  color-scheme: dark;
  /** CSS default easing. Use for hover state changes and micro-interactions. */
  /** Accelerating motion. Use for elements exiting the viewport (moving off-screen). */
  /** Smooth acceleration and deceleration. Use for elements moving or morphing within the viewport. */
  /** Decelerating motion. Use for elements entering the viewport or appearing on screen. */
  /** Constant motion with no acceleration. Use for continuous animations like progress bars or loaders. */
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  margin: 0;
  font-weight: 400;
  color: #f0f6fc;
  background-color: #0d1117;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
  font-size: 16px;
  line-height: 1.5;
  word-wrap: break-word;
}

.markdown-body a {
  text-decoration: underline;
  text-underline-offset: .2rem;
}

.markdown-body .octicon {
  display: inline-block;
  fill: currentColor;
  vertical-align: text-bottom;
}

.markdown-body h1:hover .anchor .octicon-link:before,
.markdown-body h2:hover .anchor .octicon-link:before,
.markdown-body h3:hover .anchor .octicon-link:before,
.markdown-body h4:hover .anchor .octicon-link:before,
.markdown-body h5:hover .anchor .octicon-link:before,
.markdown-body h6:hover .anchor .octicon-link:before {
  width: 16px;
  height: 16px;
  content: ' ';
  display: inline-block;
  background-color: currentColor;
  -webkit-mask-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' version='1.1' aria-hidden='true'><path fill-rule='evenodd' d='M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z'></path></svg>");
  mask-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' version='1.1' aria-hidden='true'><path fill-rule='evenodd' d='M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z'></path></svg>");
}

.markdown-body details,
.markdown-body figcaption,
.markdown-body figure {
  display: block;
}

.markdown-body summary {
  display: list-item;
}

.markdown-body [hidden] {
  display: none !important;
}

.markdown-body a {
  background-color: rgba(0,0,0,0);
  color: #4493f8;
  text-decoration: none;
}

.markdown-body abbr[title] {
  border-bottom: none;
  -webkit-text-decoration: underline dotted;
  text-decoration: underline dotted;
}

.markdown-body b,
.markdown-body strong {
  font-weight: 600;
}

.markdown-body dfn {
  font-style: italic;
}

.markdown-body h1 {
  margin: .67em 0;
  font-weight: 600;
  padding-bottom: .3em;
  font-size: 2em;
  border-bottom: 1px solid #3d444db3;
}

.markdown-body mark {
  background-color: #bb800926;
  color: #f0f6fc;
}

.markdown-body small {
  font-size: 90%;
}

.markdown-body sub,
.markdown-body sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

.markdown-body sub {
  bottom: -0.25em;
}

.markdown-body sup {
  top: -0.5em;
}

.markdown-body img {
  border-style: none;
  max-width: 100%;
  box-sizing: content-box;
}

.markdown-body code,
.markdown-body kbd,
.markdown-body pre,
.markdown-body samp {
  font-family: monospace;
  font-size: 1em;
}

.markdown-body figure {
  margin: 1em 2.5rem;
}

.markdown-body hr {
  box-sizing: content-box;
  overflow: hidden;
  background: rgba(0,0,0,0);
  border-bottom: 1px solid #3d444db3;
  height: .25em;
  padding: 0;
  margin: 1.5rem 0;
  background-color: #3d444d;
  border: 0;
}

.markdown-body input {
  font: inherit;
  margin: 0;
  overflow: visible;
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}

.markdown-body [type=button],
.markdown-body [type=reset],
.markdown-body [type=submit] {
  -webkit-appearance: button;
  appearance: button;
}

.markdown-body [type=checkbox],
.markdown-body [type=radio] {
  box-sizing: border-box;
  padding: 0;
}

.markdown-body [type=number]::-webkit-inner-spin-button,
.markdown-body [type=number]::-webkit-outer-spin-button {
  height: auto;
}

.markdown-body [type=search]::-webkit-search-cancel-button,
.markdown-body [type=search]::-webkit-search-decoration {
  -webkit-appearance: none;
  appearance: none;
}

.markdown-body ::-webkit-input-placeholder {
  color: inherit;
  opacity: .54;
}

.markdown-body ::-webkit-file-upload-button {
  -webkit-appearance: button;
  appearance: button;
  font: inherit;
}

.markdown-body a:hover {
  text-decoration: underline;
}

.markdown-body ::placeholder {
  color: #9198a1;
  opacity: 1;
}

.markdown-body hr::before {
  display: table;
  content: "";
}

.markdown-body hr::after {
  display: table;
  clear: both;
  content: "";
}

.markdown-body table {
  border-spacing: 0;
  border-collapse: collapse;
  display: block;
  width: max-content;
  max-width: 100%;
  overflow: auto;
  font-variant: tabular-nums;
}

.markdown-body td,
.markdown-body th {
  padding: 0;
}

.markdown-body details summary {
  cursor: pointer;
}

.markdown-body a:focus,
.markdown-body [role=button]:focus,
.markdown-body input[type=radio]:focus,
.markdown-body input[type=checkbox]:focus {
  outline: 2px solid var(--borderColor-accent-emphasis);
  outline-offset: -2px;
  box-shadow: none;
}

.markdown-body a:focus:not(:focus-visible),
.markdown-body [role=button]:focus:not(:focus-visible),
.markdown-body input[type=radio]:focus:not(:focus-visible),
.markdown-body input[type=checkbox]:focus:not(:focus-visible) {
  outline: solid 1px rgba(0,0,0,0);
}

.markdown-body a:focus-visible,
.markdown-body [role=button]:focus-visible,
.markdown-body input[type=radio]:focus-visible,
.markdown-body input[type=checkbox]:focus-visible {
  outline: 2px solid var(--borderColor-accent-emphasis);
  outline-offset: -2px;
  box-shadow: none;
}

.markdown-body a:not([class]):focus,
.markdown-body a:not([class]):focus-visible,
.markdown-body input[type=radio]:focus,
.markdown-body input[type=radio]:focus-visible,
.markdown-body input[type=checkbox]:focus,
.markdown-body input[type=checkbox]:focus-visible {
  outline-offset: 0;
}

.markdown-body kbd {
  display: inline-block;
  padding: 0.25rem;
  font: 11px ui-monospace, SFMono-Regular, SF Mono, Menlo, Consolas, Liberation Mono, monospace;
  line-height: 10px;
  color: #f0f6fc;
  vertical-align: middle;
  background-color: #151b23;
  border: solid 1px var(--borderColor-muted);
  border-bottom-color: var(--borderColor-muted);
  border-radius: 6px;
  box-shadow: inset 0 -1px 0 var(--borderColor-muted);
}

.markdown-body h1,
.markdown-body h2,
.markdown-body h3,
.markdown-body h4,
.markdown-body h5,
.markdown-body h6 {
  margin-top: 1.5rem;
  margin-bottom: 1rem;
  font-weight: 600;
  line-height: 1.25;
}

.markdown-body h2 {
  font-weight: 600;
  padding-bottom: .3em;
  font-size: 1.5em;
  border-bottom: 1px solid #3d444db3;
}

.markdown-body h3 {
  font-weight: 600;
  font-size: 1.25em;
}

.markdown-body h4 {
  font-weight: 600;
  font-size: 1em;
}

.markdown-body h5 {
  font-weight: 600;
  font-size: .875em;
}

.markdown-body h6 {
  font-weight: 600;
  font-size: .85em;
  color: #9198a1;
}

.markdown-body p {
  margin-top: 0;
  margin-bottom: 10px;
}

.markdown-body blockquote {
  margin: 0;
  padding: 0 1em;
  color: #9198a1;
  border-left: .25em solid #3d444d;
}

.markdown-body ul,
.markdown-body ol {
  margin-top: 0;
  margin-bottom: 0;
  padding-left: 2em;
}

.markdown-body ol ol,
.markdown-body ul ol {
  list-style-type: lower-roman;
}

.markdown-body ul ul ol,
.markdown-body ul ol ol,
.markdown-body ol ul ol,
.markdown-body ol ol ol {
  list-style-type: lower-alpha;
}

.markdown-body dd {
  margin-left: 0;
}

.markdown-body tt,
.markdown-body code,
.markdown-body samp {
  font-family: ui-monospace, SFMono-Regular, SF Mono, Menlo, Consolas, Liberation Mono, monospace;
  font-size: 12px;
}

.markdown-body pre {
  margin-top: 0;
  margin-bottom: 0;
  font-family: ui-monospace, SFMono-Regular, SF Mono, Menlo, Consolas, Liberation Mono, monospace;
  font-size: 12px;
  word-wrap: normal;
}

.markdown-body .octicon {
  display: inline-block;
  overflow: visible !important;
  vertical-align: text-bottom;
  fill: currentColor;
}

.markdown-body input::-webkit-outer-spin-button,
.markdown-body input::-webkit-inner-spin-button {
  margin: 0;
  appearance: none;
}

.markdown-body .mr-2 {
  margin-right: 0.5rem !important;
}

.markdown-body::before {
  display: table;
  content: "";
}

.markdown-body::after {
  display: table;
  clear: both;
  content: "";
}

.markdown-body>*:first-child {
  margin-top: 0 !important;
}

.markdown-body>*:last-child {
  margin-bottom: 0 !important;
}

.markdown-body a:not([href]) {
  color: inherit;
  text-decoration: none;
}

.markdown-body .absent {
  color: #f85149;
}

.markdown-body .anchor {
  float: left;
  padding-right: 0.25rem;
  margin-left: -20px;
  line-height: 1;
}

.markdown-body .anchor:focus {
  outline: none;
}

.markdown-body p,
.markdown-body blockquote,
.markdown-body ul,
.markdown-body ol,
.markdown-body dl,
.markdown-body table,
.markdown-body pre,
.markdown-body details {
  margin-top: 0;
  margin-bottom: 1rem;
}

.markdown-body blockquote>:first-child {
  margin-top: 0;
}

.markdown-body blockquote>:last-child {
  margin-bottom: 0;
}

.markdown-body h1 .octicon-link,
.markdown-body h2 .octicon-link,
.markdown-body h3 .octicon-link,
.markdown-body h4 .octicon-link,
.markdown-body h5 .octicon-link,
.markdown-body h6 .octicon-link {
  color: #f0f6fc;
  vertical-align: middle;
  visibility: hidden;
}

.markdown-body h1:hover .anchor,
.markdown-body h2:hover .anchor,
.markdown-body h3:hover .anchor,
.markdown-body h4:hover .anchor,
.markdown-body h5:hover .anchor,
.markdown-body h6:hover .anchor {
  text-decoration: none;
}

.markdown-body h1:hover .anchor .octicon-link,
.markdown-body h2:hover .anchor .octicon-link,
.markdown-body h3:hover .anchor .octicon-link,
.markdown-body h4:hover .anchor .octicon-link,
.markdown-body h5:hover .anchor .octicon-link,
.markdown-body h6:hover .anchor .octicon-link {
  visibility: visible;
}

.markdown-body h1 tt,
.markdown-body h1 code,
.markdown-body h2 tt,
.markdown-body h2 code,
.markdown-body h3 tt,
.markdown-body h3 code,
.markdown-body h4 tt,
.markdown-body h4 code,
.markdown-body h5 tt,
.markdown-body h5 code,
.markdown-body h6 tt,
.markdown-body h6 code {
  padding: 0 .2em;
  font-size: inherit;
}

.markdown-body summary h1,
.markdown-body summary h2,
.markdown-body summary h3,
.markdown-body summary h4,
.markdown-body summary h5,
.markdown-body summary h6 {
  display: inline-block;
}

.markdown-body summary h1 .anchor,
.markdown-body summary h2 .anchor,
.markdown-body summary h3 .anchor,
.markdown-body summary h4 .anchor,
.markdown-body summary h5 .anchor,
.markdown-body summary h6 .anchor {
  margin-left: -40px;
}

.markdown-body summary h1,
.markdown-body summary h2 {
  padding-bottom: 0;
  border-bottom: 0;
}

.markdown-body ul.no-list,
.markdown-body ol.no-list {
  padding: 0;
  list-style-type: none;
}

.markdown-body ol[type="a s"] {
  list-style-type: lower-alpha;
}

.markdown-body ol[type="A s"] {
  list-style-type: upper-alpha;
}

.markdown-body ol[type="i s"] {
  list-style-type: lower-roman;
}

.markdown-body ol[type="I s"] {
  list-style-type: upper-roman;
}

.markdown-body ol[type="1"] {
  list-style-type: decimal;
}

.markdown-body div>ol:not([type]) {
  list-style-type: decimal;
}

.markdown-body ul ul,
.markdown-body ul ol,
.markdown-body ol ol,
.markdown-body ol ul {
  margin-top: 0;
  margin-bottom: 0;
}

.markdown-body li>p {
  margin-top: 1rem;
}

.markdown-body li+li {
  margin-top: .25em;
}

.markdown-body dl {
  padding: 0;
}

.markdown-body dl dt {
  padding: 0;
  margin-top: 1rem;
  font-size: 1em;
  font-style: italic;
  font-weight: 600;
}

.markdown-body dl dd {
  padding: 0 1rem;
  margin-bottom: 1rem;
}

.markdown-body table th {
  font-weight: 600;
}

.markdown-body table th,
.markdown-body table td {
  padding: 6px 13px;
  border: 1px solid #3d444d;
}

.markdown-body table td>:last-child {
  margin-bottom: 0;
}

.markdown-body table tr {
  background-color: #0d1117;
  border-top: 1px solid #3d444db3;
}

.markdown-body table tr:nth-child(2n) {
  background-color: #151b23;
}

.markdown-body table img {
  background-color: rgba(0,0,0,0);
}

.markdown-body img[align=right] {
  padding-left: 20px;
}

.markdown-body img[align=left] {
  padding-right: 20px;
}

.markdown-body .emoji {
  max-width: none;
  vertical-align: text-top;
  background-color: rgba(0,0,0,0);
}

.markdown-body span.frame {
  display: block;
  overflow: hidden;
}

.markdown-body span.frame>span {
  display: block;
  float: left;
  width: auto;
  padding: 7px;
  margin: 13px 0 0;
  overflow: hidden;
  border: 1px solid #3d444d;
}

.markdown-body span.frame span img {
  display: block;
  float: left;
}

.markdown-body span.frame span span {
  display: block;
  padding: 5px 0 0;
  clear: both;
  color: #f0f6fc;
}

.markdown-body span.align-center {
  display: block;
  overflow: hidden;
  clear: both;
}

.markdown-body span.align-center>span {
  display: block;
  margin: 13px auto 0;
  overflow: hidden;
  text-align: center;
}

.markdown-body span.align-center span img {
  margin: 0 auto;
  text-align: center;
}

.markdown-body span.align-right {
  display: block;
  overflow: hidden;
  clear: both;
}

.markdown-body span.align-right>span {
  display: block;
  margin: 13px 0 0;
  overflow: hidden;
  text-align: right;
}

.markdown-body span.align-right span img {
  margin: 0;
  text-align: right;
}

.markdown-body span.float-left {
  display: block;
  float: left;
  margin-right: 13px;
  overflow: hidden;
}

.markdown-body span.float-left span {
  margin: 13px 0 0;
}

.markdown-body span.float-right {
  display: block;
  float: right;
  margin-left: 13px;
  overflow: hidden;
}

.markdown-body span.float-right>span {
  display: block;
  margin: 13px auto 0;
  overflow: hidden;
  text-align: right;
}

.markdown-body code,
.markdown-body tt {
  padding: .2em .4em;
  margin: 0;
  font-size: 85%;
  white-space: break-spaces;
  background-color: #656c7633;
  border-radius: 6px;
}

.markdown-body code br,
.markdown-body tt br {
  display: none;
}

.markdown-body del code {
  text-decoration: inherit;
}

.markdown-body samp {
  font-size: 85%;
}

.markdown-body pre code {
  font-size: 100%;
}

.markdown-body pre>code {
  padding: 0;
  margin: 0;
  word-break: normal;
  white-space: pre;
  background: rgba(0,0,0,0);
  border: 0;
}

.markdown-body .highlight {
  margin-bottom: 1rem;
}

.markdown-body .highlight pre {
  margin-bottom: 0;
  word-break: normal;
}

.markdown-body .highlight pre,
.markdown-body pre {
  padding: 1rem;
  overflow: auto;
  font-size: 85%;
  line-height: 1.45;
  color: #f0f6fc;
  background-color: #151b23;
  border-radius: 6px;
}

.markdown-body pre code,
.markdown-body pre tt {
  display: inline;
  padding: 0;
  margin: 0;
  overflow: visible;
  line-height: inherit;
  word-wrap: normal;
  background-color: rgba(0,0,0,0);
  border: 0;
}

.markdown-body .csv-data td,
.markdown-body .csv-data th {
  padding: 5px;
  overflow: hidden;
  font-size: 12px;
  line-height: 1;
  text-align: left;
  white-space: nowrap;
}

.markdown-body .csv-data .blob-num {
  padding: 10px 0.5rem 9px;
  text-align: right;
  background: #0d1117;
  border: 0;
}

.markdown-body .csv-data tr {
  border-top: 0;
}

.markdown-body .csv-data th {
  font-weight: 600;
  background: #151b23;
  border-top: 0;
}

.markdown-body [data-footnote-ref]::before {
  content: "[";
}

.markdown-body [data-footnote-ref]::after {
  content: "]";
}

.markdown-body .footnotes {
  font-size: 12px;
  color: #9198a1;
  border-top: 1px solid #3d444d;
}

.markdown-body .footnotes ol {
  padding-left: 1rem;
}

.markdown-body .footnotes ol ul {
  display: inline-block;
  padding-left: 1rem;
  margin-top: 1rem;
}

.markdown-body .footnotes li {
  position: relative;
}

.markdown-body .footnotes li:target::before {
  position: absolute;
  top: calc(0.5rem*-1);
  right: calc(0.5rem*-1);
  bottom: calc(0.5rem*-1);
  left: calc(1.5rem*-1);
  pointer-events: none;
  content: "";
  border: 2px solid #1f6feb;
  border-radius: 6px;
}

.markdown-body .footnotes li:target {
  color: #f0f6fc;
}

.markdown-body .footnotes .data-footnote-backref g-emoji {
  font-family: monospace;
}

.markdown-body .pl-c {
  color: #9198a1;
}

.markdown-body .pl-c1,
.markdown-body .pl-s .pl-v {
  color: #79c0ff;
}

.markdown-body .pl-e,
.markdown-body .pl-en {
  color: #d2a8ff;
}

.markdown-body .pl-smi,
.markdown-body .pl-s .pl-s1 {
  color: #f0f6fc;
}

.markdown-body .pl-ent {
  color: #7ee787;
}

.markdown-body .pl-k {
  color: #ff7b72;
}

.markdown-body .pl-s,
.markdown-body .pl-pds,
.markdown-body .pl-s .pl-pse .pl-s1,
.markdown-body .pl-sr,
.markdown-body .pl-sr .pl-cce,
.markdown-body .pl-sr .pl-sre,
.markdown-body .pl-sr .pl-sra {
  color: #a5d6ff;
}

.markdown-body .pl-v,
.markdown-body .pl-smw {
  color: #ffa657;
}

.markdown-body .pl-bu {
  color: #f85149;
}

.markdown-body .pl-ii {
  color: var(--fgColor-danger);
  background-color: var(--bgColor-danger-muted);
}

.markdown-body .pl-c2 {
  color: #f0f6fc;
  background-color: #b62324;
}

.markdown-body .pl-sr .pl-cce {
  font-weight: bold;
  color: #7ee787;
}

.markdown-body .pl-ml {
  color: #f2cc60;
}

.markdown-body .pl-mh,
.markdown-body .pl-mh .pl-en,
.markdown-body .pl-ms {
  font-weight: bold;
  color: #1f6feb;
}

.markdown-body .pl-mi {
  font-style: italic;
  color: #f0f6fc;
}

.markdown-body .pl-mb {
  font-weight: bold;
  color: #f0f6fc;
}

.markdown-body .pl-md {
  color: #ffdcd7;
  background-color: #67060c;
}

.markdown-body .pl-mi1 {
  color: #aff5b4;
  background-color: #033a16;
}

.markdown-body .pl-mc {
  color: #ffdfb6;
  background-color: #5a1e02;
}

.markdown-body .pl-mi2 {
  color: #f0f6fc;
  background-color: #1158c7;
}

.markdown-body .pl-mdr {
  font-weight: bold;
  color: #d2a8ff;
}

.markdown-body .pl-ba {
  color: #9198a1;
}

.markdown-body .pl-sg {
  color: #3d444d;
}

.markdown-body .pl-corl {
  text-decoration: underline;
  color: #a5d6ff;
}

.markdown-body [role=button]:focus:not(:focus-visible),
.markdown-body [role=tabpanel][tabindex="0"]:focus:not(:focus-visible),
.markdown-body button:focus:not(:focus-visible),
.markdown-body summary:focus:not(:focus-visible),
.markdown-body a:focus:not(:focus-visible) {
  outline: none;
  box-shadow: none;
}

.markdown-body [tabindex="0"]:focus:not(:focus-visible),
.markdown-body details-dialog:focus:not(:focus-visible) {
  outline: none;
}

.markdown-body g-emoji {
  display: inline-block;
  min-width: 1ch;
  font-family: "Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol";
  font-size: 1em;
  font-style: normal !important;
  font-weight: 400;
  line-height: 1;
  vertical-align: -0.075em;
}

.markdown-body g-emoji img {
  width: 1em;
  height: 1em;
}

.markdown-body a:has(>p,>div,>pre,>blockquote) {
  display: block;
}

.markdown-body a:has(>p,>div,>pre,>blockquote):not(:has(.snippet-clipboard-content,>pre)) {
  width: fit-content;
}

.markdown-body a:has(>p,>div,>pre,>blockquote):has(.snippet-clipboard-content,>pre):focus-visible {
  outline: 2px solid var(--borderColor-accent-emphasis);
  outline-offset: 2px;
}

.markdown-body .task-list-item {
  list-style-type: none;
}

.markdown-body .task-list-item label {
  font-weight: 400;
}

.markdown-body .task-list-item.enabled label {
  cursor: pointer;
}

.markdown-body .task-list-item+.task-list-item {
  margin-top: 0.25rem;
}

.markdown-body .task-list-item .handle {
  display: none;
}

.markdown-body .task-list-item-checkbox {
  margin: 0 .2em .25em -1.4em;
  vertical-align: middle;
}

.markdown-body ul:dir(rtl) .task-list-item-checkbox {
  margin: 0 -1.6em .25em .2em;
}

.markdown-body ol:dir(rtl) .task-list-item-checkbox {
  margin: 0 -1.6em .25em .2em;
}

.markdown-body .contains-task-list:hover .task-list-item-convert-container,
.markdown-body .contains-task-list:focus-within .task-list-item-convert-container {
  display: block;
  width: auto;
  height: 24px;
  overflow: visible;
  clip-path: none;
}

.markdown-body ::-webkit-calendar-picker-indicator {
  filter: invert(50%);
}

.markdown-body .markdown-alert {
  padding: 0.5rem 1rem;
  margin-bottom: 1rem;
  color: inherit;
  border-left: .25em solid #3d444d;
}

.markdown-body .markdown-alert>:first-child {
  margin-top: 0;
}

.markdown-body .markdown-alert>:last-child {
  margin-bottom: 0;
}

.markdown-body .markdown-alert .markdown-alert-title {
  display: flex;
  font-weight: 500;
  align-items: center;
  line-height: 1;
}

.markdown-body .markdown-alert.markdown-alert-note {
  border-left-color: #1f6feb;
}

.markdown-body .markdown-alert.markdown-alert-note .markdown-alert-title {
  color: #4493f8;
}

.markdown-body .markdown-alert.markdown-alert-important {
  border-left-color: #8957e5;
}

.markdown-body .markdown-alert.markdown-alert-important .markdown-alert-title {
  color: #ab7df8;
}

.markdown-body .markdown-alert.markdown-alert-warning {
  border-left-color: #9e6a03;
}

.markdown-body .markdown-alert.markdown-alert-warning .markdown-alert-title {
  color: #d29922;
}

.markdown-body .markdown-alert.markdown-alert-tip {
  border-left-color: #238636;
}

.markdown-body .markdown-alert.markdown-alert-tip .markdown-alert-title {
  color: #3fb950;
}

.markdown-body .markdown-alert.markdown-alert-caution {
  border-left-color: #da3633;
}

.markdown-body .markdown-alert.markdown-alert-caution .markdown-alert-title {
  color: #f85149;
}

.markdown-body>*:first-child>.heading-element:first-child {
  margin-top: 0 !important;
}

.markdown-body .highlight pre:has(+.zeroclipboard-container) {
  min-height: 52px;
}

 body{background:#0d1117;margin:0} .markdown-body{box-sizing:border-box;max-width:900px;margin:24px auto;padding:32px;border:1px solid #30363d;border-radius:6px} .bar{max-width:900px;margin:16px auto 0;color:#8b949e;font:14px -apple-system,Segoe UI,sans-serif}</style></head>
<body><div class="bar">CS-Fasih / README.md (preview)</div><article class="markdown-body"><p align="center">
  <img
    width="100%"
    src="data:image/svg+xml;base64,CiAgICAgIDxzdmcKICAgICAgICB3aWR0aD0iODU0IgogICAgICAgIGhlaWdodD0iMjQwIgogICAgICAgIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIKICAgICAgICB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIKICAgICAgICBzdHlsZT0iei1pbmRleDoxO3Bvc2l0aW9uOnJlbGF0aXZlIgogICAgICAgIHZpZXdCb3g9IjAgMCA4NTQgMjQwIgogICAgICA+CiAgICAgICAgPHN0eWxlPgogICAgICAudGV4dCB7ICAgZm9udC1zaXplOiA1NnB4OyAgIGZvbnQtd2VpZ2h0OiA3MDA7ICAgZm9udC1mYW1pbHk6IC1hcHBsZS1zeXN0ZW0sQmxpbmtNYWNTeXN0ZW1Gb250LFNlZ29lIFVJLEhlbHZldGljYSxBcmlhbCxzYW5zLXNlcmlmLEFwcGxlIENvbG9yIEVtb2ppLFNlZ29lIFVJIEVtb2ppOyAgfSAuZGVzYyB7ICAgZm9udC1zaXplOiAxOHB4OyAgIGZvbnQtd2VpZ2h0OiA1MDA7ICAgZm9udC1mYW1pbHk6IC1hcHBsZS1zeXN0ZW0sQmxpbmtNYWNTeXN0ZW1Gb250LFNlZ29lIFVJLEhlbHZldGljYSxBcmlhbCxzYW5zLXNlcmlmLEFwcGxlIENvbG9yIEVtb2ppLFNlZ29lIFVJIEVtb2ppOyAgfSAKICAgICAgLnRleHQsIC5kZXNjIHsgICBhbmltYXRpb246IGZhZGVJbiAxLjJzIGVhc2UtaW4tb3V0IGZvcndhcmRzOyAgfSBAa2V5ZnJhbWVzIGZhZGVJbiB7ICAgZnJvbSB7ICAgICBvcGFjaXR5OiAwOyAgIH0gICB0byB7ICAgICBvcGFjaXR5OiAxOyAgIH0gIH0gCiAgICA8L3N0eWxlPgogICAgICAgIDxkZWZzPgogICAgICAgICAgICAgIDxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyIiB4MT0iMCUiIHkxPSIwJSIgeDI9IjEwMCUiIHkyPSIwJSI+CiAgICAgICAgICAgICAgICA8c3RvcCBvZmZzZXQ9IjAlIiBzdG9wLWNvbG9yPSIjMDUwNzBBIi8+PHN0b3Agb2Zmc2V0PSI1NSUiIHN0b3AtY29sb3I9IiMxMTE4MjciLz48c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiNFODE5MkMiLz4KICAgICAgICAgICAgICA8L2xpbmVhckdyYWRpZW50PgogICAgICAgICAgICA8L2RlZnM+CiAgICAgICAgCiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQyNywgMTIwKSBzY2FsZSgxLCAxKSB0cmFuc2xhdGUoLTQyNywgLTEyMCkiPgogICAgICAgIDxwYXRoIGQ9IiIgZmlsbD0idXJsKCNsaW5lYXIpIiBvcGFjaXR5PSIwLjQiID4KICAgICAgICAgIDxhbmltYXRlCiAgICAgICAgICAgICAgYXR0cmlidXRlTmFtZT0iZCIKICAgICAgICAgICAgICBkdXI9IjIwcyIKICAgICAgICAgICAgICByZXBlYXRDb3VudD0iaW5kZWZpbml0ZSIKICAgICAgICAgICAgICBrZXlUaW1lcz0iMDswLjMzMzswLjY2NzsxIgogICAgICAgICAgICAgIGNhbGNtb2Q9InNwbGluZSIKICAgICAgICAgICAgICBrZXlTcGxpbmVzPSIwLjIgMCAwLjIgMTswLjIgMCAwLjIgMTswLjIgMCAwLjIgMSIKICAgICAgICAgICAgICBiZWdpbj0iMHMiCiAgICAgICAgICAgICAgdmFsdWVzPSJNMCAwTCAwIDE2MFEgMjEzLjUgMjAwIDQyNyAxNzBUIDg1NCAxOTVMIDg1NCAwIFo7TTAgMEwgMCAxODVRIDIxMy41IDIwMCA0MjcgMTgwVCA4NTQgMTcwTCA4NTQgMCBaO00wIDBMIDAgMjA1USAyMTMuNSAxNzUgNDI3IDIwNVQgODU0IDE3MEwgODU0IDAgWjtNMCAwTCAwIDE2MFEgMjEzLjUgMjAwIDQyNyAxNzBUIDg1NCAxOTVMIDg1NCAwIFoiPgogICAgICAgICAgPC9hbmltYXRlPgogICAgICAgIDwvcGF0aD4KICAgICAgICA8cGF0aCBkPSIiIGZpbGw9InVybCgjbGluZWFyKSIgb3BhY2l0eT0iMC40IiA+CiAgICAgICAgICA8YW5pbWF0ZQogICAgICAgICAgICBhdHRyaWJ1dGVOYW1lPSJkIgogICAgICAgICAgICBkdXI9IjIwcyIKICAgICAgICAgICAgcmVwZWF0Q291bnQ9ImluZGVmaW5pdGUiCiAgICAgICAgICAgIGtleVRpbWVzPSIwOzAuMzMzOzAuNjY3OzEiCiAgICAgICAgICAgIGNhbGNtb2Q9InNwbGluZSIKICAgICAgICAgICAga2V5U3BsaW5lcz0iMC4yIDAgMC4yIDE7MC4yIDAgMC4yIDE7MC4yIDAgMC4yIDEiCiAgICAgICAgICAgIGJlZ2luPSItMTBzIgogICAgICAgICAgICB2YWx1ZXM9Ik0wIDBMIDAgMTc1USAyMTMuNSAyMjAgNDI3IDE5MFQgODU0IDIwMEwgODU0IDAgWjtNMCAwTCAwIDE5MFEgMjEzLjUgMTYwIDQyNyAxNjBUIDg1NCAxODBMIDg1NCAwIFo7TTAgMEwgMCAxODVRIDIxMy41IDE2NSA0MjcgMTkwVCA4NTQgMjA1TCA4NTQgMCBaO00wIDBMIDAgMTc1USAyMTMuNSAyMjAgNDI3IDE5MFQgODU0IDIwMEwgODU0IDAgWiI+CiAgICAgICAgICA8L2FuaW1hdGU+CiAgICAgICAgPC9wYXRoPgogICAgICA8L2c+CiAgICAgICAgIDx0ZXh0IHRleHQtYW5jaG9yPSJtaWRkbGUiIGRvbWluYW50LWJhc2VsaW5lPSJtaWRkbGUiIHg9IjUwJSIgeT0iMzYlIiBjbGFzcz0idGV4dCIgc3R5bGU9ImZpbGw6I0ZGRkZGRjsiIHN0cm9rZT0iI25vbmUiIHN0cm9rZS13aWR0aD0iMSIgPk11aGFtbWFkIEZhc2loPC90ZXh0PgogICAgICAgIDx0ZXh0IHRleHQtYW5jaG9yPSJtaWRkbGUiIGRvbWluYW50LWJhc2VsaW5lPSJtaWRkbGUiIHg9IjUwJSIgeT0iNTclIiBjbGFzcz0iZGVzYyIgc3R5bGU9ImZpbGw6I0ZGRkZGRjsiPkFSL1ZSIERFVkVMT1BFUiDigKIgQUkg4oCiIEZVTEwtU1RBQ0s8L3RleHQ+CiAgICAgIDwvc3ZnPgogICAg"
    alt="Muhammad Fasih — AR/VR Developer, AI, Full-Stack"
  />
</p><p align="center">
  <a href="https://muhammadfasih.vercel.app">
    <img src="data:image/svg+xml;base64,PCEtLSBodHRwczovL2dpdGh1Yi5jb20vRGVudmVyQ29kZXIxL3JlYWRtZS10eXBpbmctc3ZnLyAtLT4KPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnCiAgICB4bWxuczp4bGluaz0naHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluaycKICAgIHZpZXdCb3g9JzAgMCA3MjAgNTAnCiAgICBzdHlsZT0nYmFja2dyb3VuZC1jb2xvcjogIzAwMDAwMDAwOycKICAgIHdpZHRoPSc3MjBweCcgaGVpZ2h0PSc1MHB4Jz4KCiAgICA8c3R5bGU+CkBmb250LWZhY2UgewogIGZvbnQtZmFtaWx5OiAnSmV0QnJhaW5zIE1vbm8nOwogIGZvbnQtc3R5bGU6IG5vcm1hbDsKICBmb250LXdlaWdodDogNjAwOwogIGZvbnQtZGlzcGxheTogZmFsbGJhY2s7CiAgc3JjOiB1cmwoZGF0YTpmb250L3RydWV0eXBlO2Jhc2U2NCxBQUVBQUFBUUFRQUFCQUFBUjBSRlJnRFdBTm9BQUFJUUFBQUFSa2RRVDFORWRFeDFBQUFCSEFBQUFCNUhVMVZDeUlPYklRQUFCMWdBQUFhdVQxTXZNaEhMQi9zQUFBSllBQUFBWUZOVVFWVGtLOG9BQUFBQm9BQUFBRFpqYldGd0E4OEVOZ0FBQTBBQUFBQ3daMkZ6Y0FBQUFCQUFBQUVVQUFBQUNHZHNlV2JBdWhyVkFBQU9DQUFBRkt4b1pXRmtGSkx4UXdBQUFkZ0FBQUEyYUdobFlRSE1BVHNBQUFGOEFBQUFKR2h0ZEhpWWE4NEFBQUFEOEFBQUFRaHNiMk5ocGkyaEFBQUFBcmdBQUFDR2JXRjRjQUM2QW04QUFBRThBQUFBSUc1aGJXVXkzVmpRQUFBRStBQUFBbDV3YjNOMC8yZ0FNd0FBQVZ3QUFBQWdjSEpsY0dnR2pJVUFBQUVNQUFBQUI3Z0IvNFd3QkkwQUFBRUFBZi8vQUE4QUFRQUFBQW9BSEFBY0FBRkVSa3hVQUFnQUJBQUFBQUQvL3dBQUFBQUFBQUFCQUFBQVFnRzRBRzRBdEFBR0FBRUFBQUFBQUFBQUFBQUFBQUFBQXdBQ0FBTUFBQUFBQUFEL1pRQXlBQUFBQVFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQVFBQUEveisxQUFBQkxENU8vMTBCSklBQVFBQUFBQUFBQUFBQUFBQUFBQUFBRUlBQVFBQkFBZ0FBZ0FBQUJRQUFRQUFBQ1FBQW5kbmFIUUJBQUFBYVhSaGJBRVBBQUVBQWdBREFBRUFBZ0VRQUFBQUFBQUJBQUFBQUFBQkFBQUFBallFTStrTnZWOFBQUFVBQXdQb0FBQUFBTnZTcHBvQUFBQUEyOXJROHZrNy90UUVrZ1A4QUFBQUJnQUNBQUFBQUFBQUFBRUFBQUFNQUFBQUFBQUFBQUlBQ1FBQkFBNEFBUUFRQUJBQUFRQVNBQklBQVFBVUFCUUFBUUFXQUJZQUFRQVlBQmdBQVFBYUFCc0FBUUFkQUNBQUFRQWpBQ01BQVFBQUFBUUNXZ0pZQUFVQUFBS0tBbGdBQUFCTEFvb0NXQUFBQVY0QU1nRkFBQUFDQUFBSkFBQUFBQUFBb0FBQy94QUErT3NBQUFBSUFBQUFBRXBDQUFBQXdBQWdBSGtEL1A3VUFBQUQvQUVzSUFBQm45L1hBQUFDSmdMYUFBQUFJQUFGQUFBQUdnQTdBSEFBbndEQ0FOZ0E3QUVMQVRJQmNBR09BYWtCMUFJTUFqa0NiZ0trQXNFQy93TWlBeTBEUUFOTEEyTURmUU8xQTljRUJ3UTlCRjRFbndTN0JOa0U5QVVmQlQwRlN3VnJCY1VGMUFYaEJmUUdEQVlZQmlRR01BWkFCa0FHbGdiZ0Iyc0lOZ2hKQ0dJSWZ3aWdDTDRJM0FrZUNXUUpoUW1wQ2RjS1B3cFdDbFlBQUFBQUFBSUFBQUFEQUFBQUZBQURBQUVBQUFBVUFBUUFuQUFBQUNJQUlBQUVBQUlBSUFBbUFDMEFMd0E3QUVBQVJnQk9BRk1BVmdCWUFHRUFhUUJ3QUhZQWVmLy9BQUFBSUFBbUFDd0FMd0E3QUVBQVFRQk9BRklBVlFCWUFHRUFZd0JyQUhJQWVQLy9BQThBQ3dBQS8vai82di93LzhEL3VmKzIvN1gvdFArcy82di9yUCtyLzZvQUFRQUFBQUFBSGdBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUpBQW9BbGdBV2dKWUFDY0NXQUJSQWxnQVRBSllBRThDV0FCYkFsZ0FWQUpZQUUwQ1dBQlFBbGdBUFFKWUFFMENXQUFuQWxnQUh3SllBRG9DV0FCS0FsZ0FTZ0pZQUVvQ1dBQTNBbGdBVEFKWUFGQUNXQUJPQWxnQVRnSllBRTRDV0FCVEFsZ0FIQUpZQURjQ1dBQlFBbGdBU2dKWUFGQUNXQUJpQWxnQVNBSllBQzRDV0FCT0FsZ0FLd0pZQUNjQ1dBQXFBbGdBbWdKWUFKOENXQUFmQWxnQVFBSllBSXdDV1A0MEFsajczQUpZL3BjQ1dQMzVBbGorTXdKWS9BZ0NXQUFBQWxnQUpBSllBQzRDV1AzOUFsajd1Z0pZL3BvQ1dQeVhBbGo5OVFKWSs3QUNXUDN4QWxqN21RSlkrVUVDV1BsQkFsajdtUUpZL2lRQ1dQNEtBbGo5NGdBQUFOMENXQUFBQUFBQUN3Q0tBQU1BQVFRSkFBQUF2QUVZQUFNQUFRUUpBQUVBTGdEcUFBTUFBUVFKQUFJQURnRGNBQU1BQVFRSkFBTUFQZ0NlQUFNQUFRUUpBQVFBTGdEcUFBTUFBUVFKQUFVQUdnQ0VBQU1BQVFRSkFBWUFMQUJZQUFNQUFRUUpBQTRBTmdBaUFBTUFBUVFKQVFBQURBQVdBQU1BQVFRSkFROEFEQUFLQUFNQUFRUUpBUkFBQ2dBQUFGSUFid0J0QUdFQWJnQkpBSFFBWVFCc0FHa0FZd0JYQUdVQWFRQm5BR2dBZEFCb0FIUUFkQUJ3QUhNQU9nQXZBQzhBY3dCakFISUFhUUJ3QUhRQWN3QXVBSE1BYVFCc0FDNEFid0J5QUdjQUx3QlBBRVlBVEFCS0FHVUFkQUJDQUhJQVlRQnBBRzRBY3dCTkFHOEFiZ0J2QUMwQVV3QmxBRzBBYVFCQ0FHOEFiQUJrQUZZQVpRQnlBSE1BYVFCdkFHNEFJQUF5QUM0QU1nQXhBREVBTWdBdUFESUFNUUF4QURzQVNnQkNBRHNBU2dCbEFIUUFRZ0J5QUdFQWFRQnVBSE1BVFFCdkFHNEFid0F0QUZNQVpRQnRBR2tBUWdCdkFHd0FaQUJTQUdVQVp3QjFBR3dBWVFCeUFFb0FaUUIwQUVJQWNnQmhBR2tBYmdCekFDQUFUUUJ2QUc0QWJ3QWdBRk1BWlFCdEFHa0FRZ0J2QUd3QVpBQkRBRzhBY0FCNUFISUFhUUJuQUdnQWRBQWdBRElBTUFBeUFEQUFJQUJVQUdnQVpRQWdBRW9BWlFCMEFFSUFjZ0JoQUdrQWJnQnpBQ0FBVFFCdkFHNEFid0FnQUZBQWNnQnZBR29BWlFCakFIUUFJQUJCQUhVQWRBQm9BRzhBY2dCekFDQUFLQUJvQUhRQWRBQndBSE1BT2dBdkFDOEFad0JwQUhRQWFBQjFBR0lBTGdCakFHOEFiUUF2QUVvQVpRQjBBRUlBY2dCaEFHa0FiZ0J6QUM4QVNnQmxBSFFBUWdCeUFHRUFhUUJ1QUhNQVRRQnZBRzRBYndBcEFBQUFBUUFBQUFvQU9BQjRBQUpFUmt4VUFDSnNZWFJ1QUE0QUdBQUJWRkpMSUFBS0FBRC8vd0FDQUFBQUFRQUVBQUFBQVAvL0FBRUFBQUFDWTJGc2RBQVViRzlqYkFBT0FBQUFBUUExQUFBQUZBQUFBQU1BQndBSkFBd0FEZ0FRQUJNQUZnQVpBQnNBSFFBZ0FDUUFKd0FyQUMwQUx3QXhBRE1BTmdYWUJjb0Z2QVZNQlQ0RnZBVzhCU1FGRmdUYUJNd0V2Z1NpQkpRRWVnUnNCRG9FTEFTK0EvWUQ2QVMrQTVBRGdnTjBBMWdEU2dNd0F5SUMwQUxDQkw0Q1VnSkVCTDRFdmdIc0FkNEIwQUZnQVZJQjBBSFFBVFlCS0FFT0FRQUE1Z0RZQUxnQXFnQ1FBSUlBYmdBQkFBQUFBUUFJQUFFQUJnQUNBQUVBQVFBVUFBRUFBQUFCQUFnQUFRV21BQllBQmdBQUFBRUFDQUFEQUFFRmNnQUJCWmdBQUFBQkFBQUFOQUFCQUFBQUFRQUlBQUVBSUFBUEFBWUFBQUFCQUFnQUF3QUJCVW9BQVFBU0FBQUFBUUFBQURJQUFRQUJBREFBQVFBQUFBRUFDQUFCQkRBQUZnQUdBQUFBQVFBSUFBTUFBUVVjQUFFRUlnQUFBQUVBQUFBd0FBRUFBQUFCQUFnQUFRUUlBQTRBQmdBQUFBRUFDQUFEQUFFRTlBQUJBL29BQUFBQkFBQUFMZ0FCQUFBQUFRQUlBQUVENEFBUEFBWUFBQUFCQUFnQUF3QUNCTXdFekFBQkE5SUFBQUFCQUFBQUxBQUJBQUFBQVFBSUFBRUE1QUFDQUFZQUFBQUZBRjRBVEFBNEFDUUFFQUFEQUFBQUFRRE9BQUlBemdET0FBRUFBQUFxQUFNQUFRU0dBQUVBdWdBQkFMb0FBUUFBQUNrQUF3QUNCSElFY2dBQkFLWUFBQUFCQUFBQUtBQURBQUFBQVFDU0FBTUFrZ0NTQUpJQUFBQURBQUVBZ0FBQkFJQUFBZ0NBQUlBQUFBQUJBQUFBQVFBSUFBRUFaZ0FRQUFFQUFBQUJBQWdBQVFCWUFBRUFCZ0FBQUFRQVFnQXlBQ0FBRGdBREFBQUFBUUJFQUFFQVJBQUJBQUFBSmdBREFBRUQvZ0FCQURJQUFBQUJBQUFBSlFBREFBQUFBUUFnQUFJQUlBQWdBQUFBQXdBQkFCQUFBUUFRQUFFQUVBQUFBQUVBQVFBeEFBRUFBQUFCQUFnQUFRTEVBQUlBQmdBQUFBVUFYZ0JNQURnQUpBQVFBQU1BQUFBQkFxNEFBZ0t1QXE0QUFRQUFBQ01BQXdBQkE1UUFBUUthQUFFQ21nQUJBQUFBSWdBREFBSURnQU9BQUFFQ2hnQUFBQUVBQUFBaEFBTUFBQUFCQW5JQUF3SnlBbklDY2dBQUFBTUFBUUpnQUFFQ1lBQUNBbUFDWUFBQUFBRUFBQUFCQUFnQUFRSkdBQUVBQmdBQUFBUUFRZ0F5QUNBQURnQURBQUFBQVFJeUFBRUNNZ0FCQUFBQUh3QURBQUVER2dBQkFpQUFBQUFCQUFBQUhnQURBQUFBQVFJT0FBSUNEZ0lPQUFBQUF3QUJBZjRBQVFIK0FBRUIvZ0FBQUFFQUFBQUJBQWdBQVFIbUFBd0FCZ0FBQUFFQUNBQURBQUVDMGdBQkFkZ0FBQUFCQUFBQUhBQUJBQUFBQVFBSUFBRUJ2Z0FOQUFZQUFBQUJBQWdBQXdBQ0Fxb0NxZ0FCQWJBQUFBQUJBQUFBR2dBQkFBQUFBUUFJQUFFQVpnQWNBQUVBQUFBQkFBZ0FBUUJZQUFZQUJnQUFBQVFBUWdBeUFDQUFEZ0FEQUFBQUFRQkVBQUVBUkFBQkFBQUFHQUFEQUFFQ1dnQUJBRElBQUFBQkFBQUFGd0FEQUFBQUFRQWdBQUlBSUFBZ0FBQUFBd0FCQUJBQUFRQVFBQUVBRUFBQUFBRUFBUUFsQUFFQUFBQUJBQWdBQVFFZ0FCTUFCZ0FBQUFJQUlBQUtBQU1BQWdJS0Fnb0FBUUVRQUFFQkVBQUJBQUFBRlFBREFBTUI5QUgwQWZRQUFRRDZBQUFBQVFBQUFCUUFBUUFBQUFFQUNBQUJBTndBRVFBR0FBQUFBZ0FlQUFvQUF3QUJBY1lBQVFETUFBRUF6QUFCQUFBQUVnQURBQUlCc2dHeUFBRUF1QUFBQUFFQUFBQVJBQUVBQUFBQkFBZ0FBUUNjQUJBQUJnQUFBQUVBQ0FBREFBRUJpQUFCQUk0QUFBQUJBQUFBRHdBQkFBQUFBUUFJQUFFQWRBQVVBQVlBQUFBQkFBZ0FBd0FDQVdBQllBQUJBR1lBQUFBQkFBQUFEUUFCQUFBQUFRQUlBQUVBU2dBWkFBRUFBQUFCQUFnQUFRQThBQklBQmdBQUFBSUFJQUFLQUFNQUFnRW1BU1lBQVFBc0FBRUFMQUFCQUFBQUN3QURBQU1CRUFFUUFSQUFBUUFXQUFBQUFRQUFBQW9BQVFBQkFDZ0FBUUFBQUFFQUNBQUJBUklBQlFBR0FBQUFBUUFJQUFNQUFRRGVBQUVCQkFBQUFBRUFBQUFJQUFFQUFBQUJBQWdBQVFEcUFBY0FCZ0FBQUFVQVhnQk1BRGdBSkFBUUFBTUFBQUFCQU5RQUFnRFVBTlFBQVFBQUFBWUFBd0FCQUpvQUFRREFBQUVBd0FBQkFBQUFCUUFEQUFJQWhnQ0dBQUVBckFBQUFBRUFBQUFFQUFNQUFBQUJBSmdBQXdDWUFKZ0FtQUFBQUFNQUFRQ0dBQUVBaGdBQ0FJWUFoZ0FBQUFFQUFBQUJBQWdBQVFCc0FCb0FBUUFBQUFFQUNBQUJBRjRBQmdBR0FBQUFCQUJJQURnQUlBQU9BQU1BQUFBQkFFb0FBUUJLQUFFQUFBQUNBQU1BQVFBU0FBRUFPQUFBQUFFQUFBQUJBQUVBQVFCQkFBTUFBQUFCQUNBQUFnQWdBQ0FBQUFBREFBRUFFQUFCQUJBQUFRQVFBQUFBQVFBQkFDY0FBQUFEQUZvQUFBSCtBdG9BQXdBR0FBa0FBRE1SSVJFbElSRUJBU0ZhQWFUK29nRXMvc0FCTFA3VUF0cjlKaklDTy80QUFqc0FBZ0FuQUFBQ01RTGFBQWNBRUFBQU14TXpFeU1uSXdjVE15Y21KaWNHQmdjbnVaaTVkaXZJS2orZExnd1JBd01RREFMYS9TYTF0UUVWeXpSU0VCQlJOQUFBQXdCUkFBQUNId0xhQUJJQUd3QWtBQUF6RVRNeUZoVVVCZ1lqTlRZV0ZoVVVCZ1lqSnpNeU5qVTBKaU1qTlRNeU5qVTBKaU1qVWR0cGVpeE1NVFpUTURoblIzZHZPRUpDT0c5cE5EczdNMm9DMm1SWU1Va29Cd0VxVWprL1hqSmpQRFUyUVdBM0x6QTJBQUVBVFAvMkFoTUM1QUFmQUFBRklpWW1OUkUwTmpZek1oWVdGU00wSmlNaUJoVVJGQll6TWpZMU14UUdCZ0V3UldjNE9HZEZSbVU0ZERvMU5UczdOVFU2ZERobENqUmhRUUZDUW1BME5WOUNOams1TnY2K05UbzZOVUJoTlFBQ0FFOEFBQUlTQXRvQUN3QVZBQUF6RVRNeUZoWVZFUlFHQmlNbk16STJOUkUwSmlNalQ5Skthenc4YTBwZFhUcENRanBkQXRvNFpVWCs2MFZtT0d0QU9BRVZOMEFBQVFCYkFBQUNEQUxhQUFzQUFETVJJUlVoRlNFVklSVWhGVnNCc2Y3Q0FSdis1UUUrQXRwbXgyYmhaZ0FCQUZRQUFBSVVBdHNBQ1FBQU14RWhGU0VWSVJVaEVWUUJ3UDZ5QVRUK3pnTGJiTTlzL3N3QUFRQk5BQUFDQ3dMYUFCRUFBRE1STXhNdUFqVVJNeEVqQXg0Q0ZSRk5rTkFDQndScmtNOERCUVFDMnYycUhsTlpJd0ZwL1NZQ1ZodFFWU1QramdBQ0FGQUFBQUlxQXRvQURnQVhBQUF6RVRNeUZoWVZGQVlIRXlNREl4RVJNekkyTlRRbUl5TlE1a2RwT2tvL2s0T0RZSEkxUHo4MWNnTGFOV0ZCU1cwVy9za0JKLzdaQVk0OU5UVStBQUFCQUQzLzlnSWJBdVVBS2dBQUJTSW1KalV6RkJZek1qWTFOQ1luSnlZbU5UUTJOak15Rmhjak5DWWpJZ1lWRkJZWEZ4WVdGUlFHQmdFdVNtdzdkRVE3TjBBc0tWaFRXamRsUldoNkFYVTZOVE01S3loYlUxazdhZ295WEQ0dk5qVXZKemtLR1JkeFRqNWFNMjFiTFRReEt5ZzREQm9XY0ZFK1hUUUFBUUJOLy9ZQ0N3TGFBQkVBQUFVaUpqVVJNeEVVRmpNeU5qVVJNeEVVQmdFc2FuVjBOalUwTjNSMENuUmtBZ3o5OVRZOVBUWUNDLzMwWkhRQUFRQW5BQUFDTVFMYUFBd0FBRE1ETXhNV0ZoYzJOamNUTXdQZ3VYaHlDaEFFQkE4S2NIVzVBdHIrSHlkU0dSbFNLQUhnL1NZQUFRQWZBQUFDT1FMYUFCY0FBRE1UQXpNWEZoWVhOalkzTnpNREV5TW5KaVluQmdZSEJ4L013SU5oQ2hFRUJCQUtZMzdBeklOc0NoRUZCQkVLYlFGMUFXVy9FeVlLQ2lZVHYvNmUvb2pSRXljTEN5WVQwZ0FDQURyLzlnSUtBakFBSEFBbkFBQVhJaVkxTkRZek16VTBKaU1pQmdjak5qWXpNaFlWRVNNMUl6Y1VCaWN5TmpVMUl5SUdGUlFXOGxWamExK1JOakFyT1FWeUNYbGNaSFJ5RXhSY0pqZEhqeWd3T0FwWlRWQllNU293SlNCTVdtUlcvb3BpR0QxSFdEa3NSaTBtS1M4QUFRQksvL1lDRWdJd0FCMEFBQVVpSmlZMU5UUTJOak15RmhjakppWWpJZ1lWRlJRV016STJOek1HQmdFd1JtYzVPV2RHWlhvRGRBTTZNVFU5UFRVeE9nTjBBM29LTkdGQmprSmdOR3BiTFRJNk5vNDFPekl0VzJvQUFnQksvL1lDQ0FMYUFCWUFKQUFBQlNJbU5UVTBOak15RmhVbk15YzFNeEVqTlNNM0ZBWW5NalkxTlRRbUl5SUdGUlVVRmdFQlUyUmtVMFJRR1JvRGRYTVpHVkFiTVRnNE1UTTVPUXB4WUpoZ2NVeENHNEdjL1NacEcwSk1aVHcxampVOE96YU9OanNBQUFJQVN2LzJBZzRDTUFBWkFDTUFBQVVpSmlZMU5UUTJOak15RmhZVkZTRVZGQll6TWpZM013WUdFelUwSmlNaUJoVVZOd0VzUkdZNE9HWkVSV1U0L3F3N09DMDNCM01OZWhvNU9UYzc3QW8xWVVDT1FHRTFOV0ZBWXlzN1BpQWRSbFFCUlI4N1AwQTZGd0VBQUFFQU53QUFBaHdDMmdBVEFBQXpFU00xTXpVME5qTXpGU01pQmhVVk14VWpFZEdhbWx4T29aOGFIdGZYQVlGcVZrWlRaeHNaVkdyK2Z3QUNBRXovVEFJSEFqQUFIZ0FzQUFBWE5UTXlOalUxTnlNM0ZBWWpJaVkxTlRRMk16SVdGU2N6SnpNUkZBWWpBekkyTlRVMEppTWlCaFVWRkJhYXBpb3FBaG9aVDBOVlltSlZRMDhaR1FKMGFWd1lNVGc0TVRNM043UmpLQ1l4WmhoQlNuRmdiV0J4U2tFWWFmM1ZVVjRCT2p3MVl6VThPelpqTmpzQUFRQlFBQUFDQ2dMYUFCWUFBRE1STXhVSE13YzBOak15RmhVUkl4RTBKaU1pQmhVUlVIVUNIaDVQUkZKaWRUY3dNVGdDMnJScEcwTkxhbHYrbFFGZk5EazhOdjZtLy84QVRnQUFBaTBERUFJbUFCVUFBQUFHQUVBUkFBQUJBRTRBQUFJdEFpWUFDUUFBTXpVekVTTTFJUkV6RlU3QnFBRVlybW9CVTJuK1JHb0EvLzhBVGdBQUFpMERFQUltQUJVQUFBQUdBRUFSQUFBQkFGTUFBQUkyQXRvQURBQUFNeEV6RVRNM013TVRJeWNqRlZOMVhJeURxNjZGalZ3QzJ2NXgyLzczL3VQbzZBQUJBQndBQUFJdEF0b0FEZ0FBSVNJbUpqVVJJelVoRVJRV016TVZBWDQxVHl5eUFTY2pIcWtyVGpRQnhHbjkweDhsYVFBQUFRQTNBQUFDSVFJd0FDY0FBRE1STXhVekJ6UTJNeklXRlNjekJ6UTJNeklXRlJFakVUUW1JeUlHRlJFakVUUW1JeUlHRlJFM1lSUVFNeWt0TVJja0R6UXJNenRuR1JnWUdsWWFHQmdZQWlaSUZDODNSejB5RkM4M1RVRCtYUUdmSFNBZkhmNWdBWjhlSHg4ZC9tQUFBQUVBVUFBQUFnb0NNQUFWQUFBekVUTVZNd2MwTmpNeUZoVVJJeEUwSmlNaUJoVVJVSE1lSGs5RVVtSjFOekF4T0FJbWFSdERTMnBiL3BVQlh6UTRPemIrcGdBQUFnQksvL2NDRGdJdkFCRUFId0FBQlNJbUpqVTFORFkyTXpJV0ZoVVZGQVlHSnpJMk5UVTBKaU1pQmhVVkZCWUJMRVZsT0RobFJVWmtPRGhrUmpRNk9qUXpPenNKTkdGQ2lrSmhORFJoUVl0Q1lUUm1PamVLT0RrNU9JbzNPZ0FBQWdCUS8wd0NEZ0l3QUJjQUpRQUFGeEV6RlRNSE5EWXpNaFlWRlJRR0JpTWlKalVYSXhjVkV6STJOVFUwSmlNaUJoVVZGQlpRY3hrWlVVUlRZeTFST0VSUkdSb0Rhakk1T1RJeE9UbTBBdHBwRzBKTWNXQ1lQMTh6VEVJYmdad0JEenMyampjNlBEV09OVHdBQVFCaUFBQUNKZ0l3QUJVQUFETVJNeFV6QnpRMk16SVdGUlVqTlRRbUl5SUdGUkZpYngwalQwMVpabms1TWpNNEFpWnBRVmxiYldFbUhqZzhQVGYrcGdBQUFRQkkvL2NDRlFJdkFDd0FBQVVpSmlZbk14WVdNek15TmpVMEppY25KaVkxTkRZek16SVdGeU1tSmlNaklnWVZGQllYRnhZV0ZSUUdJd0VZUFZzMUEzVURNU2NyTURBckswWmJWV1ZqSmxscUJuVURMQ1VtTFNra0owaGZXbWxwQ1NkRkx4c2dKaUFlSXdZS0RrbEpUVlJRUkJjZElTQWRIUVlLRGsxS1VGZ0FBQUVBTGdBQUFnOEN3UUFTQUFBaElpWTFFU00xTXpVekZUTVZJeEVVTXpNVkFXaE5WcGVYZE5iV05wWlZTd0VkYVp1YmFmN2pOMmtBQVFCTy8vWUNDZ0ltQUJFQUFBVWlKalVSTXhFVUZqTXlOalVSTXhFVUJnRXJabmQxTnpFeU9IVjVDblJrQVZqK3FUYzhQRGNCVi82b1pIUUFBUUFyQUFBQ0xRSW1BQXdBQURNRE14TVdGaGMyTmpjVE13UGh0bmR0Q2hFRUJSRUlhM2ExQWliK3FSOC9FaEkvSHdGWC9kb0FBUUFuQUFBQ01RSW1BQmNBQURNVEF6TVhGaFlYTmpZM056TURFeU1uSmlZbkJnWUhCeWZCdElWYkJ3NEVBdzRIVzRXMHdJVm1CdzRFQkE4SVpnRWNBUXFQREIwSkNSME1qLzcxL3VXZURCNEtDaDRNbmdBQkFDci9UQUl1QWlZQURRQUFGemNETXhNV0ZoYzJOamNUTXdHcFRzMkFiQWdQQlFRUEIyZDcvdmEwMHdJSC90Z1ZQQlFVUEJVQktQMG1BQUFCQUpyL1lBR0NBSmNBQXdBQUZ4TXpBNXBRbUlLZ0FUZit5UUFBQWdDZi8yQUJpQUl3QUFNQUVRQUFGeE16QXhNaUpqVTBOak16TWhZVkZBWWpuMUNZZ2gwa0xpOGpGQ012TGlTZ0FUZit5UUl0TGlNakx5OGpJeTRBQUFFQUh3QlpBamtDWWdBN0FBQTNKemMrQWpjbkxnSW5KemNYSGdJWE55NENOVFV6RlJRR0JnY1hQZ0kzTnhjSERnSUhCeDRDRnhjSEp5NENKeU1PQWdlOFZ5d1BLaXNRQXhRM09SZElKVWdYTWk0UUJRWVFDMm9MRHdjRUVTMHlGMGtsU1JjNE5oVURFQ3NxRGl4WExBNFpFd1lIQlJRWUQxazhRQlVwSkF3RkFRUUxDQnBrR2dnZUlBMEVGRFk4R2sxTkdqdzJGQVFPSHg0SUdtUWFDQXNFQVFZTUpDa1VRRHcvRlRZMUZCUTFOaFVBQUFFQVFQK1NBaGdEUGdBREFBQVhBVE1CUUFGZmVmNmhiZ09zL0ZRQUFBRUFqQUVWQWN3QmZ3QURBQUFUTlNFVmpBRkFBUlZxYWdBQUF2NDBBUlVCekFGL0FBTUFCd0FBRXpVaEZTRTFJUlV0QVovOGFBR2ZBUlZxYW1wcUFBQUQrOXdCRlFITUFYOEFBd0FIQUFzQUFCTTFJUlVoTlNFVk16VWhGUThCdmZvUUFiMWZBYmdCRldwcWFtcHFhdi8vL3BmL1lBRTRBakFBSndBbC9mZ0FBQUFHQUNXd0FQLy8vZm4va2dJWUF6NEFKd0FtL2RyL3NBSUdBQ2NBQVAvLy9qUC9rZ0hOQXo0QUpnQW50UUFBQndBbi9mTUFBUC8vL0FqL2tnR2dBejRBSndBbis4Z0FBQUFuQUNmOXFBQUFBQVlBSjRnQUFBSUFKUDlNQWprQzVBQXdBRDRBQUFVaUppWTFFVFEyTmpNeUZoWVZFU00zSXpjVUJpTWlKalUxTkRZek1oWVZKek1uTlRRbUppTWlCaFVSRkJZek14VVRNalkxTlRRbUl5SUdGUlVVRmdGRldZRkhRMzFYVDNJOVdRVWVFRHN4UDBWRlB6RTdEaDBQSlVVeVZsOWxXa1lGSlNJakpDTWtKTFJIZzFnQlZGcUNSanh1U2Y1UU54a29NbE5NZEUxU01Ta1ZSUWd3Unlkc1lmNnNYbWxiQVRRc01HOHJLeXdyZEMwcEFBQUNBQzcvOWdJOEF1UUFKd0F5QUFBWElpWTFOVFEyTndjbUpqVTBOall6TWhZV0ZTTTBKaVlqSWdZR0ZSUVdGeGMzTXdjWEl5Y0dKekkyTnljR0JoVVZGQmJvV0dKQU93c2ZJQzlWT1R4WU1HNFZKeG9ZSmhNWUZaSTdjbXh4ZGpOSFd4NDFFNHNYRnl3S1lWWmtRRklNRWl0UEp6SktLaTFRTmhrbEZCTWlHQmc2SGMxdXlwNUhVV0lqSHNNSEpoNWtLU3dBQlAzOS8vWUNIZ0xrQUNjQU1nQldBR0VBQUJjaUpqVTFORFkzQnlZbU5UUTJOak15RmhZVkl6UW1KaU1pQmdZVkZCWVhGemN6Qnhjakp3WWxNalkzSndZR0ZSVVVGaGNpSmpVMU5EWTNCeVltTlRRMk5qTXlGaFlWSXpRbUppTWlCZ1lWRkJZWEFTTW5CaVV5TmpjbkJnWVZGUlFXeWxoaVFEc0xIeUF2VlRrOFdEQnVGU2NhR0NZVEdCV1NPM0pzY1hZelIvMlNIalVUaXhjWExCNVlZa0E3REI4ZkwxVTVPMWt3YmhVbkdoa2tGQmdVQVVWMk0wY0J1QjQxRTRzWEZ5d0tZVlprUUZJTUVpdFBKekpLS2kxUU5oa2xGQk1pR0JnNkhjMXV5cDVIVVdJakhzTUhKaDVrS1N4aVlWWmtRRklNRWl0UEp6SktLaTFRTmhrbEZCTWlHQmc2SGY0NVIxRmlJeDdEQnlZZVpDa3NBQUFHKzdyLzlnSUFBdVFBSndBeUFGWUFZUUNGQUpBQUFCY2lKalUxTkRZM0J5WW1OVFEyTmpNeUZoWVZJelFtSmlNaUJnWVZGQllYRnpjekJ4Y2pKd1lsTWpZM0p3WUdGUlVVRmhjaUpqVTFORFkzQnlZbU5UUTJOak15RmhZVkl6UW1KaU1pQmdZVkZCWVhBU01uQmlVeU5qY25CZ1lWRlJRV0Z5SW1OVFUwTmpjSEppWTFORFkyTXpJV0ZoVWpOQ1ltSXlJR0JoVVVGaGNCSXljR0pUSTJOeWNHQmhVVkZCYXNXR0pBT3dzZklDOVZPVHhZTUc0Vkp4b1lKaE1ZRlpJN2NteHhkak5IKzIwZU5ST0xGeGNzSGxoaVFEc0xIeUF2VlRrOFdEQnVGU2NhR0NVVUdCVUJSSFl6UndIQkhqVVRpeGNYTEI1WVlrQTdDeDhnTDFVNVBGZ3diaFVuR2hnbEZCZ1ZBVVIyTTBjQndSNDFFNHNYRnl3S1lWWmtRRklNRWl0UEp6SktLaTFRTmhrbEZCTWlHQmc2SGMxdXlwNUhVV0lqSHNNSEpoNWtLU3hpWVZaa1FGSU1FaXRQSnpKS0tpMVFOaGtsRkJNaUdCZzZIZjQ1UjFGaUl4N0RCeVllWkNrc1ltRldaRUJTREJJclR5Y3lTaW90VURZWkpSUVRJaGdZT2gzK09VZFJZaU1ld3djbUhtUXBMQUFBQWY2YS82c0JwQUx1QUFjQUFBVVJNeEVoRlNFUi9wcDBBcGI5YWxVRFEvNlJhdjZXQUFBQy9KZi9xd0Z5QXU0QUJ3QUxBQUFGRVRNUklSVWhFU0VSTXhIK1JYUUN1ZjFIL2Q1MFZRTkQvcEZxL3BZRFEveTlBQUg5OVFBakFnVUNjUUFPQUFBbE56WTJOeVltSnljekZ5RVZJUWY5OWE4WkhRUUVIeG10aWJvQ3pmMHp1eVBpSHlFRUJDUWc0UEpxOGdBQys3QUFJd0lGQW5FQUNBQU9BQUFsRXdNekZ5RVZJUWNoRXdNekV3UDgzT1hsaXJvRDVmd2J1LzVMNWVXSzR1TWpBU1lCS1BKcThnRW1BU2orMmY3WkFBQUIvZkVBSXdIMEFuRUFEZ0FBSlFNVE13Y0dCZ2NoRlNFV0ZoY1gvdFBpNDRpdkF3Y0NBMVA4cmdNSEJLd2pBU2NCSitJRUNBUnFCQWtGNEFBQis1a0FJd0lGQW5FQURnQUFKUU1UTXdjR0JnY2hGU0VXRmhjWC9Idmk0NGl2QXdjQ0JiejZRZ1FJQmF3akFTY0JKK0lFQ0FSbkJRb0c0QUFGK1VILyt3SUZBdG9BQ3dBUEFCTUFHUUFuQUFBbEF4TXpCd1lHQnhZV0Z4Y2xOU0VWSVRVaEZRVUROVE1WQXdjaUpqVTBOak16TWhZVkZBWWoraVBpNDRpdkdCc0RCQnNhclA3N0Fna0JtQVM5K2t3V2doWTZIaVVsSGg0ZkpDVWVJd0VuQVNmaUh5RUVCQ01oNFBKcWFtcHFNUUZ4aFlYK2ora2tIQjBrSXgwZEpBQUUrVUVBQUFJRkF0b0FDQUFNQUNnQUxBQUFKUU1UTXdjaEZTRVhKVFVoRlFFM0l6VXpOeU0xTXpjekJ6TTNNd2N6RlNNSE14VWpCeU0zSXdjVE16Y2oraVBpNDRpN0FVSCt3TG9ESkFRMStaZ2lVMkVqWTNFaFZpS1JJVllpVTJFalkzRWhWaUtSSVMrUkk1RWpBU2NCSi9KcTh2SnFhdjdydTFERVVMdTd1N3RReEZDN3U3c0JDOFFBQUFMN21RQWpBZ1VDY1FBSUFBNEFBQ1VERXpNSElSVWhGeUVERXpNREUvMnc0dU9JdXdTSCszZTkva0xpNDRqajR5TUJKd0VuOG1mMUFTY0JKLzdhL3RnQUFBSCtKUCtTQWZNRFBnQVFBQUFYTndFMUpSVUZCZ1lIRmhZWEJRRXpBUnNzL2QwQnUvN1pFaU1LQ2lNU0FiRUJFSHIrb1c1MUFRZDMxRzZLQ1F3Q0FRd0p6d0xaL0ZRQUFBSCtDZ0RSQWZnQnd3QWZBQUFuSWk0REl5SUdGUlVqTlRRMk5qTXlIZ016TWpZMU5TRVZJUVlHVlN3OExDWW9HeHdqWlNwSkx5MDlMQ1VuR3g0aUFnLytQQlZHMFI0dExCNGlIVHhETEVNbUhpd3RIaVVlRG1vZ0pBQUFBdjNpQURjQ09RTGtBRUlBVUFBQUpTSW1OVFUwTmpNeUZoVW5NeWMxTkNZbUl5SU9CU01pTGdNaklnWVZGU00xTkRZek1oNERNekkrQlRNeUZoWVZFU00zSXpjVUJpY3lOalUxTkNZaklnWVZGUlFXQVdzL1JVVS9NVHNPSFE4bFJUSXhSemN2THpoSk1pVStOU3dxRlJZYlpWQkNKajQxTFNvVklURXJMVFJHWGtCUGNqMVpCUjRRT3d3bElpTWtJeVFrTjFOTWRFMVNNU2tWUmdjd1J5Y3NTRlpYU0NzWEpDUVlHeGc5UVQ1TEdDTWtHQ3RJVlZWSEt6eHVTZjVRTnhrb01ra3NNRzhyS3l3cmRDMHBBQUVBM1FLRUFYc0RFQUFMQUFBQklpWTFORFl6TWhZVkZBWUJMQ1VxS2lVbEtpb0NoQ1VnSVNZbUlTQWxBQT09KSBmb3JtYXQoJ3RydWV0eXBlJyk7Cn0KPC9zdHlsZT4KCiAgICAgICAgICAgICAgICAgICAgICAgICAgICA8cGF0aCBpZD0ncGF0aDAnPgogICAgICAgICAgICAgICAgICAgICAgICAgICAgPCEtLSBTaW5nbGUgbGluZSAtLT4KICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICA8YW5pbWF0ZSBpZD0nZDAnIGF0dHJpYnV0ZU5hbWU9J2QnIGJlZ2luPScwcztkMy5lbmQnCiAgICAgICAgICAgICAgICAgICAgZHVyPSczNzAwbXMnIGZpbGw9J3JlbW92ZScKICAgICAgICAgICAgICAgICAgICB2YWx1ZXM9J20wLDI1IGgwIDsgbTAsMjUgaDcyMCA7IG0wLDI1IGg3MjAgOyBtMCwyNSBoMCcga2V5VGltZXM9JzA7MC42MDU0MDU0MDU0MDU0MTswLjg0ODY0ODY0ODY0ODY1OzEnIC8+CiAgICAgICAgICAgICAgICAgICAgPC9wYXRoPgogICAgPHRleHQgZm9udC1mYW1pbHk9JyJKZXRCcmFpbnMgTW9ubyIsIG1vbm9zcGFjZScgZmlsbD0nI0U4MTkyQycgZm9udC1zaXplPScyMCcKICAgICAgICBkb21pbmFudC1iYXNlbGluZT0nbWlkZGxlJwogICAgICAgIHg9JzUwJScgdGV4dC1hbmNob3I9J21pZGRsZScKICAgICAgICBsZXR0ZXItc3BhY2luZz0nbm9ybWFsJz4KICAgICAgICA8dGV4dFBhdGggeGxpbms6aHJlZj0nI3BhdGgwJz4KICAgICAgICAgICAgUmVzZWFyY2ggU2Nob2xhciAmYW1wOyBBUi9WUiBEZXZlbG9wZXIgQCBORUQgVlJDCiAgICAgICAgPC90ZXh0UGF0aD4KICAgIDwvdGV4dD4KICAgICAgICAgICAgICAgIDxwYXRoIGlkPSdwYXRoMSc+CiAgICAgICAgICAgICAgICAgICAgICAgICAgICA8IS0tIFNpbmdsZSBsaW5lIC0tPgogICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIDxhbmltYXRlIGlkPSdkMScgYXR0cmlidXRlTmFtZT0nZCcgYmVnaW49J2QwLmVuZCcKICAgICAgICAgICAgICAgICAgICBkdXI9JzM3MDBtcycgZmlsbD0ncmVtb3ZlJwogICAgICAgICAgICAgICAgICAgIHZhbHVlcz0nbTAsMjUgaDAgOyBtMCwyNSBoNzIwIDsgbTAsMjUgaDcyMCA7IG0wLDI1IGgwJyBrZXlUaW1lcz0nMDswLjYwNTQwNTQwNTQwNTQxOzAuODQ4NjQ4NjQ4NjQ4NjU7MScgLz4KICAgICAgICAgICAgICAgICAgICA8L3BhdGg+CiAgICA8dGV4dCBmb250LWZhbWlseT0nIkpldEJyYWlucyBNb25vIiwgbW9ub3NwYWNlJyBmaWxsPScjRTgxOTJDJyBmb250LXNpemU9JzIwJwogICAgICAgIGRvbWluYW50LWJhc2VsaW5lPSdtaWRkbGUnCiAgICAgICAgeD0nNTAlJyB0ZXh0LWFuY2hvcj0nbWlkZGxlJwogICAgICAgIGxldHRlci1zcGFjaW5nPSdub3JtYWwnPgogICAgICAgIDx0ZXh0UGF0aCB4bGluazpocmVmPScjcGF0aDEnPgogICAgICAgICAgICBCdWlsZGluZyBpbW1lcnNpdmUgWFIgZXhwZXJpZW5jZXMgaW4gVW5pdHkKICAgICAgICA8L3RleHRQYXRoPgogICAgPC90ZXh0PgogICAgICAgICAgICAgICAgPHBhdGggaWQ9J3BhdGgyJz4KICAgICAgICAgICAgICAgICAgICAgICAgICAgIDwhLS0gU2luZ2xlIGxpbmUgLS0+CiAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgPGFuaW1hdGUgaWQ9J2QyJyBhdHRyaWJ1dGVOYW1lPSdkJyBiZWdpbj0nZDEuZW5kJwogICAgICAgICAgICAgICAgICAgIGR1cj0nMzcwMG1zJyBmaWxsPSdyZW1vdmUnCiAgICAgICAgICAgICAgICAgICAgdmFsdWVzPSdtMCwyNSBoMCA7IG0wLDI1IGg3MjAgOyBtMCwyNSBoNzIwIDsgbTAsMjUgaDAnIGtleVRpbWVzPScwOzAuNjA1NDA1NDA1NDA1NDE7MC44NDg2NDg2NDg2NDg2NTsxJyAvPgogICAgICAgICAgICAgICAgICAgIDwvcGF0aD4KICAgIDx0ZXh0IGZvbnQtZmFtaWx5PSciSmV0QnJhaW5zIE1vbm8iLCBtb25vc3BhY2UnIGZpbGw9JyNFODE5MkMnIGZvbnQtc2l6ZT0nMjAnCiAgICAgICAgZG9taW5hbnQtYmFzZWxpbmU9J21pZGRsZScKICAgICAgICB4PSc1MCUnIHRleHQtYW5jaG9yPSdtaWRkbGUnCiAgICAgICAgbGV0dGVyLXNwYWNpbmc9J25vcm1hbCc+CiAgICAgICAgPHRleHRQYXRoIHhsaW5rOmhyZWY9JyNwYXRoMic+CiAgICAgICAgICAgIEZpbmUtdHVuaW5nIHZpc2lvbi1sYW5ndWFnZSBtb2RlbHMKICAgICAgICA8L3RleHRQYXRoPgogICAgPC90ZXh0PgogICAgICAgICAgICAgICAgPHBhdGggaWQ9J3BhdGgzJz4KICAgICAgICAgICAgICAgICAgICAgICAgICAgIDwhLS0gU2luZ2xlIGxpbmUgLS0+CiAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgPGFuaW1hdGUgaWQ9J2QzJyBhdHRyaWJ1dGVOYW1lPSdkJyBiZWdpbj0nZDIuZW5kJwogICAgICAgICAgICAgICAgICAgIGR1cj0nMzcwMG1zJyBmaWxsPSdyZW1vdmUnCiAgICAgICAgICAgICAgICAgICAgdmFsdWVzPSdtMCwyNSBoMCA7IG0wLDI1IGg3MjAgOyBtMCwyNSBoNzIwIDsgbTAsMjUgaDAnIGtleVRpbWVzPScwOzAuNjA1NDA1NDA1NDA1NDE7MC44NDg2NDg2NDg2NDg2NTsxJyAvPgogICAgICAgICAgICAgICAgICAgIDwvcGF0aD4KICAgIDx0ZXh0IGZvbnQtZmFtaWx5PSciSmV0QnJhaW5zIE1vbm8iLCBtb25vc3BhY2UnIGZpbGw9JyNFODE5MkMnIGZvbnQtc2l6ZT0nMjAnCiAgICAgICAgZG9taW5hbnQtYmFzZWxpbmU9J21pZGRsZScKICAgICAgICB4PSc1MCUnIHRleHQtYW5jaG9yPSdtaWRkbGUnCiAgICAgICAgbGV0dGVyLXNwYWNpbmc9J25vcm1hbCc+CiAgICAgICAgPHRleHRQYXRoIHhsaW5rOmhyZWY9JyNwYXRoMyc+CiAgICAgICAgICAgIFNoaXBwaW5nIGZ1bGwtc3RhY2sgcHJvZHVjdHMsIGVuZCB0byBlbmQKICAgICAgICA8L3RleHRQYXRoPgogICAgPC90ZXh0Pgo8L3N2Zz4K" alt="Typing intro" />
  </a>
</p><p align="center">
  <a href="https://muhammadfasih.vercel.app">
    <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMjAuMjUiIGhlaWdodD0iMjgiIHJvbGU9ImltZyIgYXJpYS1sYWJlbD0iUE9SVEZPTElPIj48dGl0bGU+UE9SVEZPTElPPC90aXRsZT48ZyBzaGFwZS1yZW5kZXJpbmc9ImNyaXNwRWRnZXMiPjxyZWN0IHdpZHRoPSIxMjAuMjUiIGhlaWdodD0iMjgiIGZpbGw9IiNlODE5MmMiLz48L2c+PGcgZmlsbD0iI2ZmZiIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZm9udC1mYW1pbHk9IlZlcmRhbmEsR2VuZXZhLERlamFWdSBTYW5zLHNhbnMtc2VyaWYiIHRleHQtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iIGZvbnQtc2l6ZT0iMTAwIj48aW1hZ2UgeD0iOSIgeT0iNyIgd2lkdGg9IjE0IiBoZWlnaHQ9IjE0IiBocmVmPSJkYXRhOmltYWdlL3N2Zyt4bWw7YmFzZTY0LFBITjJaeUJtYVd4c1BTSjNhR2wwWlNJZ2NtOXNaVDBpYVcxbklpQjJhV1YzUW05NFBTSXdJREFnTWpRZ01qUWlJSGh0Ykc1elBTSm9kSFJ3T2k4dmQzZDNMbmN6TG05eVp5OHlNREF3TDNOMlp5SStQSFJwZEd4bFBsWmxjbU5sYkR3dmRHbDBiR1UrUEhCaGRHZ2daRDBpYlRFeUlERXVOakE0SURFeUlESXdMamM0TkVnd1dpSXZQand2YzNablBnPT0iLz48dGV4dCB0cmFuc2Zvcm09InNjYWxlKC4xKSIgeD0iNzAxLjI1IiB5PSIxNzUiIHRleHRMZW5ndGg9Ijc2Mi41IiBmb250LXdlaWdodD0iYm9sZCI+UE9SVEZPTElPPC90ZXh0PjwvZz48L3N2Zz4=" alt="Portfolio" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/muhammad-fasih-19f">
    <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI5MSIgaGVpZ2h0PSIyOCIgcm9sZT0iaW1nIiBhcmlhLWxhYmVsPSJMSU5LRURJTiI+PHRpdGxlPkxJTktFRElOPC90aXRsZT48ZyBzaGFwZS1yZW5kZXJpbmc9ImNyaXNwRWRnZXMiPjxyZWN0IHdpZHRoPSI5MSIgaGVpZ2h0PSIyOCIgZmlsbD0iIzBhNjZjMiIvPjwvZz48ZyBmaWxsPSIjZmZmIiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmb250LWZhbWlseT0iVmVyZGFuYSxHZW5ldmEsRGVqYVZ1IFNhbnMsc2Fucy1zZXJpZiIgdGV4dC1yZW5kZXJpbmc9Imdlb21ldHJpY1ByZWNpc2lvbiIgZm9udC1zaXplPSIxMDAiPjx0ZXh0IHRyYW5zZm9ybT0ic2NhbGUoLjEpIiB4PSI0NTUiIHk9IjE3NSIgdGV4dExlbmd0aD0iNjcwIiBmb250LXdlaWdodD0iYm9sZCI+TElOS0VESU48L3RleHQ+PC9nPjwvc3ZnPg==" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:muhammadfasih146@gmail.com">
    <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMDkiIGhlaWdodD0iMjgiIHJvbGU9ImltZyIgYXJpYS1sYWJlbD0iRU1BSUwgTUUiPjx0aXRsZT5FTUFJTCBNRTwvdGl0bGU+PGcgc2hhcGUtcmVuZGVyaW5nPSJjcmlzcEVkZ2VzIj48cmVjdCB3aWR0aD0iMTA5IiBoZWlnaHQ9IjI4IiBmaWxsPSIjMTYxYjIyIi8+PC9nPjxnIGZpbGw9IiNmZmYiIHRleHQtYW5jaG9yPSJtaWRkbGUiIGZvbnQtZmFtaWx5PSJWZXJkYW5hLEdlbmV2YSxEZWphVnUgU2FucyxzYW5zLXNlcmlmIiB0ZXh0LXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIiBmb250LXNpemU9IjEwMCI+PGltYWdlIHg9IjkiIHk9IjciIHdpZHRoPSIxNCIgaGVpZ2h0PSIxNCIgaHJlZj0iZGF0YTppbWFnZS9zdmcreG1sO2Jhc2U2NCxQSE4yWnlCbWFXeHNQU0ozYUdsMFpTSWdjbTlzWlQwaWFXMW5JaUIyYVdWM1FtOTRQU0l3SURBZ01qUWdNalFpSUhodGJHNXpQU0pvZEhSd09pOHZkM2QzTG5jekxtOXlaeTh5TURBd0wzTjJaeUkrUEhScGRHeGxQa2R0WVdsc1BDOTBhWFJzWlQ0OGNHRjBhQ0JrUFNKTk1qUWdOUzQwTlRkMk1UTXVPVEE1WXpBZ0xqa3dOQzB1TnpNeUlERXVOak0yTFRFdU5qTTJJREV1TmpNMmFDMHpMamd4T1ZZeE1TNDNNMHd4TWlBeE5pNDJOR3d0Tmk0MU5EVXROQzQ1TVhZNUxqSTNNMGd4TGpZek5rRXhMall6TmlBeExqWXpOaUF3SURBZ01TQXdJREU1TGpNMk5sWTFMalExTjJNd0xUSXVNREl6SURJdU16QTVMVE11TVRjNElETXVPVEkzTFRFdU9UWTBURFV1TkRVMUlEUXVOalFnTVRJZ09TNDFORGhzTmk0MU5EVXROQzQ1TVNBeExqVXlPQzB4TGpFME5VTXlNUzQyT1NBeUxqSTRJREkwSURNdU5ETTBJREkwSURVdU5EVTNlaUl2UGp3dmMzWm5QZz09Ii8+PHRleHQgdHJhbnNmb3JtPSJzY2FsZSguMSkiIHg9IjY0NSIgeT0iMTc1IiB0ZXh0TGVuZ3RoPSI2NTAiIGZvbnQtd2VpZ2h0PSJib2xkIj5FTUFJTCBNRTwvdGV4dD48L2c+PC9zdmc+" alt="Email" />
  </a>
</p><br><h2 align="center">⚡ Right Now</h2><table align="center">
  <tr>
    <td>🥽</td>
    <td><b>Research Scholar & AR/VR Developer</b> at <b>NED University Virtual Reality Center</b>, Karachi</td>
  </tr>
  <tr>
    <td>🛰️</td>
    <td><b>GeoExtract</b>, a vision-language pipeline for satellite imagery. IEEE journal paper in progress</td>
  </tr>
  <tr>
    <td>🏗️</td>
    <td>Previously <b>XR Engineer</b> at AIDL, working on WorldViz VR solutions</td>
  </tr>
  <tr>
    <td>🎓</td>
    <td><b>BS Computer Science</b>, Dawood University of Engineering & Technology</td>
  </tr>
</table><br><h2 align="center">🧭 What I Build</h2><table align="center">
  <tr>
    <th width="33%">🥽 XR & 3D</th>
    <th width="33%">🧠 AI & ML</th>
    <th width="33%">🛠️ Full-Stack & Systems</th>
  </tr>
  <tr>
    <td valign="top">VR/AR apps in Unity, interactive simulations, game-ready 3D assets and animation in Blender</td>
    <td valign="top">VLM fine-tuning (QLoRA), computer vision, object detection and segmentation, ML in production</td>
    <td valign="top">MERN and Next.js products, FastAPI microservices, Docker, Linux and security tooling</td>
  </tr>
</table><br><h2 align="center">🧰 Tech Stack</h2><p align="center"><b>XR & 3D</b></p>
<p align="center">
  <img src="data:image/svg+xml;base64,CiAgPHN2ZyB3aWR0aD0iMjE2Ljc1IiBoZWlnaHQ9IjQ4IiB2aWV3Qm94PSIwIDAgMTE1NiAyNTYiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHZlcnNpb249IjEuMSI+CiAgICAKICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLCAwKSI+CiAgICAgICAgICA8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIGZpbGw9Im5vbmUiIHZpZXdCb3g9IjAgMCAyNTYgMjU2Ij48cmVjdCB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgZmlsbD0iIzI0MjkzOCIgcng9IjYwIi8+PHBhdGggZmlsbD0iI0NDQyIgZD0iTTIxNi4wNDIgMTY3LjgxNFY3NC43NDI1TDEzNS4zOCAyOC4yMDY4VjYzLjk4NzZMMTY3LjAyNSA4Mi4xODgyQzE2OC4yNjYgODIuODA4NiAxNjguMjY2IDg0LjY3MDEgMTY3LjAyNSA4NS4yOTA1TDEyOS4zODIgMTA3LjAwN0MxMjguMzQ4IDEwNy42MjggMTI2LjkwMSAxMDcuNjI4IDEyNS44NjYgMTA3LjAwN0w4OC4yMjQzIDg1LjA4MzdDODYuOTgzNCA4NC40NjMyIDg2Ljk4MzQgODIuNjAxOCA4OC4yMjQzIDgxLjk4MTNMMTE5Ljg2OSA2My43ODA3VjI4TDM5LjIwNjggNzQuNTM1NlYxNjcuODE0VjE2Ny40VjE2Ny44MTRMNzAuMjMwNSAxNTAuMDI3VjExMy40MTlDNzAuMjMwNSAxMTIuMTc4IDcxLjY3ODMgMTExLjE0NCA3Mi45MTkzIDExMS45NzFMMTEwLjU2MSAxMzMuNjg4QzExMS41OTYgMTM0LjMwOCAxMTIuNDIzIDEzNS41NDkgMTEyLjQyMyAxMzYuNzlWMTgwLjIyM0MxMTIuNDIzIDE4MS40NjQgMTEwLjk3NSAxODIuNDk4IDEwOS43MzQgMTgxLjY3MUw3OC4wODk5IDE2My40N0w0Ny4wNjYxIDE4MS4yNTdMMTI3LjcyOCAyMjcuNzkzTDIwOC4zOSAxODEuMjU3TDE3Ny4zNjYgMTYzLjQ3TDE0NS43MjIgMTgxLjY3MUMxNDQuNjg4IDE4Mi4yOTEgMTQzLjAzMyAxODEuNDY0IDE0My4wMzMgMTgwLjIyM1YxMzYuNzlDMTQzLjAzMyAxMzUuNTQ5IDE0My42NTMgMTM0LjMwOCAxNDQuODk0IDEzMy42ODhMMTgyLjUzNyAxMTEuOTcxQzE4My41NzEgMTExLjM1IDE4NS4yMjUgMTEyLjE3OCAxODUuMjI1IDExMy40MTlWMTUwLjAyN0wyMTYuMDQyIDE2Ny44MTRaIi8+PHBhdGggZmlsbD0iI0E2QTZBNiIgZD0iTTEyNy41MjEgMjI4TDIwOC4xODMgMTgxLjQ2NEwxNzcuMTU5IDE2My42NzdMMTQ1LjUxNSAxODEuODc4QzE0NC40ODEgMTgyLjQ5OSAxNDIuODI2IDE4MS42NzEgMTQyLjgyNiAxODAuNDNWMTM2Ljk5N0MxNDIuODI2IDEzNS43NTYgMTQzLjQ0NyAxMzQuNTE1IDE0NC42ODggMTMzLjg5NUwxODIuMzMgMTEyLjE3OEMxODMuMzY0IDExMS41NTggMTg1LjAxOSAxMTIuMzg1IDE4NS4wMTkgMTEzLjYyNlYxNTAuMjM0TDIxNi4wNDIgMTY4LjAyMVY3NC43NDI3TDEyNy41MjEgMTI1LjgyOFYyMjhaIi8+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTEzNS4xNzQgMjhWNjMuNzgwN0wxNjYuODE4IDgxLjk4MTNDMTY4LjA1OSA4Mi42MDE4IDE2OC4wNTkgODQuNDYzMiAxNjYuODE4IDg1LjA4MzdMMTI5LjE3NiAxMDYuOEMxMjguMTQyIDEwNy40MjEgMTI2LjY5NCAxMDcuNDIxIDEyNS42NiAxMDYuOEw4OC4yMjQzIDg1LjA4MzdDODYuOTgzNCA4NC40NjMyIDg2Ljk4MzQgODIuNjAxOCA4OC4yMjQzIDgxLjk4MTNMMTE5Ljg2OSA2My43ODA3VjI4TDM5LjIwNjggNzQuNTM1NkwxMjcuNzI4IDEyNS42MjFMMjE2LjI0OSA3NC41MzU2TDEzNS4xNzQgMjhaIi8+PHBhdGggZmlsbD0iI0NDQyIgZD0iTTEwOS4zMiAxODEuNjcxTDc3LjY3NjMgMTYzLjQ3MUw0Ni42NTI1IDE4MS4yNThMMTI3LjMxNCAyMjcuNzkzVjEyNS42MjJMMzkgNzQuNzQyN1YxNjguMDIxVjE2Ny42MDdWMTY4LjAyMUw3MC4wMjM3IDE1MC4yMzRWMTEzLjYyNkM3MC4wMjM3IDExMi4zODUgNzEuNDcxNSAxMTEuMzUxIDcyLjcxMjUgMTEyLjE3OEwxMTAuMzU1IDEzMy44OTVDMTExLjM4OSAxMzQuNTE1IDExMi4yMTYgMTM1Ljc1NiAxMTIuMjE2IDEzNi45OTdWMTgwLjQzQzExMi4wMDkgMTgxLjQ2NCAxMTAuNTYxIDE4Mi4yOTIgMTA5LjMyIDE4MS42NzFaIi8+PC9zdmc+CiAgICAgICAgPC9nPgogICAgICAgICAKICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzMDAsIDApIj4KICAgICAgICAgIDxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgZmlsbD0ibm9uZSIgdmlld0JveD0iMCAwIDI1NiAyNTYiPjxyZWN0IHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiBmaWxsPSIjMjQyOTM4IiByeD0iNjAiLz48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMTA1LjU1MiAxMzcuMjgzQzEwNi4zMjcgMTIzLjQwMyAxMTMuMDkxIDExMS4xNzQgMTIzLjI5NiAxMDIuNTA1QzEzMy4zMDQgOTMuOTkwNyAxNDYuNzc1IDg4Ljc4NjYgMTYxLjQ3MyA4OC43ODY2QzE3Ni4xNTYgODguNzg2NiAxODkuNjI3IDkzLjk5MDcgMTk5LjY0MiAxMDIuNTA1QzIwOS44NCAxMTEuMTc0IDIxNi42MDQgMTIzLjQwMyAyMTcuMzg2IDEzNy4yNjhDMjE4LjE2IDE1MS41MyAyMTIuNDU1IDE2NC43NzkgMjAyLjQ0NyAxNzQuNkMxOTIuMjQyIDE4NC41OSAxNzcuNzI3IDE5MC44NTkgMTYxLjQ3MyAxOTAuODU5QzE0NS4yMTkgMTkwLjg1OSAxMzAuNjc1IDE4NC41OSAxMjAuNDc3IDE3NC42QzExMC40NjEgMTY0Ljc3OSAxMDQuNzcxIDE1MS41MyAxMDUuNTUyIDEzNy4yODNWMTM3LjI4M1oiLz48cGF0aCBmaWxsPSIjMjY1Nzg3IiBkPSJNMTMyLjc4MiAxMzguNTI5QzEzMy4xNzkgMTMxLjQwNyAxMzYuNjUgMTI1LjEzMiAxNDEuODg2IDEyMC42ODRDMTQ3LjAyMSAxMTYuMzE1IDE1My45MzMgMTEzLjY0NSAxNjEuNDc1IDExMy42NDVDMTY5LjAwOSAxMTMuNjQ1IDE3NS45MjEgMTE2LjMxNSAxODEuMDU5IDEyMC42ODRDMTg2LjI5MiAxMjUuMTMyIDE4OS43NjMgMTMxLjQwNyAxOTAuMTY0IDEzOC41MjFDMTkwLjU2MSAxNDUuODM5IDE4Ny42MzQgMTUyLjYzNyAxODIuNDk5IDE1Ny42NzdDMTc3LjI2MiAxNjIuODAzIDE2OS44MTUgMTY2LjAxOSAxNjEuNDc1IDE2Ni4wMTlDMTUzLjEzNSAxNjYuMDE5IDE0NS42NzIgMTYyLjgwMyAxNDAuNDM5IDE1Ny42NzdDMTM1LjMwMSAxNTIuNjM3IDEzMi4zODEgMTQ1LjgzOSAxMzIuNzgyIDEzOC41MjlWMTM4LjUyOVoiLz48cGF0aCBmaWxsPSIjRUE3NjAwIiBkPSJNODcuMDkwMiAxNTIuOTJDODcuMTM5IDE1NS43MDcgODguMDIzNSAxNjEuMTIzIDg5LjM1MDQgMTY1LjM1M0M5Mi4xMzkyIDE3NC4zMDUgOTYuODY5NCAxODIuNTg3IDEwMy40NTEgMTg5Ljg4NkMxMTAuMjA2IDE5Ny4zODkgMTE4LjUyMyAyMDMuNDE1IDEyOC4xMyAyMDcuNjkzQzEzOC4yMjggMjEyLjE4NiAxNDkuMTY5IDIxNC40NzYgMTYwLjUzNCAyMTQuNDU3QzE3MS44OCAyMTQuNDQyIDE4Mi44MjEgMjEyLjEwNyAxOTIuOTE5IDIwNy41OEMyMDIuNTI2IDIwMy4yNiAyMTAuODM2IDE5Ny4yMDggMjE3LjU3OSAxODkuNzAyQzIyNC4xNTcgMTgyLjM3MiAyMjguODggMTc0LjA3NSAyMzEuNjc2IDE2NS4xMjNDMjMzLjA4MiAxNjAuNTk5IDIzMy45NyAxNTYuMDA4IDIzNC4zMjYgMTUxLjQwMkMyMzQuNjc1IDE0Ni44NjQgMjM0LjUyOSAxNDIuMzE4IDIzMy44ODggMTM3Ljc3NkMyMzIuNjM2IDEyOC45MjUgMjI5LjU4OCAxMjAuNjIgMjI0Ljg5NSAxMTMuMDVDMjIwLjYwNCAxMDYuMDk0IDIxNS4wNzEgMTAwLjAwNCAyMDguNDkzIDk0Ljg3NzdMMjA4LjUwOCA5NC44NjYzTDE0Mi4xMjIgNDMuNjQ4NkMxNDIuMDYyIDQzLjYwMzQgMTQyLjAxNCA0My41NTQ1IDE0MS45NSA0My41MTMxQzEzNy41OTQgNDAuMTUzNSAxMzAuMjcgNDAuMTY0OCAxMjUuNDggNDMuNTMxOUMxMjAuNjM3IDQ2LjkzNjYgMTIwLjA4MyA1Mi41NjcyIDEyNC4zOTMgNTYuMTE4OEwxMjQuMzc0IDU2LjEzNzZMMTUyLjA2MyA3OC43NjE3TDY3LjY3MDQgNzguODUyMUg2Ny41NThDNjAuNTgyNSA3OC44NTk3IDUzLjg3NjggODMuNDU4MyA1Mi41NDk5IDg5LjI2OTdDNTEuMTg1NSA5NS4xOTAzIDU1LjkyMzMgMTAwLjEwMSA2My4xNzYyIDEwMC4xMjhMNjMuMTY1IDEwMC4xNTRMMTA1Ljk0IDEwMC4wNzFMMjkuNjEwNCAxNTguOTQyQzI5LjUxMyAxNTkuMDE0IDI5LjQwOCAxNTkuMDg5IDI5LjMxODEgMTU5LjE2MUMyMi4xMTc2IDE2NC43MDEgMTkuNzkgMTczLjkxMyAyNC4zMjU0IDE3OS43NDNDMjguOTI4MyAxODUuNjcyIDM4LjcxNSAxODUuNjgzIDQ1Ljk5MDQgMTc5Ljc3N0w4Ny42NDg3IDE0NS41MTlDODcuNjQ4NyAxNDUuNTE5IDg3LjA0MTUgMTUwLjE0NCA4Ny4wOTAyIDE1Mi45MlYxNTIuOTJaTTE5NC4xMzcgMTY4LjQwN0MxODUuNTU0IDE3Ny4xOTQgMTczLjUzNyAxODIuMTc3IDE2MC41MzQgMTgyLjIwM0MxNDcuNTEyIDE4Mi4yMjYgMTM1LjQ5NSAxNzcuMjg4IDEyNi45MTIgMTY4LjUxNkMxMjIuNzE4IDE2NC4yNDEgMTE5LjYzNiAxNTkuMzIzIDExNy43MzYgMTU0LjA4NEMxMTUuODczIDE0OC45MzUgMTE1LjE1IDE0My40NyAxMTUuNjMgMTM3Ljk1NkMxMTYuMDgzIDEzMi41NjcgMTE3LjY4IDEyNy40MjYgMTIwLjIyOSAxMjIuNzc1QzEyMi43MzMgMTE4LjIwMiAxMjYuMTgxIDExNC4wNzEgMTMwLjQzOSAxMTAuNTc2QzEzOC43ODMgMTAzLjc0NCAxNDkuNDA1IDEwMC4wNDUgMTYwLjUxNSAxMDAuMDNDMTcxLjYzNiAxMDAuMDE1IDE4Mi4yNTEgMTAzLjY3OSAxOTAuNjAzIDExMC40ODlDMTk0Ljg1MyAxMTMuOTY5IDE5OC4yOTggMTE4LjA4NiAyMDAuODAyIDEyMi42NUMyMDMuMzYyIDEyNy4yOTggMjA0Ljk0NyAxMzIuNDIgMjA1LjQxOSAxMzcuODI1QzIwNS44OTIgMTQzLjMzMSAyMDUuMTY4IDE0OC43ODggMjAzLjMwNSAxNTMuOTQxQzIwMS40MDEgMTU5LjE5NSAxOTguMzMxIDE2NC4xMTMgMTk0LjEzNyAxNjguNDA3VjE2OC40MDdaIi8+PC9zdmc+CiAgICAgICAgPC9nPgogICAgICAgICAKICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDAsIDApIj4KICAgICAgICAgIDxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgZmlsbD0ibm9uZSIgdmlld0JveD0iMCAwIDI1NiAyNTYiPjxyZWN0IHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiBmaWxsPSIjOTUzQ0FEIiByeD0iNjAiLz48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMTk1LjQzNiAxMDAuNjY4VjExNC4xNDJIMjA4LjkxVjEwMC42NjhIMjE1LjY0N1YxMTQuMTQySDIyOS4xMlYxMjAuODc5SDIxNS42NDdWMTM0LjM1MkgyMjkuMTJWMTQxLjA4OUgyMTUuNjQ3VjE1NC41NjNIMjA4LjkxVjE0MS4wODlIMTk1LjQzNlYxNTQuNTYzSDE4OC42OTlWMTQxLjA4OUgxNzUuMjI2VjEzNC4zNTJIMTg4LjY5OVYxMjAuODc5SDE3NS4yMjZWMTE0LjE0MkgxODguNjk5VjEwMC42NjhIMTk1LjQzNlpNMjA4LjkxIDEyMC44NzlIMTk1LjQzNlYxMzQuMzUySDIwOC45MVYxMjAuODc5WiIvPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik0xMjIuMDAxIDMzQzE1Ny4xNDQgMzMgMTg3LjgyOCA1Mi4wODYzIDIwNC4yNjIgODAuNDU2MUwyMDQuMTAyIDgwLjE4M0wxNjIuNzUzIDEwMy45OTFDMTU0LjYwNyA5MC4xOTc3IDEzOS42NzIgODAuODg5MiAxMjIuNTQgODAuNjk3NUwxMjIuMDAxIDgwLjY5NDVDOTUuODc1IDgwLjY5NDUgNzQuNjk0NSAxMDEuODc0IDc0LjY5NDUgMTI3Ljk5OUM3NC42OTQ1IDEzNi41NDMgNzYuOTcyMyAxNDQuNTUyIDgwLjkzMzUgMTUxLjQ2OUM4OS4wODc2IDE2NS43MDQgMTA0LjQxNiAxNzUuMzA2IDEyMi4wMDEgMTc1LjMwNkMxMzkuNjkzIDE3NS4zMDYgMTU1LjEwOSAxNjUuNTgyIDE2My4yMjIgMTUxLjE5NUwxNjMuMDI1IDE1MS41NEwyMDQuMzExIDE3NS40NThDMTg4LjA1NyAyMDMuNTg4IDE1Ny43OTQgMjIyLjYxNSAxMjMuMDU5IDIyMi45OTRMMTIyLjAwMSAyMjNDODYuNzQ2IDIyMyA1NS45NzUzIDIwMy43OTYgMzkuNTgyIDE3NS4yNzZDMzEuNTc5MSAxNjEuMzUzIDI3IDE0NS4yMTIgMjcgMTI3Ljk5OUMyNyA3NS41MzM0IDY5LjUzMjMgMzMgMTIyLjAwMSAzM1oiLz48L3N2Zz4KICAgICAgICA8L2c+CiAgICAgICAgIAogICAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDkwMCwgMCkiPgogICAgICAgICAgPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiBmaWxsPSJub25lIiB2aWV3Qm94PSIwIDAgMjU2IDI1NiI+PHJlY3Qgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIGZpbGw9IiMyNDI5MzgiIHJ4PSI2MCIvPjxwYXRoIGZpbGw9IiM0NEQxRkQiIGQ9Ik0xNDQuOTM0IDM4LjA2MTVMMjAwLjcwOSAzOEwxMDcuMTM0IDEzMS41MjZMODIuNzQ3MiAxNTUuNzc3TDU1IDEyNy45OTZMMTQ0LjkzNCAzOC4wNjE1Wk0xNDQuNDE1IDEyMS41NjlDMTQ1LjEzOSAxMjAuNjEzIDE0Ni40NzEgMTIxLjA4NSAxNDcuNDgyIDEyMC45NjJMMjAwLjY2MSAxMjAuOTc1TDE1Mi4xOTQgMTY5LjM5NUwxMjQuMzAzIDE0MS42NzVMMTQ0LjQxNSAxMjEuNTY5WiIvPjxwYXRoIGZpbGw9IiMxRkJDRkQiIGQ9Ik05Ni41MDEzIDE2OS40NDJMMTI0LjMwMyAxNDEuNjc1TDE1Mi4xOTQgMTY5LjM5NUwxNTIuMzEgMTY5LjUxOEwxMjQuMzEgMTk3LjI1OEw5Ni41MDEzIDE2OS40NDJWMTY5LjQ0MloiLz48cGF0aCBmaWxsPSIjMDg1ODlDIiBkPSJNMTI0LjMxIDE5Ny4yNThMMTUyLjMxIDE2OS41MThMMjAwLjY4MSAyMTcuOTM3QzE4Mi40NjEgMjE3Ljk3OCAxNjQuMjQ3IDIxNy45MjMgMTQ2LjAzNCAyMTcuOTY0QzE0NC45OTYgMjE4LjE5NiAxNDQuMzU0IDIxNy4yNDcgMTQzLjY5MSAyMTYuNjZMMTI0LjMxIDE5Ny4yNThWMTk3LjI1OFoiLz48L3N2Zz4KICAgICAgICA8L2c+CiAgICAgICAgCiAgPC9zdmc+CiAg" alt="XR and 3D stack" />
</p><p align="center"><b>AI & Data</b></p>
<p align="center">
  <img src="data:image/svg+xml;base64,CiAgPHN2ZyB3aWR0aD0iMzg1LjUiIGhlaWdodD0iNDgiIHZpZXdCb3g9IjAgMCAyMDU2IDI1NiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIj4KICAgIAogICAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAsIDApIj4KICAgICAgICAgIDxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgZmlsbD0ibm9uZSIgdmlld0JveD0iMCAwIDI1NiAyNTYiPjxyZWN0IHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiBmaWxsPSIjMjQyOTM4IiByeD0iNjAiLz48cGF0aCBmaWxsPSJ1cmwoI3BhaW50MF9saW5lYXJfMl80NykiIGQ9Ik0xMjcuMjc5IDI5Qzc2LjUwNjYgMjkgNzkuNjc3MiA1MS4wMTggNzkuNjc3MiA1MS4wMThMNzkuNzMzOCA3My44Mjg0SDEyOC4xODVWODAuNjc3Mkg2MC40ODkzQzYwLjQ4OTMgODAuNjc3MiAyOCA3Ni45OTI2IDI4IDEyOC4yMjJDMjggMTc5LjQ1MiA1Ni4zNTczIDE3Ny42MzYgNTYuMzU3MyAxNzcuNjM2SDczLjI4MTJWMTUzLjg2M0M3My4yODEyIDE1My44NjMgNzIuMzY5IDEyNS41MDYgMTAxLjE4NiAxMjUuNTA2SDE0OS4yNEMxNDkuMjQgMTI1LjUwNiAxNzYuMjM5IDEyNS45NDIgMTc2LjIzOSA5OS40MTIzVjU1LjU0NjFDMTc2LjIzOSA1NS41NDYxIDE4MC4zMzggMjkgMTI3LjI3OSAyOVpNMTAwLjU2MyA0NC4zMzlDMTA1LjM4NCA0NC4zMzkgMTA5LjI4IDQ4LjIzNTEgMTA5LjI4IDUzLjA1NTZDMTA5LjI4IDU3Ljg3NjEgMTA1LjM4NCA2MS43NzIzIDEwMC41NjMgNjEuNzcyM0M5NS43NDI2IDYxLjc3MjMgOTEuODQ2NSA1Ny44NzYxIDkxLjg0NjUgNTMuMDU1NkM5MS44NDY1IDQ4LjIzNTEgOTUuNzQyNiA0NC4zMzkgMTAwLjU2MyA0NC4zMzlaIi8+PHBhdGggZmlsbD0idXJsKCNwYWludDFfbGluZWFyXzJfNDcpIiBkPSJNMTI4LjcyMSAyMjcuOTU4QzE3OS40OTMgMjI3Ljk1OCAxNzYuMzIzIDIwNS45NDEgMTc2LjMyMyAyMDUuOTQxTDE3Ni4yNjYgMTgzLjEzSDEyNy44MTVWMTc2LjI4MUgxOTUuNTExQzE5NS41MTEgMTc2LjI4MSAyMjggMTc5Ljk2NiAyMjggMTI4LjczNkMyMjggNzcuNTA2MiAxOTkuNjQzIDc5LjMyMyAxOTkuNjQzIDc5LjMyM0gxODIuNzE5VjEwMy4wOTZDMTgyLjcxOSAxMDMuMDk2IDE4My42MzEgMTMxLjQ1MyAxNTQuODE0IDEzMS40NTNIMTA2Ljc2QzEwNi43NiAxMzEuNDUzIDc5Ljc2MDcgMTMxLjAxNiA3OS43NjA3IDE1Ny41NDZWMjAxLjQxMkM3OS43NjA3IDIwMS40MTIgNzUuNjYxNSAyMjcuOTU4IDEyOC43MjEgMjI3Ljk1OFpNMTU1LjQzNyAyMTIuNjE5QzE1MC42MTYgMjEyLjYxOSAxNDYuNzIgMjA4LjcyMyAxNDYuNzIgMjAzLjkwM0MxNDYuNzIgMTk5LjA4MiAxNTAuNjE2IDE5NS4xODYgMTU1LjQzNyAxOTUuMTg2QzE2MC4yNTcgMTk1LjE4NiAxNjQuMTU0IDE5OS4wODIgMTY0LjE1NCAyMDMuOTAzQzE2NC4xNTQgMjA4LjcyMyAxNjAuMjU3IDIxMi42MTkgMTU1LjQzNyAyMTIuNjE5WiIvPjxkZWZzPjxsaW5lYXJHcmFkaWVudCBpZD0icGFpbnQwX2xpbmVhcl8yXzQ3IiB4MT0iNDcuMjIiIHgyPSIxNDYuMzMzIiB5MT0iNDYuODk2IiB5Mj0iMTQ1LjAyIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSI+PHN0b3Agc3RvcC1jb2xvcj0iIzM4N0VCOCIvPjxzdG9wIG9mZnNldD0iMSIgc3RvcC1jb2xvcj0iIzM2Njk5NCIvPjwvbGluZWFyR3JhZGllbnQ+PGxpbmVhckdyYWRpZW50IGlkPSJwYWludDFfbGluZWFyXzJfNDciIHgxPSIxMDguMDU2IiB4Mj0iMjE0LjQ5MiIgeTE9IjEwOS45MDUiIHkyPSIyMTAuNTIyIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSI+PHN0b3Agc3RvcC1jb2xvcj0iI0ZGRTA1MiIvPjxzdG9wIG9mZnNldD0iMSIgc3RvcC1jb2xvcj0iI0ZGQzMzMSIvPjwvbGluZWFyR3JhZGllbnQ+PC9kZWZzPjwvc3ZnPgogICAgICAgIDwvZz4KICAgICAgICAgCiAgICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMzAwLCAwKSI+CiAgICAgICAgICA8c3ZnIHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiB2aWV3Qm94PSIwIDAgMjU2IDI1NiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHJlY3Qgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIHJ4PSI2MCIgZmlsbD0iIzI0MjkzOCIvPgo8cGF0aCBkPSJNMTgwLjk3NSA5MC40MTUzTDE2Ny41NjcgMTAzLjgyNEMxODkuNTA4IDEyNS43NjUgMTg5LjUwOCAxNjEuMTE1IDE2Ny41NjcgMTgyLjY1QzE0NS42MjUgMjA0LjU5MSAxMTAuMjc1IDIwNC41OTEgODguNzQwNCAxODIuNjVDNjYuNzk5MSAxNjAuNzA5IDY2Ljc5OTEgMTI1LjM1OSA4OC43NDA0IDEwMy44MjRMMTIzLjQ4MSA2OS4wODM1TDEyOC4zNTcgNjQuMjA3N1YzOEw3NS45NDEzIDkwLjQxNTNDNDYuNjg2MiAxMTkuNjcgNDYuNjg2MiAxNjYuODA0IDc1Ljk0MTMgMTk2LjA1OUMxMDUuMTk2IDIyNS4zMTQgMTUyLjMzIDIyNS4zMTQgMTgwLjk3NSAxOTYuMDU5QzIxMC4yMyAxNjYuNiAyMTAuMjMgMTE5LjY3IDE4MC45NzUgOTAuNDE1M1oiIGZpbGw9IiNFRTRDMkMiLz4KPHBhdGggZD0iTTE1NC43NyA4Ny4xNzA1QzE2MC4xNTYgODcuMTcwNSAxNjQuNTIyIDgyLjgwNDUgMTY0LjUyMiA3Ny40MTg4QzE2NC41MjIgNzIuMDMzMSAxNjAuMTU2IDY3LjY2NyAxNTQuNzcgNjcuNjY3QzE0OS4zODUgNjcuNjY3IDE0NS4wMTkgNzIuMDMzMSAxNDUuMDE5IDc3LjQxODhDMTQ1LjAxOSA4Mi44MDQ1IDE0OS4zODUgODcuMTcwNSAxNTQuNzcgODcuMTcwNVoiIGZpbGw9IiNFRTRDMkMiLz4KPC9zdmc+CgogICAgICAgIDwvZz4KICAgICAgICAgCiAgICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoNjAwLCAwKSI+CiAgICAgICAgICA8c3ZnIHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiB2aWV3Qm94PSIwIDAgMjU2IDI1NiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHJlY3Qgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIHJ4PSI2MCIgZmlsbD0iIzI0MjkzOCIvPgo8cGF0aCBkPSJNMTA0LjAyOCAxMjIuNThDOTUuMDggMTE3LjQxNCA4OC4wODcgMTA5LjQ0IDg0LjEzMzIgOTkuODk1QzgwLjE3OTQgOTAuMzQ5NiA3OS40ODU3IDc5Ljc2NjQgODIuMTU5OCA2OS43ODY2Qzg0LjgzMzkgNTkuODA2OSA5MC43MjYyIDUwLjk4ODQgOTguOTIzIDQ0LjY5ODhDMTA3LjEyIDM4LjQwOTIgMTE3LjE2MyAzNSAxMjcuNDk1IDM1QzEzNy44MjYgMzUgMTQ3Ljg3IDM4LjQwOTIgMTU2LjA2NiA0NC42OTg4QzE2NC4yNjMgNTAuOTg4NCAxNzAuMTU1IDU5LjgwNjkgMTcyLjgyOSA2OS43ODY2QzE3NS41MDQgNzkuNzY2NCAxNzQuODEgOTAuMzQ5NiAxNzAuODU2IDk5Ljg5NUMxNjYuOTAyIDEwOS40NCAxNTkuOTA5IDExNy40MTQgMTUwLjk2MiAxMjIuNThMMTM2LjgzMSA5OC4xMDQzQzE0MC4zOSA5Ni4wNDkyIDE0My4xNzIgOTIuODc2OSAxNDQuNzQ1IDg5LjA3OTVDMTQ2LjMxOCA4NS4yODIgMTQ2LjU5NCA4MS4wNzE3IDE0NS41MyA3Ny4xMDE1QzE0NC40NjYgNzMuMTMxMiAxNDIuMTIyIDY5LjYyMyAxMzguODYxIDY3LjEyMDhDMTM1LjYgNjQuNjE4NiAxMzEuNjA1IDYzLjI2MjMgMTI3LjQ5NSA2My4yNjIzQzEyMy4zODQgNjMuMjYyMyAxMTkuMzg5IDY0LjYxODYgMTE2LjEyOCA2Ny4xMjA4QzExMi44NjcgNjkuNjIzIDExMC41MjMgNzMuMTMxMiAxMDkuNDU5IDc3LjEwMTVDMTA4LjM5NSA4MS4wNzE3IDEwOC42NzEgODUuMjgyIDExMC4yNDQgODkuMDc5NUMxMTEuODE3IDkyLjg3NjkgMTE0LjU5OSA5Ni4wNDkyIDExOC4xNTkgOTguMTA0M0wxMDQuMDI4IDEyMi41OFoiIGZpbGw9IiNGRjAxMDEiLz4KPHBhdGggZD0iTTIwNC41MzMgMTMzLjk0M0MyMTMuNDgxIDEzOS4xMDkgMjIwLjQ3NCAxNDcuMDgzIDIyNC40MjcgMTU2LjYyOEMyMjguMzgxIDE2Ni4xNzMgMjI5LjA3NSAxNzYuNzU2IDIyNi40MDEgMTg2LjczNkMyMjMuNzI3IDE5Ni43MTYgMjE3LjgzNCAyMDUuNTM0IDIwOS42MzggMjExLjgyNEMyMDEuNDQxIDIxOC4xMTQgMTkxLjM5OCAyMjEuNTIzIDE4MS4wNjYgMjIxLjUyM0MxNzAuNzM0IDIyMS41MjMgMTYwLjY5MSAyMTguMTE0IDE1Mi40OTQgMjExLjgyNEMxNDQuMjk3IDIwNS41MzQgMTM4LjQwNSAxOTYuNzE2IDEzNS43MzEgMTg2LjczNkMxMzMuMDU3IDE3Ni43NTYgMTMzLjc1MSAxNjYuMTczIDEzNy43MDQgMTU2LjYyOEMxNDEuNjU4IDE0Ny4wODMgMTQ4LjY1MSAxMzkuMTA5IDE1Ny41OTkgMTMzLjk0M0wxNzEuNzMgMTU4LjQxOUMxNjguMTcgMTYwLjQ3NCAxNjUuMzg4IDE2My42NDYgMTYzLjgxNSAxNjcuNDQzQzE2Mi4yNDIgMTcxLjI0MSAxNjEuOTY3IDE3NS40NTEgMTYzLjAzIDE3OS40MjFDMTY0LjA5NCAxODMuMzkyIDE2Ni40MzggMTg2LjkgMTY5LjY5OSAxODkuNDAyQzE3Mi45NiAxOTEuOTA0IDE3Ni45NTYgMTkzLjI2MSAxODEuMDY2IDE5My4yNjFDMTg1LjE3NiAxOTMuMjYxIDE4OS4xNzIgMTkxLjkwNCAxOTIuNDMzIDE4OS40MDJDMTk1LjY5MyAxODYuOSAxOTguMDM4IDE4My4zOTIgMTk5LjEwMSAxNzkuNDIxQzIwMC4xNjUgMTc1LjQ1MSAxOTkuODg5IDE3MS4yNDEgMTk4LjMxNiAxNjcuNDQzQzE5Ni43NDMgMTYzLjY0NiAxOTMuOTYxIDE2MC40NzQgMTkwLjQwMiAxNTguNDE5TDIwNC41MzMgMTMzLjk0M1oiIGZpbGw9IiMwMTAxRkYiLz4KPHBhdGggZD0iTTEyMS44NjggMTc0LjU4OUMxMjEuODY4IDE4NC45MjEgMTE4LjQ1OSAxOTQuOTY0IDExMi4xNjkgMjAzLjE2QzEwNS44OCAyMTEuMzU3IDk3LjA2MTMgMjE3LjI1IDg3LjA4MTYgMjE5LjkyNEM3Ny4xMDE4IDIyMi41OTggNjYuNTE4NiAyMjEuOTA0IDU2Ljk3MzMgMjE3Ljk1QzQ3LjQyNzkgMjEzLjk5NiAzOS40NTM5IDIwNy4wMDMgMzQuMjg4IDE5OC4wNTZDMjkuMTIyMSAxODkuMTA4IDI3LjA1MyAxNzguNzA2IDI4LjQwMTYgMTY4LjQ2M0MyOS43NTAyIDE1OC4yMTkgMzQuNDQxMSAxNDguNzA3IDQxLjc0NjcgMTQxLjQwMUM0OS4wNTI0IDEzNC4wOTYgNTguNTY0NiAxMjkuNDA1IDY4LjgwOCAxMjguMDU2Qzc5LjA1MTQgMTI2LjcwOCA4OS40NTM2IDEyOC43NzcgOTguNDAxMiAxMzMuOTQzTDg0LjI3IDE1OC40MTlDODAuNzEwNCAxNTYuMzYzIDc2LjU3MjEgMTU1LjU0IDcyLjQ5NyAxNTYuMDc3QzY4LjQyMTkgMTU2LjYxMyA2NC42Mzc2IDE1OC40NzkgNjEuNzMxMiAxNjEuMzg2QzU4LjgyNDggMTY0LjI5MiA1Ni45NTg2IDE2OC4wNzcgNTYuNDIyMSAxNzIuMTUyQzU1Ljg4NTYgMTc2LjIyNyA1Ni43MDg4IDE4MC4zNjUgNTguNzYzOSAxODMuOTI1QzYwLjgxOTEgMTg3LjQ4NCA2My45OTE0IDE5MC4yNjYgNjcuNzg4OCAxOTEuODM5QzcxLjU4NjIgMTkzLjQxMiA3NS43OTY1IDE5My42ODggNzkuNzY2OCAxOTIuNjI0QzgzLjczNyAxOTEuNTYxIDg3LjI0NTMgMTg5LjIxNiA4OS43NDc1IDE4NS45NTVDOTIuMjQ5NiAxODIuNjk1IDkzLjYwNTkgMTc4LjY5OSA5My42MDU5IDE3NC41ODlIMTIxLjg2OFoiIGZpbGw9IiMwMUZGMDEiLz4KPC9zdmc+CgogICAgICAgIDwvZz4KICAgICAgICAgCiAgICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTAwLCAwKSI+CiAgICAgICAgICA8c3ZnIHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiB2aWV3Qm94PSIwIDAgMjU2IDI1NiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHJlY3Qgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIHJ4PSI2MCIgZmlsbD0iIzA0OTc4OSIvPgo8cGF0aCBkPSJNMTI3LjUgNDFDNzkuNzQzIDQxIDQxIDc5Ljc0MyA0MSAxMjcuNUM0MSAxNzUuMjU3IDc5Ljc0MyAyMTQgMTI3LjUgMjE0QzE3NS4yNTcgMjE0IDIxNCAxNzUuMjU3IDIxNCAxMjcuNUMyMTQgNzkuNzQzIDE3NS4yNTcgNDEgMTI3LjUgNDFaTTEyMi45OTMgMTk2LjgzOVYxNDIuNTgxSDkyLjgzMDZMMTM2LjE2NyA1OC4xNjE1VjExMi40MTlIMTY1LjIwM0wxMjIuOTkzIDE5Ni44MzlaIiBmaWxsPSJ3aGl0ZSIvPgo8L3N2Zz4KCiAgICAgICAgPC9nPgogICAgICAgICAKICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjAwLCAwKSI+CiAgICAgICAgICA8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIGZpbGw9Im5vbmUiIHZpZXdCb3g9IjAgMCAyNTYgMjU2Ij48cmVjdCB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgZmlsbD0iIzAyMzQzMCIgcng9IjYwIi8+PHBhdGggZmlsbD0iIzEwQUE1MCIgZD0iTTE3MS4xNzMgMTA3LjU5MUMxNjAuNjM2IDYxLjEwOTcgMTM4LjY3NiA0OC43MzU3IDEzMy4wNzQgMzkuOTg4NkMxMzAuNzY0IDM2LjEzNTMgMTI4LjcxNyAzMi4xMjk5IDEyNi45NDkgMjhDMTI2LjY1MyAzMi4xMjkyIDEyNi4xMDkgMzQuNzMwNyAxMjIuNTk5IDM3Ljg2MkMxMTUuNTUyIDQ0LjE0NTQgODUuNjIxNyA2OC41MzU0IDgzLjEwMjggMTIxLjM0OEM4MC43NTYgMTcwLjU5IDExOS4zMDMgMjAwLjk1MyAxMjQuMzk1IDIwNC4wOTJDMTI4LjMxMSAyMDYuMDE5IDEzMy4wOCAyMDQuMTMzIDEzNS40MDcgMjAyLjM2NEMxNTMuOTg4IDE4OS42MTIgMTc5LjM3NiAxNTUuNjE0IDE3MS4xOTMgMTA3LjU5MSIvPjxwYXRoIGZpbGw9IiNCOEM0QzIiIGQ9Ik0xMjguNTQ1IDE3Ny44NzFDMTI3LjU3NSAxOTAuMDU5IDEyNi44OCAxOTcuMTQxIDEyNC40MTYgMjA0LjEwNkMxMjQuNDE2IDIwNC4xMDYgMTI2LjAzMyAyMTUuNzA5IDEyNy4xNjkgMjI4SDEzMS4xODhDMTMyLjE0NyAyMTkuMzQ1IDEzMy42MSAyMTAuNzUzIDEzNS41NzIgMjAyLjI2OEMxMzAuMzY5IDE5OS43MDggMTI4Ljc0NSAxODguNTY2IDEyOC41NDUgMTc3Ljg3MVoiLz48cGF0aCBmaWxsPSIjMTI5MjRGIiBkPSJNMTM1LjU2NSAyMDIuMjc1QzEzMC4zMDcgMTk5Ljg0NiAxMjguNzg2IDE4OC40NjkgMTI4LjU1MiAxNzcuODcxQzEyOS44NTIgMTYwLjM4OCAxMzAuMjMxIDE0Mi44NDkgMTI5LjY4OCAxMjUuMzI2QzEyOS40MTIgMTE2LjEzMiAxMjkuODE4IDQwLjE2NzYgMTI3LjQyMyAyOS4wNDYxQzEyOS4wNjIgMzIuODEyOSAxMzAuOTQ5IDM2LjQ2NjIgMTMzLjA3NCAzOS45ODE4QzEzOC42NzYgNDguNzM1OCAxNjAuNjQzIDYxLjEwOTcgMTcxLjE3MyAxMDcuNTkxQzE3OS4zNzYgMTU1LjUzMiAxNTQuMTI2IDE4OS40NCAxMzUuNTY1IDIwMi4yNzVaIi8+PC9zdmc+CiAgICAgICAgPC9nPgogICAgICAgICAKICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNTAwLCAwKSI+CiAgICAgICAgICA8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIGZpbGw9Im5vbmUiIHZpZXdCb3g9IjAgMCAyNTYgMjU2Ij48cmVjdCB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgZmlsbD0iIzI0MjkzOCIgcng9IjYwIi8+PHBhdGggZmlsbD0iIzMzNjc5MSIgZD0iTTIwMy40OCAxNDguNjg4QzE4My4xNiAxNTIuODc4IDE4MS42ODQgMTQ1Ljk5NSAxODEuNjg0IDE0NS45OTVDMjAzLjE1IDExNC4xNDMgMjEyLjEyOSA3My43MTM0IDIwNC4zOCA2My44MjA0QzE4My4yNTkgMzYuODIwNCAxNDYuNjg5IDQ5LjU5NjIgMTQ2LjA3NyA0OS45MjY2TDE0NS44OCA0OS45NjE4QzE0MS40MTQgNDkuMDY1NiAxMzYuODczIDQ4LjU5MjQgMTMyLjMxNyA0OC41NDg1QzEyMy4xMiA0OC40MDc5IDExNi4xNDUgNTAuOTYwMiAxMTAuODQ0IDU0Ljk3NTFDMTEwLjg0NCA1NC45NzUxIDQ1LjYwNzggMjguMTAxNiA0OC42NDUzIDg4Ljc3NDNDNDkuMjkyMiAxMDEuNjg0IDY3LjEzNzUgMTg2LjUwOSA4OC40NDIyIDE2MC44NDVDOTYuMjg5MSAxNTEuNDA5IDEwMy44MTIgMTQzLjQ4NCAxMDMuODEyIDE0My40ODRDMTA3LjUzOSAxNDUuOTY2IDExMi4wMTggMTQ3LjIzMiAxMTYuNzA4IDE0Ni43NzVMMTE3LjA3MyAxNDYuNDY2QzExNi45NjYgMTQ3LjY4MSAxMTcuMDE2IDE0OC45MDUgMTE3LjIyMSAxNTAuMTA4QzExMS43MzcgMTU2LjIzOSAxMTMuMzU0IDE1Ny4zMTUgMTAyLjM4NSAxNTkuNTcyQzkxLjI4OTggMTYxLjg1NyA5Ny44MTQ4IDE2NS45MjggMTAyLjA2MiAxNjYuOTk3QzEwNy4yMjMgMTY4LjI5MSAxMTkuMTYyIDE3MC4xMTkgMTI3LjIzNCAxNTguODI3TDEyNi45MSAxNjAuMTEzQzEyOS4wNjIgMTYxLjgzNiAxMzAuNTY2IDE3MS4zMTQgMTMwLjMxMyAxNzkuOTA2QzEzMC4wNiAxODguNDk5IDEyOS44OTEgMTk0LjM5MSAxMzEuNTc5IDE5OS4wMDNDMTMzLjI2NiAyMDMuNjE2IDEzNC45NTQgMjEzLjk4IDE0OS4zNjggMjEwLjk1NkMxNjEuNDEzIDIwOC4zNzYgMTY3LjY0OSAyMDEuNjc1IDE2OC41MjggMTkwLjUyNEMxNjkuMTQ3IDE4Mi41OTIgMTcwLjUzOSAxODMuNzU5IDE3MC42MzggMTc2LjY3MkwxNzEuNzYzIDE3My4zMTFDMTczLjA0OSAxNjIuNTUzIDE3MS45NzMgMTU5LjA4NyAxNzkuMzkxIDE2MC43MDRMMTgxLjE5OCAxNjAuODY2QzE4Ni42NjIgMTYxLjExMiAxOTMuODEzIDE1OS45ODcgMTk4LjAwMyAxNTguMDM5QzIwNy4wMzggMTUzLjg0OSAyMTIuMzk2IDE0Ni44NDUgMjAzLjQ4NyAxNDguNjg4SDIwMy40OFoiLz48cGF0aCBzdHJva2U9IiNmZmYiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSI1LjAzNCIgZD0iTTE0Ni4wNyA0OC41OTYxQzE0My44MiA0OS4yOTkzIDE4Mi4zOCAzNC40OTg1IDIwNC4zMDMgNjIuNTA0QzIxMi4wMzggNzIuMzk2OSAyMDMuMDczIDExMi44MjcgMTgxLjYwNiAxNDQuNjc4TTEyOC4wOTggMTUzLjc4NEMxMjcuNTM2IDE3My43OTUgMTI4LjIzOSAxOTMuOTQ2IDEzMC4xOTQgMTk4Ljc4NEMxMzIuMTQ4IDIwMy42MjEgMTM2LjM0NiAyMTMuMTk4IDE1MC43NjcgMjEwLjExOEMxNjIuODEyIDIwNy41MzggMTY3LjE5OSAyMDIuNTM4IDE2OS4wOTggMTkxLjUwNkwxNzMuNTQ4IDE1Ni4yMzFMMTI4LjA5OCAxNTMuNzg0Wk0xMTAuODE2IDUzLjQ2ODhDMTEwLjgxNiA1My40Njg4IDQ1LjUzNzUgMjYuNzc4MiA0OC41NzUgODcuNDUwOEM0OS4yMjE5IDEwMC4zNiA2Ny4wNjcyIDE4NS4xODUgODguMzcxOSAxNTkuNTIxQzk2LjE0ODQgMTUwLjE0OCAxMDMuMTggMTQyLjgxNSAxMDMuMTggMTQyLjgxNUwxMTAuODE2IDUzLjQ2ODhaIi8+PHBhdGggc3Ryb2tlPSIjZmZmIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0iYmV2ZWwiIHN0cm9rZS13aWR0aD0iNS4wMzQiIGQ9Ik0xODEuNjEzIDE0NC42NjRDMTgxLjYxMyAxNDQuNjY0IDE4My4wMiAxNTEuNTU1IDIwMy40MSAxNDcuMzVDMjEyLjMxOSAxNDUuNTA4IDIwNi45NTQgMTUyLjUxMSAxOTcuOTI2IDE1Ni43MDJDMTkwLjUxNSAxNjAuMTQ3IDE3My44OTMgMTYxLjAyNiAxNzMuNjE5IDE1Ni4yOEMxNzIuOTE2IDE0NC4wMSAxODIuMzY2IDE0Ny43MzcgMTgxLjY4NCAxNDQuNjY0QzE4MS4wNjUgMTQxLjg5NCAxNzYuODMyIDEzOS4xOCAxNzQuMDQ4IDEzMi40MDJDMTcxLjYwOCAxMjYuNDk1IDE0MC41NzkgODEuMTQzOCAxODIuNjU0IDg3Ljg3MjdDMTg0LjIwMSA4Ny41NTYzIDE3MS42ODUgNDcuNzk0NiAxMzIuMzEgNDcuMjE4MUM5Mi45MzUyIDQ2LjY0MTUgOTQuMTc5NyA5NS42MjgyIDk0LjE3OTcgOTUuNjI4MiIvPjxwYXRoIHN0cm9rZT0iI2ZmZiIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSI1LjAzNCIgZD0iTTExNy4wOCAxNDguODY5QzExMS41OTYgMTU1IDExMy4yMTMgMTU2LjA3NiAxMDIuMjQ1IDE1OC4zMzNDOTEuMTQ5MiAxNjAuNjE4IDk3LjY3NDIgMTY0LjY4OSAxMDEuOTIxIDE2NS43NThDMTA3LjA4MiAxNjcuMDUyIDExOS4wMjEgMTY4Ljg4IDEyNy4wOTMgMTU3LjU4QzEyOS41NTQgMTU0LjEzNSAxMjcuMDc5IDE0OC42NTEgMTIzLjcwNCAxNDcuMjU5QzEyMi4wNzMgMTQ2LjU4NCAxMTkuODkzIDE0NS43NCAxMTcuMDk1IDE0OC44NzZMMTE3LjA4IDE0OC44NjlaIi8+PHBhdGggc3Ryb2tlPSIjZmZmIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiIHN0cm9rZS13aWR0aD0iNS4wMzQiIGQ9Ik0xMTYuNzIyIDE0OC43NjNDMTE2LjE1OSAxNDUuMTU2IDExNy45MDMgMTQwLjg3NCAxMTkuNzY2IDEzNS44NTRDMTIyLjU2NSAxMjguMzMxIDEyOS4wMiAxMjAuODA3IDEyMy44NTkgOTYuOTIxOUMxMjAuMDEzIDc5LjEzMjkgOTQuMTg2NyA5My4yMTY1IDk0LjE4NjcgOTUuNjI4MkM5NC4xODY3IDk4LjAzOTkgOTUuMzUzOSAxMDcuODYzIDkzLjc2NDggMTE5LjI4OEM5MS42NzY2IDEzNC4yMDkgMTAzLjI1NyAxNDYuODIzIDExNi41ODggMTQ1LjUzNiIvPjxwYXRoIGZpbGw9IiNmZmYiIHN0cm9rZT0iI2ZmZiIgc3Ryb2tlLXdpZHRoPSIxLjY4IiBkPSJNMTEwLjU3NyA5NS4yNjk1QzExMC40NTcgOTYuMDkyMiAxMTIuMDg4IDk4LjI5MyAxMTQuMjA1IDk4LjU4ODNDMTE2LjMyMSA5OC44ODM2IDExOC4xMjggOTcuMTY4IDExOC4yNDggOTYuMzM4M0MxMTguMzY3IDk1LjUwODYgMTE2LjczNiA5NC42MDg2IDExNC42MiA5NC4zMTMzQzExMi41MDMgOTQuMDE4IDExMC42ODIgOTQuNDUzOSAxMTAuNTc3IDk1LjI2OTVWOTUuMjY5NVoiLz48cGF0aCBmaWxsPSIjZmZmIiBzdHJva2U9IiNmZmYiIHN0cm9rZS13aWR0aD0iLjgzNyIgZD0iTTE3NS4wMTEgOTMuNTg5MUMxNzUuMTIzIDk0LjQxMTggMTczLjQ5OSA5Ni42MTI1IDE3MS4zODMgOTYuOTA3OUMxNjkuMjY2IDk3LjIwMzIgMTY3LjQ0NSA5NS40ODc1IDE2Ny4zNCA5NC42NTc5QzE2Ny4yMzQgOTMuODI4MiAxNjguODUyIDkyLjkyODIgMTcwLjk2OCA5Mi42MzI5QzE3My4wODQgOTIuMzM3NSAxNzQuOTA1IDkyLjc3MzUgMTc1LjAxMSA5My41ODkxWiIvPjxwYXRoIHN0cm9rZT0iI2ZmZiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiBzdHJva2Utd2lkdGg9IjUuMDM0IiBkPSJNMTgyLjU3NyA4Ny44ODY3QzE4Mi45MjggOTQuMzU1NSAxODEuMTg0IDk4Ljc1IDE4MC45NTkgMTA1LjYzNEMxODAuNjM2IDExNS42MzIgMTg1LjcyNyAxMjcuMDc5IDE3OC4wNTUgMTM4LjU0Ii8+PC9zdmc+CiAgICAgICAgPC9nPgogICAgICAgICAKICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxODAwLCAwKSI+CiAgICAgICAgICA8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIGZpbGw9Im5vbmUiIHZpZXdCb3g9IjAgMCAyNTYgMjU2Ij48cmVjdCB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgZmlsbD0iIzI0MjkzOCIgcng9IjYwIi8+PGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwXzdfMjE4KSI+PHBhdGggZmlsbD0iI0E0MUUxMSIgZD0iTTIyMC4xNjEgMTc0LjQ2OEMyMDkuNDg4IDE4MC4wMzUgMTU0LjIwNCAyMDIuNzY1IDE0Mi40MzQgMjA4Ljg5OUMxMzAuNjYzIDIxNS4wMzQgMTI0LjEyNiAyMTQuOTc2IDExNC44MjYgMjEwLjUzMkMxMDUuNTI2IDIwNi4wODkgNDYuNjk0NSAxODIuMzI2IDM2LjA5MDQgMTc3LjI1N0MzMC43ODg0IDE3NC43MjIgMjguMDEwMSAxNzIuNTkxIDI4LjAxMDEgMTcwLjU3NlYxNTAuMzZDMjguMDEwMSAxNTAuMzYgMTA0LjYwOSAxMzMuNjg1IDExNi45NzggMTI5LjI0N0MxMjkuMzQ4IDEyNC44MDkgMTMzLjYyNyAxMjQuNjUgMTQ0LjE1NyAxMjguNTA1QzE1NC42ODcgMTMyLjM1OSAyMTcuNjA2IDE0My43MTEgMjI4LjAwMyAxNDcuNTIzVjE2Ny40NTlDMjI4LjAwMyAxNjkuNDU4IDIyNS42MDcgMTcxLjcgMjIwLjE3MiAxNzQuNDc5TDIyMC4xNjEgMTc0LjQ2OFoiLz48cGF0aCBmaWxsPSIjRDgyQzIwIiBkPSJNMjIwLjE2MiAxNTQuMjQ2QzIwOS40ODggMTU5LjgxMyAxNTQuMjA0IDE4Mi41NDMgMTQyLjQzNCAxODguNjc3QzEzMC42NjMgMTk0LjgxMiAxMjQuMTI2IDE5NC43NTMgMTE0LjgyNiAxOTAuMzFDMTA1LjUyNiAxODUuODY3IDQ2LjY5NDYgMTYyLjEwMyAzNi4wOTA1IDE1Ny4wMzVDMjUuNDg2NCAxNTEuOTY2IDI1LjI3NDMgMTQ4LjQ4MyAzNS42ODIyIDE0NC40MDVMMTE2Ljk3MyAxMTIuOTMyQzEyOS4zMzggMTA4LjUgMTMzLjYyMiAxMDguMzM1IDE0NC4xNTEgMTEyLjE5QzE1NC42ODEgMTE2LjA0NSAyMDkuNjMyIDEzNy45MTYgMjIwLjAyNCAxNDEuNzg2QzIzMC40MTYgMTQ1LjY1NyAyMzAuODI0IDE0OC43MzIgMjIwLjE1MSAxNTQuMjk5TDIyMC4xNjIgMTU0LjI0NloiLz48cGF0aCBmaWxsPSIjQTQxRTExIiBkPSJNMjIwLjE2MSAxNDEuNUMyMDkuNDg4IDE0Ny4wNjcgMTU0LjIwNCAxNjkuNzk3IDE0Mi40MzQgMTc1LjkzMUMxMzAuNjYzIDE4Mi4wNjYgMTI0LjEyNiAxODIuMDA3IDExNC44MjYgMTc3LjU2NEMxMDUuNTI2IDE3My4xMjEgNDYuNjk0NSAxNDkuMzU3IDM2LjA5MDQgMTQ0LjI4OUMzMC43ODg0IDE0MS43NTQgMjguMDEwMSAxMzkuNjIzIDI4LjAxMDEgMTM3LjYwOFYxMTcuMzkxQzI4LjAxMDEgMTE3LjM5MSAxMDQuNjA5IDEwMC43MTYgMTE2Ljk3OCA5Ni4yNzg3QzEyOS4zNDggOTEuODQwOSAxMzMuNjI3IDkxLjY4MTggMTQ0LjE1NyA5NS41MzY0QzE1NC42ODcgOTkuMzkxIDIxNy42MDYgMTEwLjc0MyAyMjguMDAzIDExNC41NTVWMTM0LjQ5MUMyMjguMDAzIDEzNi40ODkgMjI1LjYwNyAxMzguNzMyIDIyMC4xNzIgMTQxLjUxTDIyMC4xNjEgMTQxLjVaIi8+PHBhdGggZmlsbD0iI0Q4MkMyMCIgZD0iTTIyMC4xNjIgMTIxLjI4M0MyMDkuNDg4IDEyNi44NSAxNTQuMjA0IDE0OS41OCAxNDIuNDM0IDE1NS43MTVDMTMwLjY2MyAxNjEuODQ5IDEyNC4xMjYgMTYxLjc5MSAxMTQuODI2IDE1Ny4zNDhDMTA1LjUyNiAxNTIuOTA0IDQ2LjY5NDYgMTI5LjE0MSAzNi4wOTA1IDEyNC4wNzJDMjUuNDg2NCAxMTkuMDAzIDI1LjI3NDMgMTE1LjUyIDM1LjY4MjIgMTExLjQ0MkwxMTYuOTczIDc5Ljk3NDhDMTI5LjMzOCA3NS41MzcgMTMzLjYyMiA3NS4zNzggMTQ0LjE1MSA3OS4yMzI2QzE1NC42ODEgODMuMDg3MSAyMDkuNjMyIDEwNC45NjMgMjIwLjAzNCAxMDguNzY1QzIzMC40MzcgMTEyLjU2NyAyMzAuODM1IDExNS43MTEgMjIwLjE2MiAxMjEuMjc4VjEyMS4yODNaIi8+PHBhdGggZmlsbD0iI0E0MUUxMSIgZD0iTTIyMC4xNjEgMTA3LjMxMkMyMDkuNDg4IDExMi44NzkgMTU0LjIwNCAxMzUuNjA5IDE0Mi40MzQgMTQxLjc0OUMxMzAuNjYzIDE0Ny44ODkgMTI0LjEyNiAxNDcuODI1IDExNC44MjYgMTQzLjM4MkMxMDUuNTI2IDEzOC45MzkgNDYuNjk0NSAxMTUuMTc1IDM2LjA5MDQgMTEwLjEwNkMzMC43ODg0IDEwNy41NzIgMjguMDEwMSAxMDUuNDQxIDI4LjAxMDEgMTAzLjQyNlY4My4xOTg1QzI4LjAxMDEgODMuMTk4NSAxMDQuNjA5IDY2LjUyMzYgMTE2Ljk3OCA2Mi4wODU4QzEyOS4zNDggNTcuNjQ4IDEzMy42MjcgNTcuNDg4OSAxNDQuMTU3IDYxLjM0MzVDMTU0LjY4NyA2NS4xOTgxIDIxNy42MDYgNzYuNTQ5OCAyMjguMDAzIDgwLjM2MTlWMTAwLjI5OEMyMjguMDAzIDEwMi4yOTcgMjI1LjYwNyAxMDQuNTM5IDIyMC4xNzIgMTA3LjMxOEwyMjAuMTYxIDEwNy4zMTJaIi8+PHBhdGggZmlsbD0iI0Q4MkMyMCIgZD0iTTIyMC4xNjIgODcuMDkwMkMyMDkuNDg4IDkyLjY1NzMgMTU0LjIwNCAxMTUuMzg3IDE0Mi40MzQgMTIxLjUyMkMxMzAuNjYzIDEyNy42NTYgMTI0LjEyNiAxMjcuNTk4IDExNC44MjYgMTIzLjE1NUMxMDUuNTI2IDExOC43MTIgNDYuNjk0NiA5NC45NDc4IDM2LjA5MDUgODkuODc5MUMyNS40ODY0IDg0LjgxMDMgMjUuMjc0MyA4MS4zMjY5IDM1LjY4MjIgNzcuMjQ5NkwxMTYuOTczIDQ1Ljc4MkMxMjkuMzM4IDQxLjM0NDIgMTMzLjYyMiA0MS4xODUxIDE0NC4xNTEgNDUuMDM5N0MxNTQuNjgxIDQ4Ljg5NDMgMjA5LjYzMiA3MC43NzA1IDIyMC4wMzQgNzQuNTcyMUMyMzAuNDM3IDc4LjM3MzYgMjMwLjgzNSA4MS41MTc3IDIyMC4xNjIgODcuMDg0OVY4Ny4wOTAyWiIvPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik0xMzIuOTk2IDc4Ljc1NTRMMTI2LjcyOSA2OC4zMzY5TDEwNi43MTkgNjYuNTM0MkwxMjEuNjUgNjEuMTQ3M0wxMTcuMTY5IDUyLjg3NjFMMTMxLjE0NiA1OC4zMzcyTDE0NC4zMjYgNTQuMDIxM0wxNDAuNzYzIDYyLjU2ODJMMTU0LjE5OSA2Ny42MDUyTDEzNi44NzIgNjkuNDA3OUwxMzIuOTk2IDc4Ljc1NTRaTTk5LjYxNDMgOTkuNDk3TDE0NS45NTQgOTIuMzgxNkwxMzEuOTU3IDExMi45MTFMOTkuNjE0MyA5OS40OTdaIi8+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTg3LjEyMjYgOTIuMDE1OEMxMDAuODAzIDkyLjAxNTggMTExLjg5NCA4Ny43MTY4IDExMS44OTQgODIuNDEzOEMxMTEuODk0IDc3LjExMDcgMTAwLjgwMyA3Mi44MTE4IDg3LjEyMjYgNzIuODExOEM3My40NDE5IDcyLjgxMTggNjIuMzUxNSA3Ny4xMTA3IDYyLjM1MTUgODIuNDEzOEM2Mi4zNTE1IDg3LjcxNjggNzMuNDQxOSA5Mi4wMTU4IDg3LjEyMjYgOTIuMDE1OFoiLz48cGF0aCBmaWxsPSIjN0EwQzAwIiBkPSJNMjAyLjExMyA4MS4wMTQxTDE3NC43MDIgOTEuODQwOEwxNzQuNjgxIDcwLjE3MTRMMjAyLjExMyA4MS4wMTQxWiIvPjxwYXRoIGZpbGw9IiNBRDIxMTUiIGQ9Ik0xNzQuNzA3IDkxLjg0MDhMMTcxLjczOCA5My4wMDcyTDE0NC4zNDggODIuMTgwNUwxNzQuNjkxIDcwLjE3NjZMMTc0LjcwNyA5MS44NDA4WiIvPjwvZz48ZGVmcz48Y2xpcFBhdGggaWQ9ImNsaXAwXzdfMjE4Ij48cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0iI2ZmZiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMjggMjgpIi8+PC9jbGlwUGF0aD48L2RlZnM+PC9zdmc+CiAgICAgICAgPC9nPgogICAgICAgIAogIDwvc3ZnPgogIA==" alt="AI and data stack" />
</p><p align="center"><b>Web & Systems</b></p>
<p align="center">
  <img src="data:image/svg+xml;base64,CiAgPHN2ZyB3aWR0aD0iNjY2Ljc1IiBoZWlnaHQ9IjQ4IiB2aWV3Qm94PSIwIDAgMzU1NiAyNTYiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHZlcnNpb249IjEuMSI+CiAgICAKICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLCAwKSI+CiAgICAgICAgICA8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIGZpbGw9Im5vbmUiIHZpZXdCb3g9IjAgMCAyNTYgMjU2Ij48cmVjdCB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgZmlsbD0iIzAwN0FDQyIgcng9IjYwIi8+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTU2LjYxMTIgMTI4Ljg0OUw1Ni41Mjk5IDEzOS4zMzNINzMuMTkwMkg4OS44NTA1TDg5Ljg1MDUgMTg2LjY3M1YyMzQuMDEySDEwMS42MzVIMTEzLjQxOVYxODYuNjczTDExMy40MTkgMTM5LjMzM0gxMzAuMDc5SDE0Ni43MzlWMTI5LjA1MkMxNDYuNzM5IDEyMy4zNjMgMTQ2LjYxOCAxMTguNjA5IDE0Ni40NTUgMTE4LjQ4N0MxNDYuMzMzIDExOC4zMjUgMTI2LjA1NiAxMTguMjQzIDEwMS40NzIgMTE4LjI4NEw1Ni43MzMxIDExOC40MDZMNTYuNjExMiAxMjguODQ5WiIvPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik0yMDYuNTY3IDExOC4xMDhDMjEzLjA2OCAxMTkuNzM0IDIxOC4wMjYgMTIyLjYxOSAyMjIuNTc3IDEyNy4zMzJDMjI0LjkzNCAxMjkuODUyIDIyOC40MjggMTM0LjQ0NCAyMjguNzEzIDEzNS41NDFDMjI4Ljc5NCAxMzUuODY2IDIxNy42NiAxNDMuMzQzIDIxMC45MTUgMTQ3LjUyOEMyMTAuNjcxIDE0Ny42OTEgMjA5LjY5NSAxNDYuNjM0IDIwOC41OTggMTQ1LjAwOUMyMDUuMzA3IDE0MC4yMTQgMjAxLjg1MyAxMzguMTQxIDE5Ni41NyAxMzcuNzc2QzE4OC44MDkgMTM3LjI0NyAxODMuODExIDE0MS4zMTEgMTgzLjg1MiAxNDguMDk3QzE4My44NTIgMTUwLjA4OCAxODQuMTM2IDE1MS4yNjYgMTg0Ljk0OSAxNTIuODkyQzE4Ni42NTUgMTU2LjQyNyAxODkuODI1IDE1OC41NCAxOTkuNzgxIDE2Mi44NDdDMjE4LjEwNyAxNzAuNzMxIDIyNS45NDkgMTc1LjkzMiAyMzAuODI2IDE4My4zMjdDMjM2LjI3MSAxOTEuNTc2IDIzNy40OSAyMDQuNzQyIDIzMy43OTIgMjE0LjUzNUMyMjkuNzI5IDIyNS4xODEgMjE5LjY1MSAyMzIuNDE0IDIwNS40NjkgMjM0LjgxMkMyMDEuMDgxIDIzNS41ODQgMTkwLjY3OCAyMzUuNDYyIDE4NS45NjUgMjM0LjYwOUMxNzUuNjg0IDIzMi43OCAxNjUuOTMyIDIyNy43MDEgMTU5LjkxOCAyMjEuMDM3QzE1Ny41NjEgMjE4LjQzNiAxNTIuOTY5IDIxMS42NSAxNTMuMjU0IDIxMS4xNjJDMTUzLjM3NSAyMTEgMTU0LjQzMiAyMTAuMzUgMTU1LjYxIDIwOS42NTlDMTU2Ljc0OCAyMDkuMDA5IDE2MS4wNTYgMjA2LjUzIDE2NS4xMTkgMjA0LjE3M0wxNzIuNDc0IDE5OS45MDZMMTc0LjAxOCAyMDIuMTgyQzE3Ni4xNzIgMjA1LjQ3MyAxODAuODg1IDIwOS45ODQgMTgzLjczIDIxMS40ODdDMTkxLjg5NyAyMTUuNzk1IDIwMy4xMTMgMjE1LjE4NSAyMDguNjM5IDIxMC4yMjhDMjEwLjk5NiAyMDguMDc0IDIxMS45NzEgMjA1LjgzOSAyMTEuOTcxIDIwMi41NDhDMjExLjk3MSAxOTkuNTgxIDIxMS42MDUgMTk4LjI4MSAyMTAuMDYxIDE5Ni4wNDZDMjA4LjA3IDE5My4yMDIgMjA0LjAwNyAxOTAuODA0IDE5Mi40NjYgMTg1LjgwNkMxNzkuMjYgMTgwLjExNyAxNzMuNTcxIDE3Ni41ODIgMTY4LjM3IDE3MC45NzRDMTY1LjM2MyAxNjcuNzI0IDE2Mi41MTggMTYyLjUyMiAxNjEuMzQgMTU4LjE3NEMxNjAuMzY1IDE1NC41NTggMTYwLjEyMSAxNDUuNDk2IDE2MC44OTMgMTQxLjgzOUMxNjMuNjE1IDEyOS4wOCAxNzMuMjQ2IDEyMC4xODEgMTg3LjE0MyAxMTcuNTM5QzE5MS42NTQgMTE2LjY4NiAyMDIuMTM3IDExNy4wMTEgMjA2LjU2NyAxMTguMTA4WiIvPjwvc3ZnPgogICAgICAgIDwvZz4KICAgICAgICAgCiAgICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMzAwLCAwKSI+CiAgICAgICAgICA8c3ZnIHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiB2aWV3Qm94PSIwIDAgMjU2IDI1NiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHJlY3Qgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIHJ4PSI2MCIgZmlsbD0iI0YwREI0RiIvPgo8cGF0aCBkPSJNNjcuMzExNyAyMTMuOTMyTDg2LjkwMjcgMjAyLjA3NkM5MC42ODIxIDIwOC43NzcgOTQuMTIwMiAyMTQuNDQ3IDEwMi4zNjcgMjE0LjQ0N0MxMTAuMjcyIDIxNC40NDcgMTE1LjI1NiAyMTEuMzU1IDExNS4yNTYgMTk5LjMyN1YxMTcuNTI5SDEzOS4zMTRWMTk5LjY2N0MxMzkuMzE0IDIyNC41ODQgMTI0LjcwOCAyMzUuOTI2IDEwMy4zOTggMjM1LjkyNkM4NC4xNTMzIDIzNS45MjYgNzIuOTgxOSAyMjUuOTU5IDY3LjMxMTMgMjEzLjkzIiBmaWxsPSIjMzIzMzMwIi8+CjxwYXRoIGQ9Ik0xNTIuMzgxIDIxMS4zNTRMMTcxLjk2OSAyMDAuMDEzQzE3Ny4xMjYgMjA4LjQzNCAxODMuODI4IDIxNC42MiAxOTUuNjg0IDIxNC42MkMyMDUuNjUzIDIxNC42MiAyMTIuMDA5IDIwOS42MzYgMjEyLjAwOSAyMDIuNzYyQzIxMi4wMDkgMTk0LjUxNCAyMDUuNDc5IDE5MS41OTIgMTk0LjQ4MSAxODYuNzgyTDE4OC40NjggMTg0LjIwM0MxNzEuMTExIDE3Ni44MTUgMTU5LjU5NyAxNjcuNTM1IDE1OS41OTcgMTQ3Ljk0NUMxNTkuNTk3IDEyOS45MDEgMTczLjM0NSAxMTYuMTUzIDE5NC44MjYgMTE2LjE1M0MyMTAuMTIgMTE2LjE1MyAyMjEuMTE4IDEyMS40ODEgMjI5LjAyMiAxMzUuNEwyMTAuMjkxIDE0Ny40MjlDMjA2LjE2NiAxNDAuMDQgMjAxLjcgMTM3LjExOSAxOTQuODI2IDEzNy4xMTlDMTg3Ljc4IDEzNy4xMTkgMTgzLjMxMiAxNDEuNTg3IDE4My4zMTIgMTQ3LjQyOUMxODMuMzEyIDE1NC42NDYgMTg3Ljc4IDE1Ny41NjggMTk4LjA5IDE2Mi4wMzdMMjA0LjEwNCAxNjQuNjE0QzIyNC41NTMgMTczLjM3OSAyMzYuMDY3IDE4Mi4zMTMgMjM2LjA2NyAyMDIuNDE4QzIzNi4wNjcgMjI0LjA3MiAyMTkuMDU1IDIzNS45MjggMTk2LjIgMjM1LjkyOEMxNzMuODYxIDIzNS45MjggMTU5LjQyNiAyMjUuMjc0IDE1Mi4zODEgMjExLjM1NCIgZmlsbD0iIzMyMzMzMCIvPgo8L3N2Zz4KCiAgICAgICAgPC9nPgogICAgICAgICAKICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDAsIDApIj4KICAgICAgICAgIDxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgZmlsbD0ibm9uZSIgdmlld0JveD0iMCAwIDI1NiAyNTYiPjxyZWN0IHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiBmaWxsPSIjMjQyOTM4IiByeD0iNjAiLz48cGF0aCBmaWxsPSIjMDBEOEZGIiBkPSJNMTI4LjAwMSAxNDYuOTUxQzEzOC4zMDUgMTQ2Ljk1MSAxNDYuNjU3IDEzOC41OTggMTQ2LjY1NyAxMjguMjk1QzE0Ni42NTcgMTE3Ljk5MiAxMzguMzA1IDEwOS42MzkgMTI4LjAwMSAxMDkuNjM5QzExNy42OTggMTA5LjYzOSAxMDkuMzQ1IDExNy45OTIgMTA5LjM0NSAxMjguMjk1QzEwOS4zNDUgMTM4LjU5OCAxMTcuNjk4IDE0Ni45NTEgMTI4LjAwMSAxNDYuOTUxWiIvPjxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgc3Ryb2tlPSIjMDBEOEZGIiBzdHJva2Utd2lkdGg9IjguOTExIiBkPSJNMTI4LjAwMiA5MC4zNjMzQzE1My4wNSA5MC4zNjMzIDE3Ni4zMTkgOTMuOTU3NSAxOTMuODY0IDk5Ljk5NzZDMjE1LjAwMyAxMDcuMjc1IDIyOCAxMTguMzA2IDIyOCAxMjguMjk1QzIyOCAxMzguNzA0IDIxNC4yMjYgMTUwLjQyMyAxOTEuNTI1IDE1Ny45NDRDMTc0LjM2MyAxNjMuNjMgMTUxLjc3OSAxNjYuNTk4IDEyOC4wMDIgMTY2LjU5OEMxMDMuNjI0IDE2Ni41OTggODAuNTM4OSAxNjMuODEyIDYzLjE4MzQgMTU3Ljg4MUM0MS4yMjU1IDE1MC4zNzYgMjggMTM4LjUwNiAyOCAxMjguMjk1QzI4IDExOC4zODcgNDAuNDA5NiAxMDcuNDQxIDYxLjI1MTUgMTAwLjE3NUM3OC44NjE3IDk0LjAzNTMgMTAyLjcwNSA5MC4zNjMzIDEyNy45OTggOTAuMzYzM0gxMjguMDAyWiIgY2xpcC1ydWxlPSJldmVub2RkIi8+PHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBzdHJva2U9IiMwMEQ4RkYiIHN0cm9rZS13aWR0aD0iOC45MTEiIGQ9Ik05NC45ODExIDEwOS40MzhDMTA3LjQ5NSA4Ny43NDAyIDEyMi4yMzIgNjkuMzc4MyAxMzYuMjMgNTcuMTk3MUMxNTMuMDk0IDQyLjUyMDYgMTY5LjE0NCAzNi43NzI4IDE3Ny43OTYgNDEuNzYyM0MxODYuODEzIDQ2Ljk2MjMgMTkwLjA4NCA2NC43NDk2IDE4NS4yNTkgODguMTcxMkMxODEuNjE0IDEwNS44NzkgMTcyLjkgMTI2LjkyNSAxNjEuMDIxIDE0Ny41MjNDMTQ4Ljg0MiAxNjguNjQxIDEzNC44OTcgMTg3LjI0NyAxMjEuMDkgMTk5LjMxNUMxMDMuNjE5IDIxNC41ODcgODYuNzI4NCAyMjAuMTE0IDc3Ljg4MzMgMjE1LjAxM0M2OS4zMDAzIDIxMC4wNjcgNjYuMDE4MSAxOTMuODQ2IDcwLjEzNTYgMTcyLjE2MUM3My42MTQ1IDE1My44MzggODIuMzQ1MSAxMzEuMzQ5IDk0Ljk3NyAxMDkuNDM4TDk0Ljk4MTEgMTA5LjQzOFoiIGNsaXAtcnVsZT0iZXZlbm9kZCIvPjxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgc3Ryb2tlPSIjMDBEOEZGIiBzdHJva2Utd2lkdGg9IjguOTExIiBkPSJNOTUuMDEyMyAxNDcuNTc4QzgyLjQ2MzMgMTI1LjkwNCA3My45MTk0IDEwMy45NjIgNzAuMzUzMSA4NS43NTE3QzY2LjA2MDIgNjMuODEwOSA2OS4wOTU0IDQ3LjAzNTUgNzcuNzQwMSA0Mi4wMzE1Qzg2Ljc0ODUgMzYuODE2MyAxMDMuNzkyIDQyLjg2NiAxMjEuNjc0IDU4Ljc0MzdDMTM1LjE5NCA3MC43NDc5IDE0OS4wNzcgODguODA1MiAxNjAuOTkgMTA5LjM4M0MxNzMuMjA0IDEzMC40ODEgMTgyLjM1OCAxNTEuODU2IDE4NS45MTkgMTY5Ljg0NEMxOTAuNDI1IDE5Mi42MDggMTg2Ljc3OCAyMTAuMDAxIDE3Ny45NDEgMjE1LjExNkMxNjkuMzY3IDIyMC4wOCAxNTMuNjc2IDIxNC44MjUgMTM2Ljk0NSAyMDAuNDI3QzEyMi44MDkgMTg4LjI2MyAxMDcuNjg1IDE2OS40NjggOTUuMDEyMyAxNDcuNTc4WiIgY2xpcC1ydWxlPSJldmVub2RkIi8+PC9zdmc+CiAgICAgICAgPC9nPgogICAgICAgICAKICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg5MDAsIDApIj4KICAgICAgICAgIDxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgZmlsbD0ibm9uZSIgdmlld0JveD0iMCAwIDI1NiAyNTYiPjxyZWN0IHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiBmaWxsPSIjMjQyOTM4IiByeD0iNjAiLz48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMTIxLjQ1MSAyOC4wNTM3QzEyMS4wMjEgMjguMDkyOCAxMTkuNjUyIDI4LjIyOTcgMTE4LjQyIDI4LjMyNzRDOTAuMDEzNyAzMC44ODg1IDYzLjQwNTcgNDYuMjE2IDQ2LjU1MzMgNjkuNzc0MkMzNy4xNjkxIDgyLjg3MjkgMzEuMTY3MiA5Ny43MzEyIDI4Ljg5OTMgMTEzLjQ2OUMyOC4wOTc4IDExOC45NjMgMjggMTIwLjU4NiAyOCAxMjguMDM0QzI4IDEzNS40ODMgMjguMDk3OCAxMzcuMTA2IDI4Ljg5OTMgMTQyLjU5OUMzNC4zMzQzIDE4MC4xNTUgNjEuMDU5NiAyMTEuNzEgOTcuMzA2IDIyMy40MDFDMTAzLjc5NyAyMjUuNDkzIDExMC42MzkgMjI2LjkyIDExOC40MiAyMjcuNzhDMTIxLjQ1MSAyMjguMTEyIDEzNC41NDkgMjI4LjExMiAxMzcuNTggMjI3Ljc4QzE1MS4wMTEgMjI2LjI5NCAxNjIuMzg5IDIyMi45NzEgMTczLjYxMSAyMTcuMjQyQzE3NS4zMzEgMjE2LjM2MyAxNzUuNjY0IDIxNi4xMjggMTc1LjQyOSAyMTUuOTMzQzE3NS4yNzMgMjE1LjgxNSAxNjcuOTQxIDIwNS45ODEgMTU5LjE0NCAxOTQuMDk1TDE0My4xNTIgMTcyLjQ5MkwxMjMuMTEyIDE0Mi44MzRDMTEyLjA4NiAxMjYuNTI5IDEwMy4wMTUgMTEzLjE5NSAxMDIuOTM2IDExMy4xOTVDMTAyLjg1OCAxMTMuMTc2IDEwMi43OCAxMjYuMzUzIDEwMi43NDEgMTQyLjQ0M0MxMDIuNjgyIDE3MC42MTUgMTAyLjY2MyAxNzEuNzQ5IDEwMi4zMTEgMTcyLjQxM0MxMDEuODAzIDE3My4zNzEgMTAxLjQxMiAxNzMuNzYyIDEwMC41OSAxNzQuMTkzQzk5Ljk2NDggMTc0LjUwNSA5OS40MTc0IDE3NC41NjQgOTYuNDY1MyAxNzQuNTY0SDkzLjA4MzFMOTIuMTgzOCAxNzMuOTk3QzkxLjU5NzMgMTczLjYyNiA5MS4xNjcyIDE3My4xMzcgOTAuODczOSAxNzIuNTdMOTAuNDYzMyAxNzEuNjlMOTAuNTAyNCAxMzIuNDkyTDkwLjU2MTEgOTMuMjczN0w5MS4xNjcyIDkyLjUxMTJDOTEuNDggOTIuMTAwNyA5Mi4xNDQ3IDkxLjU3MjggOTIuNjEzOSA5MS4zMTg2QzkzLjQxNTQgOTAuOTI3NiA5My43MjgzIDkwLjg4ODUgOTcuMTEwNSA5MC44ODg1QzEwMS4wOTkgOTAuODg4NSAxMDEuNzYzIDkxLjA0NDkgMTAyLjggOTIuMTc4OUMxMDMuMDkzIDkyLjQ5MTcgMTEzLjk0MyAxMDguODM2IDEyNi45MjUgMTI4LjUyM0MxMzkuOTA2IDE0OC4yMSAxNTcuNjU4IDE3NS4wOTIgMTY2LjM3NyAxODguMjg4TDE4Mi4yMTMgMjEyLjI3N0wxODMuMDE1IDIxMS43NDlDMTkwLjExMSAyMDcuMTM1IDE5Ny42MTkgMjAwLjU2NiAyMDMuNTYyIDE5My43MjNDMjE2LjIxMSAxNzkuMTk3IDIyNC4zNjQgMTYxLjQ4NSAyMjcuMTAxIDE0Mi41OTlDMjI3LjkwMiAxMzcuMTA2IDIyOCAxMzUuNDgzIDIyOCAxMjguMDM0QzIyOCAxMjAuNTg2IDIyNy45MDIgMTE4Ljk2MyAyMjcuMTAxIDExMy40NjlDMjIxLjY2NiA3NS45MTMgMTk0Ljk0IDQ0LjM1ODcgMTU4LjY5NCAzMi42Njc2QzE1Mi4zMDEgMzAuNTk1MyAxNDUuNDk4IDI5LjE2ODEgMTM3Ljg3MyAyOC4zMDc5QzEzNS45OTYgMjguMTEyNCAxMjMuMDczIDI3Ljg5NzMgMTIxLjQ1MSAyOC4wNTM3Wk0xNjIuMzg5IDg4LjU0MjVDMTYzLjMyNyA4OS4wMTE3IDE2NC4wOSA4OS45MTEgMTY0LjM2NCA5MC44NDk0QzE2NC41MiA5MS4zNTc3IDE2NC41NTkgMTAyLjIyOCAxNjQuNTIgMTI2LjcyNEwxNjQuNDYxIDE2MS44NzZMMTU4LjI2NCAxNTIuMzc0TDE1Mi4wNDcgMTQyLjg3M1YxMTcuMzIxQzE1Mi4wNDcgMTAwLjgwMSAxNTIuMTI1IDkxLjUxNDEgMTUyLjI0MiA5MS4wNjQ1QzE1Mi41NTUgODkuOTY5NyAxNTMuMjM5IDg5LjEwOTUgMTU0LjE3OCA4OC42MDExQzE1NC45NzkgODguMTkwNiAxNTUuMjczIDg4LjE1MTUgMTU4LjM0MiA4OC4xNTE1QzE2MS4yMzYgODguMTUxNSAxNjEuNzQ0IDg4LjE5MDYgMTYyLjM4OSA4OC41NDI1WiIvPjwvc3ZnPgogICAgICAgIDwvZz4KICAgICAgICAgCiAgICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTIwMCwgMCkiPgogICAgICAgICAgPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiBmaWxsPSJub25lIiB2aWV3Qm94PSIwIDAgMjU2IDI1NiI+PHJlY3Qgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIGZpbGw9IiMyNDI5MzgiIHJ4PSI2MCIvPjxwYXRoIGZpbGw9IiM4MUNEMzkiIGQ9Ik0xMTkuODc4IDMxLjExNjRDMTI0Ljc5NyAyOC4zMDA4IDEzMS4yMDMgMjguMjg4MyAxMzYuMTE3IDMxLjExNjRDMTYwLjgzOSA0NS4wODU1IDE4NS41NjkgNTkuMDMzMiAyMTAuMjg3IDczLjAxMDhDMjE0LjkzNyA3NS42Mjk2IDIxOC4wNDYgODAuODAzOCAyMTcuOTk5IDg2LjE2MDhWMTcwLjIwNkMyMTguMDM0IDE3NS43ODUgMjE0LjYxNyAxODEuMDgzIDIwOS43MTIgMTgzLjY0MkMxODUuMDcxIDE5Ny41MzUgMTYwLjQ0MiAyMTEuNDQ0IDEzNS44MDUgMjI1LjMzN0MxMzAuNzg2IDIyOC4yMDcgMTI0LjI1MSAyMjcuOTg2IDExOS4zODcgMjI0Ljg4QzExMiAyMjAuNTk4IDEwNC42IDIxNi4zMzYgOTcuMjEyMSAyMTIuMDU4Qzk1LjcwMjIgMjExLjE1OCA5NC4wMDA0IDIxMC40NDIgOTIuOTM0NSAyMDguOTc4QzkzLjg3NjYgMjA3LjcwOCA5NS41NjE4IDIwNy41NSA5Ni45MzA5IDIwNi45OTVDMTAwLjAxNCAyMDYuMDE0IDEwMi44NDcgMjA0LjQ0IDEwNS42NzkgMjAyLjkxM0MxMDYuMzk2IDIwMi40MjMgMTA3LjI3IDIwMi42MTEgMTA3Ljk1NyAyMDMuMDQ5QzExNC4yNzQgMjA2LjY3MSAxMjAuNTM2IDIxMC4zOTkgMTI2Ljg3NCAyMTMuOTg2QzEyOC4yMjYgMjE0Ljc2NyAxMjkuNTk1IDIxMy43MyAxMzAuNzUxIDIxMy4wODZDMTU0LjkzMSAxOTkuNDE5IDE3OS4xNDEgMTg1LjgwNSAyMDMuMzE4IDE3Mi4xMzRDMjA0LjIxNCAxNzEuNzAzIDIwNC43MDkgMTcwLjc1MiAyMDQuNjM2IDE2OS43NzFDMjA0LjY1MyAxNDIuMDQ2IDIwNC42NCAxMTQuMzE3IDIwNC42NDUgODYuNTkxOEMyMDQuNzQ3IDg1LjQ3ODUgMjA0LjEwMyA4NC40NTUgMjAzLjA5NiA4My45OTlDMTc4LjU0MSA3MC4xNzAyIDE1My45OTcgNTYuMzIwNSAxMjkuNDQ2IDQyLjQ4ODJDMTI4LjU3NSA0MS44ODkzIDEyNy40MjYgNDEuODg3OCAxMjYuNTU0IDQyLjQ4MzdDMTAyLjAwMiA1Ni4zMjA1IDc3LjQ2MzggNzAuMTgzMiA1Mi45MTI0IDg0LjAxMUM1MS45MDkyIDg0LjQ2NzUgNTEuMjM2IDg1LjQ3NDUgNTEuMzU1NCA4Ni41OTE4QzUxLjM1OTYgMTE0LjMxNyA1MS4zNTU0IDE0Mi4wNDYgNTEuMzU1NCAxNjkuNzc1QzUxLjI2ODIgMTcwLjc1NiA1MS44MDEgMTcxLjY4NyA1Mi42OTA2IDE3Mi4xMDlDNTkuMjQyMiAxNzUuODI0IDY1LjgwMjQgMTc5LjUxMyA3Mi4zNTgyIDE4My4yMTZDNzYuMDUxNiAxODUuMjAzIDgwLjU4NjMgMTg2LjM4NSA4NC42NTU1IDE4NC44NjJDODguMjQ2MyAxODMuNTc0IDkwLjc2MzMgMTc5LjkwOSA5MC42OTQ4IDE3Ni4wOTdDOTAuNzI4OCAxNDguNTM0IDkwLjY3NzggMTIwLjk2NyA5MC43MjAzIDkzLjQwNzhDOTAuNjMwOSA5Mi4xODQxIDkxLjc5MTIgOTEuMTczMSA5Mi45ODEgOTEuMjg4NUM5Ni4xMjkyIDkxLjI2NyA5OS4yODEgOTEuMjQ2MSAxMDIuNDI5IDkxLjI5N0MxMDMuNzQzIDkxLjI2NyAxMDQuNjQ3IDkyLjU4NDcgMTA0LjQ4NSA5My44MTc0QzEwNC40NzIgMTIxLjU1NSAxMDQuNTE5IDE0OS4yOTMgMTA0LjQ2NCAxNzcuMDNDMTA0LjQ3MiAxODQuNDIzIDEwMS40MzUgMTkyLjQ2NyA5NC41OTczIDE5Ni4wODRDODYuMTczNyAyMDAuNDQ3IDc1Ljc2MTkgMTk5LjUyMiA2Ny40Mzk5IDE5NS4zMzhDNjAuMjM1NSAxOTEuNzQyIDUzLjM2MDMgMTg3LjQ5OCA0Ni4yODM4IDE4My42NDZDNDEuMzY2MSAxODEuMTAxIDM3Ljk2NiAxNzUuNzgyIDM4LjAwMDYgMTcwLjIwN1Y4Ni4xNjA4QzM3Ljk0OSA4MC42OTI5IDQxLjE4MjUgNzUuNDI0OCA0NS45NzY0IDcyLjg0NDVDNzAuNjEzMyA1OC45NDA4IDk1LjI0NjEgNDUuMDI2MSAxMTkuODc4IDMxLjExNjRaIi8+PHBhdGggZmlsbD0iIzgxQ0QzOSIgZD0iTTE0MS4zNzIgODkuMzM1MUMxNTIuMTE3IDg4LjY0MzMgMTYzLjYyIDg4LjkyNTUgMTczLjI4OSA5NC4yMTg1QzE4MC43NzYgOTguMjc1NCAxODQuOTI2IDEwNi43ODkgMTg1LjA1OCAxMTUuMTA2QzE4NC44NDkgMTE2LjIyNyAxODMuNjc2IDExNi44NDYgMTgyLjYwNSAxMTYuNzY5QzE3OS40ODggMTE2Ljc2NSAxNzYuMzY5IDExNi44MTIgMTczLjI1MiAxMTYuNzQ4QzE3MS45MjkgMTE2Ljc5OSAxNzEuMTYxIDExNS41OCAxNzAuOTk1IDExNC40MTFDMTcwLjA5OSAxMTAuNDMxIDE2Ny45MjggMTA2LjQ5IDE2NC4xODMgMTA0LjU3QzE1OC40MzMgMTAxLjY5MiAxNTEuNzY3IDEwMS44MzcgMTQ1LjQ5NyAxMDEuODk3QzE0MC45MiAxMDIuMTM5IDEzNS45OTggMTAyLjUzNiAxMzIuMTIgMTA1LjIyN0MxMjkuMTQzIDEwNy4yNjYgMTI4LjIzOSAxMTEuMzgyIDEyOS4zMDEgMTE0LjY5N0MxMzAuMzAzIDExNy4wNzcgMTMzLjA1IDExNy44NDUgMTM1LjI5OSAxMTguNTUzQzE0OC4yNDggMTIxLjk0IDE2MS45NyAxMjEuNjAyIDE3NC42NzIgMTI2LjA1OUMxNzkuOTMxIDEyNy44NzYgMTg1LjA3NSAxMzEuNDA5IDE4Ni44NzUgMTM2LjkxNUMxODkuMjMgMTQ0LjI5NSAxODguMTk4IDE1My4xMTUgMTgyLjk0NyAxNTkuMDM5QzE3OC42ODkgMTYzLjkxNCAxNzIuNDg4IDE2Ni41NjggMTY2LjMwMyAxNjguMDA5QzE1OC4wNzUgMTY5Ljg0NCAxNDkuNTM2IDE2OS44OTEgMTQxLjE4IDE2OS4wNzZDMTMzLjMyMyAxNjguMTggMTI1LjE0NiAxNjYuMTE2IDExOS4wODEgMTYwLjc2M0MxMTMuODk0IDE1Ni4yNTkgMTExLjM2MSAxNDkuMjQxIDExMS42MTIgMTQyLjQ2OUMxMTEuNjcyIDE0MS4zMjUgMTEyLjgxMSAxNDAuNTI3IDExMy45MDcgMTQwLjYyMUMxMTcuMDQ2IDE0MC41OTYgMTIwLjE4NiAxNDAuNTg3IDEyMy4zMjUgMTQwLjYyNkMxMjQuNTggMTQwLjUzNiAxMjUuNTA5IDE0MS42MiAxMjUuNTc0IDE0Mi44MDJDMTI2LjE1MiAxNDYuNTkzIDEyNy41NzcgMTUwLjU3MyAxMzAuODg0IDE1Mi44MkMxMzcuMjY0IDE1Ni45MzcgMTQ1LjI3MSAxNTYuNjU1IDE1Mi41NzcgMTU2Ljc3QzE1OC42MyAxNTYuNTAyIDE2NS40MjUgMTU2LjQyMSAxNzAuMzY0IDE1Mi40MkMxNzIuOTcgMTUwLjEzOCAxNzMuNzQyIDE0Ni4zMiAxNzMuMDM4IDE0My4wMzZDMTcyLjI3NSAxNDAuMjYzIDE2OS4zNzQgMTM4Ljk3MSAxNjYuODgzIDEzOC4xMjZDMTU0LjEgMTM0LjA4MyAxNDAuMjI0IDEzNS41NSAxMjcuNTY1IDEzMC45NzdDMTIyLjQyNSAxMjkuMTYxIDExNy40NTUgMTI1LjcyNyAxMTUuNDgxIDEyMC40NDdDMTEyLjcyNiAxMTIuOTc0IDExMy45ODggMTAzLjczIDExOS43ODkgOTguMDA2MUMxMjUuNDQ1IDkyLjMxMiAxMzMuNjA5IDkwLjExOTIgMTQxLjM3MiA4OS4zMzQ2Vjg5LjMzNTEiLz48L3N2Zz4KICAgICAgICA8L2c+CiAgICAgICAgIAogICAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE1MDAsIDApIj4KICAgICAgICAgIDxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgZmlsbD0ibm9uZSIgdmlld0JveD0iMCAwIDI1NiAyNTYiPjxyZWN0IHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiBmaWxsPSIjMjQyOTM4IiByeD0iNjAiLz48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMjI4IDE4Mi45MzdDMjI1LjA4OSAxODQuMDQgMjIxLjg3NSAxODQuMDM3IDIxOC45NjUgMTgyLjkzMUMyMTYuMDU2IDE4MS44MjQgMjEzLjY1MiAxNzkuNjkgMjEyLjIwOSAxNzYuOTMyQzIwMy4xNDYgMTYzLjM2NSAxOTMuMTM4IDE1MC40MSAxODMuNTE5IDEzNy4xNzdMMTc5LjM0OCAxMzEuNjE3QzE2Ny44OTQgMTQ2Ljk2MyAxNTYuNDQgMTYxLjY5NyAxNDUuOTg3IDE3Ni45ODhDMTQ0LjYyNSAxNzkuNjI0IDE0Mi4zNTIgMTgxLjY3NSAxMzkuNTkgMTgyLjc1OUMxMzYuODI4IDE4My44NDQgMTMzLjc2NiAxODMuODg3IDEzMC45NzUgMTgyLjg4MkwxNzMuOTU1IDEyNS4yMjNMMTMzLjk3NyA3My4xMjM2QzEzNi44NTUgNzIuMDg0NSAxNDAuMDAzIDcyLjA3MDIgMTQyLjg5IDczLjA4MzJDMTQ1Ljc3NyA3NC4wOTYyIDE0OC4yMjYgNzYuMDc0NCAxNDkuODI0IDc4LjY4MzhDMTU5LjEwOSA5Mi4yNTA2IDE2OS4zOTYgMTA1LjIwNiAxNzkuNjI2IDExOC45NEMxODkuOTEzIDEwNS4zMTcgMjAwLjA4OCA5Mi4zMDYyIDIwOS41OTYgNzguODUwNkMyMTAuOTY1IDc2LjI1NzQgMjEzLjI0IDc0LjI1OCAyMTUuOTg4IDczLjIzMjhDMjE4LjczNSA3Mi4yMDc2IDIyMS43NjQgNzIuMjI4MSAyMjQuNDk3IDczLjI5MDRMMjA4Ljk4NCA5My44NjMxQzIwMi4wMzQgMTAzLjAzNyAxOTUuMTk1IDExMi4yNjcgMTg3Ljk2NyAxMjEuMjE5QzE4Ny4zODQgMTIxLjc0MSAxODYuOTE4IDEyMi4zNzkgMTg2LjU5OSAxMjMuMDkzQzE4Ni4yOCAxMjMuODA3IDE4Ni4xMTUgMTI0LjU4IDE4Ni4xMTUgMTI1LjM2MkMxODYuMTE1IDEyNi4xNDMgMTg2LjI4IDEyNi45MTYgMTg2LjU5OSAxMjcuNjNDMTg2LjkxOCAxMjguMzQ0IDE4Ny4zODQgMTI4Ljk4MiAxODcuOTY3IDEyOS41MDRDMjAxLjI1NiAxNDcuMTMgMjE0LjQzMyAxNjQuODExIDIyOCAxODIuOTM3VjE4Mi45MzdaIi8+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTI4IDEyNC41QzI5LjE2NzYgMTE4Ljk0IDI5Ljg5MDUgMTEyLjg3OSAzMS41MDI5IDEwNy4yMDhDNDEuMTIyIDczLjAxMjkgODAuMzIxNCA1OC43Nzg4IDEwNy4yODggNzkuOTYzMkMxMjMuMDc5IDkyLjM2MjQgMTI3LjAyNyAxMDkuOTMzIDEyNi4yNDkgMTI5LjcyN0gzNy4yODU1QzM1LjgzOTkgMTY1LjA5IDYxLjM2MTEgMTg2LjQ0MSA5My45OTk0IDE3NS41NDNDOTkuMjkzOCAxNzMuNjQ5IDEwNC4wMzMgMTcwLjQ2NyAxMDcuNzkgMTY2LjI4M0MxMTEuNTQ3IDE2Mi4wOTkgMTE0LjIwMiAxNTcuMDQ1IDExNS41MTcgMTUxLjU3OEMxMTcuMjQxIDE0Ni4wMTggMTIwLjAyMSAxNDUuMDczIDEyNS4zMDMgMTQ2LjY4NUMxMjQuNDMzIDE1My40NTQgMTIyLjA0IDE1OS45MzggMTE4LjMwMyAxNjUuNjQ5QzExNC41NjcgMTcxLjM2IDEwOS41ODQgMTc2LjE0OSAxMDMuNzMgMTc5LjY1N0M5NC4wNTczIDE4NC45NDcgODIuOTYgMTg3LjA0MiA3Mi4wMjQ3IDE4NS42NDRDNjEuMDg5NCAxODQuMjQ2IDUwLjg3NjMgMTc5LjQyNiA0Mi44NDU3IDE3MS44NzNDMzQuOTAxMSAxNjIuOTQgMzAuMDk3MyAxNTEuNjU0IDI5LjE2NzYgMTM5LjczNUMyOS4xNjc2IDEzNy44NDUgMjguNDQ0OCAxMzUuOTU0IDI4LjA1NTYgMTM0LjE3NUMyOC4wMTg1IDEzMC44NzYgMjggMTI3LjY1MSAyOCAxMjQuNVpNMzcuMzk2NyAxMjIuMTA5SDExNy44NTNDMTE3LjM1MiA5Ni40NzY5IDEwMS4xNzIgNzguMjk1MSA3OS41OTg2IDc4LjEyODNDNTUuNTc4NSA3Ny43OTQ3IDM4LjM5NzYgOTUuNTg3MyAzNy4zNDExIDEyMS45OThMMzcuMzk2NyAxMjIuMTA5WiIvPjwvc3ZnPgogICAgICAgIDwvZz4KICAgICAgICAgCiAgICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTgwMCwgMCkiPgogICAgICAgICAgPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiBmaWxsPSJub25lIiB2aWV3Qm94PSIwIDAgMjU2IDI1NiI+PHJlY3Qgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIGZpbGw9IiMyMzk2RUQiIHJ4PSI2MCIvPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik0xNDEuMTg3IDEyMi4xMjNIMTYxLjkwNFYxMDMuMzc5SDE0MS4xODdWMTIyLjEyM1pNMTE2LjUyNSAxMjIuMTIzSDEzNy4yNDFWMTAzLjM3OUgxMTYuNTI1VjEyMi4xMjNaTTkyLjM1NTQgMTIyLjEyM0gxMTMuMDcyVjEwMy4zNzlIOTIuMzU1NFYxMjIuMTIzWk02OC4xODU5IDEyMi4xMjNIODguNDA5M1YxMDMuMzc5SDY4LjE4NTlWMTIyLjEyM1pNNDMuNTIzMyAxMjIuMTIzSDY0LjIzOTlWMTAzLjM3OUg0My41MjMzVjEyMi4xMjNaTTY4LjE4NTkgOTkuNDMzM0g4OC40MDkzVjgwLjY4OTZINjguMTg1OVY5OS40MzMzWk05Mi4zNTU0IDk5LjQzMzNIMTEzLjA3MlY4MC42ODk2SDkyLjM1NTRWOTkuNDMzM1pNMTE2LjUyNSA5OS40MzMzSDEzNy4yNDFWODAuNjg5NkgxMTYuNTI1Vjk5LjQzMzNaTTExNi41MjUgNzYuNzQzNkgxMzcuMjQxVjU4SDExNi41MjVWNzYuNzQzNlpNMjI4IDExMy43MzhDMjI4IDExMy43MzggMjE5LjEyMSAxMDUuMzUyIDIwMC44NzEgMTA4LjMxMkMxOTguODk4IDk0LjAwNzUgMTgzLjYwNyA4NS42MjIyIDE4My42MDcgODUuNjIyMkMxODMuNjA3IDg1LjYyMjIgMTY5LjMwMyAxMDIuODg2IDE3OS42NjEgMTIyLjEyM0MxNzYuNzAyIDEyMy42MDMgMTcxLjc2OSAxMjUuNTc2IDE2NC4zNyAxMjUuNTc2SDI4LjcyNTdDMjYuMjU5NCAxMzQuOTQ4IDI2LjI1OTQgMTk3LjA5NyA5NC4zMjg0IDE5Ny4wOTdDMTQzLjE2IDE5Ny4wOTcgMTc5LjY2MSAxNzQuNDA4IDE5Ni45MjUgMTMyLjk3NEMyMjIuNTc0IDEzNC45NDggMjI4IDExMy43MzggMjI4IDExMy43MzhaIi8+PC9zdmc+CiAgICAgICAgPC9nPgogICAgICAgICAKICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgyMTAwLCAwKSI+CiAgICAgICAgICA8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIGZpbGw9Im5vbmUiIHZpZXdCb3g9IjAgMCAyNTYgMjU2Ij48cmVjdCB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgZmlsbD0iIzI0MjkzOCIgcng9IjYwIi8+PHBhdGggZmlsbD0iI0VDRUZGMSIgZD0iTTg1Ljk0OTMgMTk5LjkyNkwxMTAuNDggMjEzLjU0NkgxNDcuNTc2TDE4Mi4yNzggMTg3LjQ5MUwxOTcuODM0IDE0Ni42MzJMMTYxLjkzNSAxMDMuNDA1TDE1MS43NjQgNzkuMTI2OEwxMDIuMTA0IDgwLjkwMzJMMTAyLjcwMiA5NC41MjI4TDkzLjEyOTEgMTEyLjI4N0w3OC4xNzEzIDE0MS4zMDNMNzUuMTc5NyAxNjUuNTgxTDg1Ljk0OTMgMTk5LjkyNloiLz48cGF0aCBmaWxsPSIjMjYzMjM4IiBkPSJNMTg3LjA2NCAxMTQuNjU2QzE3Ny40OTEgMTAxLjAzNiAxNjkuNzEzIDkyLjc0NjMgMTY1LjUyNSA3NS41NzM4QzE2MS4zMzcgNTguNDAxMyAxNjYuNzIyIDYzLjEzODYgMTYzLjEzMiA0OC4zMzQ3QzE2MS4zMzcgNDAuNjM2NyAxNTguMzQ1IDM1LjMwNzMgMTU1LjM1NCAzMS4xNjIyQzE1MS43NjQgMjcuMDE3MSAxNDcuNTc2IDI0LjY0ODUgMTQ1LjE4MiAyNC4wNTYzQzEzOS43OTggMjEuMDk1NiAxMjcuMjMzIDE2LjM1ODMgMTExLjY3NyAyNC42NDg1Qzk1LjUyMjMgMzIuOTM4NyA5Ny4zMTcyIDUwLjcwMzMgMTAwLjMwOSA4Ni44MjQ4QzEwMC4zMDkgODkuMTkzNCA5OS43MTA1IDkyLjE1NDIgOTguNTEzOSA5NC41MjI4Qzk2LjEyMDYgOTkuODUyMiA5MS45MzI0IDEwNC41ODkgODguMzQyNSAxMDguNzM1Qzg0LjE1NDMgMTE0LjY1NiA3OS45NjYxIDEyMC41NzggNzYuOTc0NiAxMjcuMDkxQzY5Ljc5NDggMTQwLjcxMSA2My4yMTM0IDE1Ny44ODMgNjUuMDA4MyAxNjQuMzk3QzY3Ljk5OTkgMTYzLjgwNSAxMDUuNjk0IDIyMC42NTIgMTA1LjY5NCAyMjEuODM2QzEwOC4wODcgMjIxLjI0NCAxMTguMjU4IDIyMS4yNDQgMTI3LjIzMyAyMjEuMjQ0QzEzOS43OTggMjIwLjY1MiAxNDYuOTc3IDIyMC4wNiAxNTcuMTQ5IDIyMi40MjhDMTU3LjE0OSAyMjAuNjUyIDE1Ni41NSAyMTguODc1IDE1Ni41NSAyMTcuMDk5QzE1Ni41NSAyMTMuNTQ2IDE1Ny4xNDkgMjEwLjU4NSAxNTcuNzQ3IDIwNi40NEMxNTguMzQ1IDIwMy40NzkgMTU4Ljk0NCAyMDAuNTE5IDE1OS41NDIgMTk2Ljk2NkMxNTMuNTU5IDIwMi4yOTUgMTQyLjc4OSAyMDguMjE3IDEzMi42MTggMjA5Ljk5M0MxMjMuNjQzIDIxMS43NjkgMTA4LjY4NSAyMDguODA5IDEwMS41MDUgMTk5LjkyNkMxMDIuMTA0IDE5OS45MjYgMTAzLjMgMTk5LjkyNiAxMDMuODk5IDE5OS4zMzRDMTA1LjY5NCAxOTguNzQyIDEwNy40ODkgMTk4LjE1IDEwOC4wODcgMTk2Ljk2NkMxMDkuODgyIDE5NC4wMDUgMTA4LjY4NSAxOTEuMDQ0IDEwNy40ODkgMTg5LjI2OEMxMDYuMjkyIDE4Ny40OTEgOTcuMzE3MyAxODAuOTc3IDkzLjEyOTEgMTc3LjQyNUM4OC45NDA5IDE3My44NzIgODYuNTQ3NiAxNzIuMDk1IDg0LjE1NDQgMTY5LjcyN0M4NC4xNTQ0IDE2OS43MjcgODAuNTY0NSAxNjYuMTc0IDc5LjM2NzggMTY0Ljk4OUM3OC4xNzEyIDE2My44MDUgNzcuNTcyOSAxNjIuNjIxIDc2Ljk3NDYgMTYyLjAyOEM3NS43NzggMTU5LjA2OCA3NS4xNzk2IDE1NS41MTUgNzUuNzc4IDE1MC43NzhDNzYuMzc2MyAxNDQuMjY0IDc4Ljc2OTUgMTM4LjkzNCA4MS43NjExIDEzMy4wMTNDODIuOTU3NyAxMzAuNjQ0IDg1Ljk0OTMgMTI1LjkwNyA4NS45NDkzIDEyNS45MDdDODUuOTQ5MyAxMjUuOTA3IDc1Ljc3OCAxNTAuNzc4IDgxLjE2MjggMTU4LjQ3NkM4MS4xNjI4IDE1OC40NzYgODEuNzYxMSAxNTAuNzc4IDg0LjE1NDQgMTQzLjA4Qzg1Ljk0OTMgMTM3Ljc1IDg4Ljk0MDkgMTMwLjA1MiA5Mi41MzA3IDEyNS45MDdDOTYuMTIwNiAxMjEuNzYyIDEwNS4wOTUgMTA2LjM2NiAxMDUuNjk0IDk2Ljg5MTRDMTA1LjY5NCA5Mi43NDYzIDEwNi4yOTIgODguNjAxMiAxMDYuMjkyIDg1LjY0MDVDMTAzLjg5OSA4My4yNzE4IDE0NS43ODEgNzcuMzUwMyAxNDguMTc0IDgzLjg2NEMxNDguNzcyIDg2LjIzMjYgMTU3LjE0OSAxMDcuNTUgMTYxLjkzNSAxMTguODAxQzE2NC4zMjggMTI0LjEzMSAxNjcuMzIgMTI4Ljg2OCAxNjkuMTE1IDEzNC43ODlDMTcwLjkxIDE0MS4zMDMgMTcyLjEwNiAxNTAuMTg1IDE3Mi4xMDYgMTU5LjA2OEMxNzIuMTA2IDE2MC44NDQgMTcyLjEwNiAxNjMuODA1IDE3MS41MDggMTY2Ljc2NkMxNzIuNzA1IDE2Ni43NjYgMTk2LjAzOSAxNDEuODk1IDE2OC41MTcgMTIxLjE3QzE2OC41MTcgMTIxLjE3IDE4NS4yNjkgMTI4Ljg2OCAxODUuODY4IDE0NC4yNjRDMTg2LjQ2NiAxNTYuNjk5IDE4MS4wODEgMTY2Ljc2NiAxNzkuODg1IDE2OC41NDJDMTgwLjQ4MyAxNjguNTQyIDE5Mi40NDkgMTczLjg3MiAxOTMuMDQ3IDE3My44NzJDMTk1LjQ0MSAxNzMuODcyIDIwMC4yMjcgMTcyLjA5NSAyMDAuMjI3IDE3Mi4wOTVDMjAwLjgyNiAxNzAuMzE5IDIwMi42MiAxNjUuNTgxIDIwMi42MiAxNjMuODA1QzIwNi44MDkgMTUwLjE4NSAxOTYuNjM3IDEyOC4yNzYgMTg3LjA2NCAxMTQuNjU2VjExNC42NTZaIi8+PHBhdGggZmlsbD0iI0VDRUZGMSIgZD0iTTExMS4wNzggNzUuNTczOEMxMTUuMzc0IDc1LjU3MzggMTE4Ljg1NiA3MC4yNzE0IDExOC44NTYgNjMuNzMwN0MxMTguODU2IDU3LjE4OTkgMTE1LjM3NCA1MS44ODc2IDExMS4wNzggNTEuODg3NkMxMDYuNzgzIDUxLjg4NzYgMTAzLjMgNTcuMTg5OSAxMDMuMyA2My43MzA3QzEwMy4zIDcwLjI3MTQgMTA2Ljc4MyA3NS41NzM4IDExMS4wNzggNzUuNTczOFoiLz48cGF0aCBmaWxsPSIjRUNFRkYxIiBkPSJNMTM4LjAwMiA3Ni43NTgxQzE0My42MiA3Ni43NTgxIDE0OC4xNzQgNzAuNjYwNCAxNDguMTc0IDYzLjEzODZDMTQ4LjE3NCA1NS42MTY3IDE0My42MiA0OS41MTkgMTM4LjAwMiA0OS41MTlDMTMyLjM4NSA0OS41MTkgMTI3LjgzMSA1NS42MTY3IDEyNy44MzEgNjMuMTM4NkMxMjcuODMxIDcwLjY2MDQgMTMyLjM4NSA3Ni43NTgxIDEzOC4wMDIgNzYuNzU4MVoiLz48cGF0aCBmaWxsPSIjMjEyMTIxIiBkPSJNMTE1LjQyNCA2NC41NDExQzExNC45MjcgNjAuNjQ3NiAxMTIuNjYzIDU3LjcyNDEgMTEwLjM2OCA1OC4wMTExQzEwOC4wNzQgNTguMjk4MiAxMDYuNjE2IDYxLjY4NzIgMTA3LjExNCA2NS41ODA3QzEwNy42MTEgNjkuNDc0MSAxMDkuODc0IDcyLjM5NzcgMTEyLjE2OSA3Mi4xMTA2QzExNC40NjQgNzEuODIzNSAxMTUuOTIxIDY4LjQzNDUgMTE1LjQyNCA2NC41NDExWiIvPjxwYXRoIGZpbGw9IiMyMTIxMjEiIGQ9Ik0xMzcuNDA0IDczLjIwNTJDMTQwLjcwOSA3My4yMDUyIDE0My4zODcgNjkuNzU4NyAxNDMuMzg3IDY1LjUwNzJDMTQzLjM4NyA2MS4yNTU3IDE0MC43MDkgNTcuODA5MSAxMzcuNDA0IDU3LjgwOTFDMTM0LjEgNTcuODA5MSAxMzEuNDIxIDYxLjI1NTcgMTMxLjQyMSA2NS41MDcyQzEzMS40MjEgNjkuNzU4NyAxMzQuMSA3My4yMDUyIDEzNy40MDQgNzMuMjA1MloiLz48cGF0aCBmaWxsPSIjRkZDMTA3IiBkPSJNMjE2Ljk4IDE5NS43ODFDMjE0LjU4NyAxOTQuNTk3IDIxMC4zOTggMTkyLjgyIDIwNi44MDggMTg3LjQ5MUMyMDUuMDE0IDE4NC41MyAyMDUuNjEyIDE3Ni4yNCAyMDIuNjIgMTcyLjY4N0MyMDAuODI1IDE3MC4zMTkgMTk4LjQzMiAxNzEuNTAzIDE5Ny44MzQgMTcxLjUwM0MxOTIuNDQ5IDE3Mi42ODcgMTc5Ljg4NCAxODAuOTc3IDE3MS41MDggMTcxLjUwM0MxNzAuMzExIDE3MC4zMTkgMTY4LjUxNiAxNjguNTQyIDE2NS41MjUgMTY4LjU0MkMxNjIuNTMzIDE2OC41NDIgMTYxLjMzNyAxNjkuNzI2IDE2MC4xNCAxNzIuMDk1QzE1OC45NDMgMTc0LjQ2NCAxNTguOTQzIDE3Ni4yNCAxNTguOTQzIDE4Mi4xNjJDMTU4Ljk0MyAxODYuODk5IDE1OC45NDMgMTkyLjIyOCAxNTguMzQ1IDE5Ni4zNzNDMTU3LjE0OCAyMDYuNDQgMTU1LjM1NCAyMTIuMzYyIDE1NS4zNTQgMjE4LjI4M0MxNTUuMzU0IDIyNC43OTcgMTU3LjE0OCAyMjguOTQyIDE1OS41NDIgMjMwLjcxOEMxNjEuMzM3IDIzMi40OTUgMTY0LjMyOCAyMzMuNjc5IDE3MC45MSAyMzMuNjc5QzE3Ny40OTEgMjMzLjY3OSAxODEuNjc5IDIzMS4zMTEgMTg1Ljg2OCAyMjcuMTY1QzE4OC44NTkgMjI0LjIwNSAxOTEuMjUyIDIyMy4wMiAxOTkuNjI5IDIxNy4wOTlDMjA2LjIxIDIxMi45NTQgMjE2LjM4MiAyMDcuNjI0IDIxOC4xNzYgMjA1Ljg0OEMyMTkuMzczIDIwNC42NjQgMjIxLjE2OCAyMDQuMDcxIDIyMS4xNjggMjAwLjUxOEMyMjEuMTY4IDE5Ny41NTggMjE4Ljc3NSAxOTYuMzczIDIxNi45OCAxOTUuNzgxVjE5NS43ODFaIi8+PHBhdGggZmlsbD0iI0ZGQzEwNyIgZD0iTTk2LjcxODkgMTk3LjU1OEM5MC43MzU3IDE4OC4wODMgOTAuMTM3NCAxODYuMzA3IDg1Ljk0OTIgMTgwLjM4NUM4Mi4zNTkzIDE3NC40NjQgNzQuNTgxMyAxNjMuMjEzIDY5Ljc5NDggMTYzLjIxM0M2Ni4yMDQ5IDE2My4yMTMgNjQuNDA5OSAxNjQuOTg5IDYyLjAxNjcgMTY3LjM1OEM1OS42MjM0IDE2OS43MjYgNTcuMjMwMiAxNzUuMDU2IDUzLjA0MiAxNzguMDE3QzQ5LjQ1MjEgMTgwLjk3NyAzOS4yODA4IDE4MC4zODUgMzYuODg3NSAxODMuOTM4QzM0LjQ5NDIgMTg3LjQ5MSAzOS4yODA4IDE5Mi44MjEgMzkuMjgwOCAyMDEuNzAzQzM5LjI4MDggMjA1LjI1NiAzNi4yODkyIDIwNy42MjQgMzUuNjkwOSAyMDkuOTkzQzM1LjA5MjYgMjEyLjk1NCAzNC40OTQyIDIxNC43MyAzNS42OTA5IDIxNy4wOTlDMzguMDg0MSAyMjAuNjUyIDQxLjA3NTcgMjIxLjgzNiA2MS40MTg0IDIyNS45ODFDNzIuMTg4IDIyOC4zNSA4Mi4zNTkzIDIzNC4yNzEgODguOTQwOCAyMzQuODY0Qzk1LjUyMjIgMjM1LjQ1NiAxMDYuODkgMjM0Ljg2NCAxMDYuODkgMjE4Ljg3NUMxMDcuNDg5IDIwOS40MDEgMTAyLjEwNCAyMDcuMDMyIDk2LjcxODkgMTk3LjU1OFoiLz48cGF0aCBmaWxsPSIjRkZDMTA3IiBkPSJNMTA4LjA4NyA5MC4zNzc3QzEwNC40OTcgODguMDA5MSAxMDEuNTA1IDg1LjY0MDQgMTAxLjUwNSA4Mi4wODc1QzEwMS41MDUgNzguNTM0NiAxMDMuODk5IDc3LjM1MDMgMTA3LjQ4OSA3NC4zODk1QzEwOC4wODcgNzMuNzk3MyAxMTQuNjY4IDY3Ljg3NTggMTIxLjI1IDY3Ljg3NThDMTI3LjgzMSA2Ny44NzU4IDEzNS42MDkgNzIuMDIwOSAxMzguNjAxIDczLjIwNTJDMTQzLjk4NiA3NC4zODk1IDE0OS4zNyA3NS41NzM4IDE0OC43NzIgNzkuNzE4OUMxNDguMTc0IDg1LjY0MDQgMTQ3LjU3NiA4Ni44MjQ4IDE0MS41OTIgODkuNzg1NUMxMzcuNDA0IDkwLjk2OTggMTI5LjYyNiA5Ny40ODM1IDEyNC4yNDEgOTcuNDgzNUMxMjEuODQ4IDk3LjQ4MzUgMTE4LjI1OCA5Ny40ODM1IDExNS44NjUgOTYuODkxNEMxMTQuMDcgOTYuMjk5MiAxMTEuMDc4IDkzLjMzODUgMTA4LjA4NyA5MC4zNzc3VjkwLjM3NzdaIi8+PHBhdGggZmlsbD0iIzYzNDcwMyIgZD0iTTEwNi44OSA4NS42NDA1QzEwOC4wODcgODYuODI0OCAxMDkuODgyIDg4LjAwOTEgMTExLjY3NyA4OC42MDEyQzExMi44NzMgODkuMTkzNCAxMTQuNjY4IDg5Ljc4NTYgMTE0LjY2OCA4OS43ODU2QzExNy4wNjIgODkuNzg1NiAxMTguODU3IDg5Ljc4NTYgMTIwLjA1MyA4OS43ODU2QzEyMy4wNDUgODkuNzg1NiAxMjcuMjMzIDg4LjYwMTMgMTMxLjQyMSA4Ni4yMzI2QzEzNS42MDkgODQuNDU2MiAxMzYuMjA4IDgzLjI3MTggMTM5LjE5OSA4Mi4wODc1QzE0Mi4xOTEgODAuMzExMSAxNDUuMTgyIDc4LjUzNDYgMTQzLjk4NiA3Ny45NDI1QzE0Mi43ODkgNzcuMzUwMyAxNDEuNTkyIDc3Ljk0MjUgMTM3LjQwNCA4MC4zMTExQzEzMy44MTQgODIuNjc5NyAxMzAuODIzIDgzLjg2NCAxMjcuMjMzIDg1LjY0MDVDMTI1LjQzOCA4Ni4yMzI2IDEyMy4wNDUgODcuNDE2OSAxMjEuMjUgODcuNDE2OUMxMTkuNDU1IDg3LjQxNjkgMTE3LjY2IDg3LjQxNjkgMTE1Ljg2NSA4Ny40MTY5QzExNC4wNyA4Ny40MTY5IDExMi44NzMgODYuODI0OCAxMTEuMDc4IDg2LjIzMjZDMTA5Ljg4MiA4NS42NDA1IDEwOS4yODMgODUuMDQ4MyAxMDguNjg1IDg1LjA0ODNDMTA3LjQ4OSA4NC40NTYyIDEwNS4wOTUgODIuMDg3NSAxMDMuODk5IDgxLjQ5NTRDMTAzLjg5OSA4MS40OTU0IDEwMi43MDIgODEuNDk1NCAxMDMuMyA4Mi4wODc1QzEwNS4wOTUgODMuODY0IDEwNS42OTQgODQuNDU2MiAxMDYuODkgODUuNjQwNVoiLz48cGF0aCBmaWxsPSIjNjM0NzAzIiBkPSJNMTI0Ljg0IDcyLjYxM0MxMjUuNDM4IDczLjc5NzMgMTI2LjYzNSA3My43OTczIDEyNy4yMzMgNzQuMzg5NUMxMjcuODMxIDc0Ljk4MTYgMTI4LjQyOSA3NC45ODE2IDEyOC40MjkgNzQuOTgxNkMxMjkuMDI4IDc0LjM4OTUgMTI4LjQyOSA3My4yMDUyIDEyNy44MzEgNzMuMjA1MkMxMjcuODMxIDcyLjAyMDkgMTI0Ljg0IDcyLjAyMDkgMTI0Ljg0IDcyLjYxM1Y3Mi42MTNaIi8+PHBhdGggZmlsbD0iIzYzNDcwMyIgZD0iTTExNS4yNjcgNzMuNzk3M0MxMTUuMjY3IDc0LjM4OTUgMTE2LjQ2MyA3NC45ODE2IDExNi40NjMgNzQuMzg5NUMxMTcuMDYyIDczLjc5NzMgMTE3LjY2IDczLjIwNTIgMTE4LjI1OCA3My4yMDUyQzExOS40NTUgNzIuNjEzIDExOC44NTYgNzIuMDIwOSAxMTcuMDYyIDcyLjAyMDlDMTE1Ljg2NSA3Mi42MTMgMTE1Ljg2NSA3My4yMDUyIDExNS4yNjcgNzMuNzk3M1Y3My43OTczWiIvPjxwYXRoIGZpbGw9IiM0NTVBNjQiIGQ9Ik0xNzMuMzAzIDE3OC42MDlDMTczLjMwMyAxNzkuMjAxIDE3My4zMDMgMTc5Ljc5MyAxNzMuMzAzIDE4MC4zODVDMTc0LjUgMTgyLjc1NCAxNzcuNDkxIDE4My4zNDYgMTc5Ljg4NCAxODMuMzQ2QzE4My40NzQgMTgzLjM0NiAxODcuMDY0IDE4MC45NzcgMTg4Ljg1OSAxNzguNjA5QzE4OC44NTkgMTc4LjAxNyAxODkuNDU3IDE3Ny40MjQgMTkwLjA1NiAxNzYuODMyQzE5MS4yNTIgMTc1LjA1NiAxOTEuODUxIDE3My44NzIgMTkyLjQ0OSAxNzMuMjc5QzE5Mi40NDkgMTczLjI3OSAxOTEuODUxIDE3Mi42ODcgMTkxLjg1MSAxNzIuMDk1QzE5MS4yNTIgMTcwLjkxMSAxODkuNDU3IDE2OS43MjYgMTg3LjA2NCAxNjkuMTM0QzE4NS4yNjkgMTY4LjU0MiAxODIuMjc4IDE2Ny45NSAxODEuMDgxIDE2Ny45NUMxNzUuNjk2IDE2Ny4zNTggMTcyLjcwNSAxNjkuMTM0IDE3MC45MSAxNzAuOTExQzE3MC45MSAxNzAuOTExIDE3MS41MDggMTcwLjkxMSAxNzEuNTA4IDE3MS41MDNDMTcyLjcwNSAxNzIuNjg3IDE3My4zMDMgMTczLjg3MiAxNzMuMzAzIDE3NS42NDhDMTczLjkwMSAxNzYuODMyIDE3My4zMDMgMTc3LjQyNCAxNzMuMzAzIDE3OC42MDlWMTc4LjYwOVoiLz48L3N2Zz4KICAgICAgICA8L2c+CiAgICAgICAgIAogICAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDI0MDAsIDApIj4KICAgICAgICAgIDxzdmcgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIHZpZXdCb3g9IjAgMCAyNTYgMjU2IiBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgo8cmVjdCB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgcng9IjYwIiBmaWxsPSIjMzk0QUFCIi8+CjxwYXRoIGQ9Ik0xMzQuMDAxIDMzQzE2OS4xNDQgMzMgMTk5LjgyOCA1Mi4wODYzIDIxNi4yNjIgODAuNDU2MUwyMTYuMTAyIDgwLjE4M0wxNzQuNzUzIDEwMy45OTFDMTY2LjYwNyA5MC4xOTc3IDE1MS42NzIgODAuODg5MiAxMzQuNTQgODAuNjk3NUwxMzQuMDAxIDgwLjY5NDVDMTA3Ljg3NSA4MC42OTQ1IDg2LjY5NDUgMTAxLjg3NCA4Ni42OTQ1IDEyNy45OTlDODYuNjk0NSAxMzYuNTQzIDg4Ljk3MjMgMTQ0LjU1MiA5Mi45MzM1IDE1MS40NjlDMTAxLjA4OCAxNjUuNzA0IDExNi40MTYgMTc1LjMwNiAxMzQuMDAxIDE3NS4zMDZDMTUxLjY5MyAxNzUuMzA2IDE2Ny4xMDkgMTY1LjU4MiAxNzUuMjIyIDE1MS4xOTVMMTc1LjAyNSAxNTEuNTRMMjE2LjMxMSAxNzUuNDU4QzIwMC4wNTcgMjAzLjU4OCAxNjkuNzk0IDIyMi42MTUgMTM1LjA1OSAyMjIuOTk0TDEzNC4wMDEgMjIzQzk4Ljc0NiAyMjMgNjcuOTc1MyAyMDMuNzk2IDUxLjU4MiAxNzUuMjc2QzQzLjU3OTEgMTYxLjM1MyAzOSAxNDUuMjEyIDM5IDEyNy45OTlDMzkgNzUuNTMzNCA4MS41MzIzIDMzIDEzNC4wMDEgMzNaIiBmaWxsPSJ3aGl0ZSIvPgo8L3N2Zz4KCiAgICAgICAgPC9nPgogICAgICAgICAKICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgyNzAwLCAwKSI+CiAgICAgICAgICA8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIGZpbGw9Im5vbmUiIHZpZXdCb3g9IjAgMCAyNTYgMjU2Ij48cmVjdCB3aWR0aD0iMjU2IiBoZWlnaHQ9IjI1NiIgZmlsbD0iIzAwNTk5QyIgcng9IjYwIi8+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTExMC43NTkgMjEwLjUxN0M2NS4xMjU0IDIxMC41MTcgMjggMTczLjM5MiAyOCAxMjcuNzU5QzI4IDgyLjEyNTQgNjUuMTI1NCA0NSAxMTAuNzU5IDQ1QzE0MC4yMDQgNDUgMTY3LjY2NyA2MC44NDU4IDE4Mi40MjcgODYuMzUzM0wxNDYuNjExIDEwNy4wNzlDMTM5LjIyNCA5NC4zMTExIDEyNS40ODUgODYuMzc5MyAxMTAuNzU5IDg2LjM3OTNDODcuOTQxNiA4Ni4zNzkzIDY5LjM3OTMgMTA0Ljk0MiA2OS4zNzkzIDEyNy43NTlDNjkuMzc5MyAxNTAuNTc1IDg3Ljk0MTYgMTY5LjEzOCAxMTAuNzU5IDE2OS4xMzhDMTI1LjQ4NiAxNjkuMTM4IDEzOS4yMjUgMTYxLjIwNiAxNDYuNjEzIDE0OC40MzZMMTgyLjQyOSAxNjkuMTYxQzE2Ny42NjkgMTk0LjY3MSAxNDAuMjA2IDIxMC41MTcgMTEwLjc1OSAyMTAuNTE3WiIvPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik0xOTMuNTE3IDEyMy4xNjFIMTg0LjMyMVYxMTMuOTY1SDE3NS4xMjdWMTIzLjE2MUgxNjUuOTMxVjEzMi4zNTZIMTc1LjEyN1YxNDEuNTUySDE4NC4zMjFWMTMyLjM1NkgxOTMuNTE3VjEyMy4xNjFaIi8+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTIyOCAxMjMuMTYxSDIxOC44MDRWMTEzLjk2NUgyMDkuNjFWMTIzLjE2MUgyMDAuNDE0VjEzMi4zNTZIMjA5LjYxVjE0MS41NTJIMjE4LjgwNFYxMzIuMzU2SDIyOFYxMjMuMTYxWiIvPjwvc3ZnPgogICAgICAgIDwvZz4KICAgICAgICAgCiAgICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMzAwMCwgMCkiPgogICAgICAgICAgPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiBmaWxsPSJub25lIiB2aWV3Qm94PSIwIDAgMjU2IDI1NiI+PHJlY3Qgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIGZpbGw9IiNGMDNDMkUiIHJ4PSI2MCIvPjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF83XzI4MykiPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik0yMjQuMjI1IDExOS4wOTRMMTM2LjkwNiAzMS43NzVDMTM1LjcxMSAzMC41Nzg3IDEzNC4yOTEgMjkuNjI5OCAxMzIuNzI5IDI4Ljk4MjRDMTMxLjE2NiAyOC4zMzQ5IDEyOS40OTEgMjguMDAxNyAxMjcuOCAyOC4wMDE3QzEyNi4xMDkgMjguMDAxNyAxMjQuNDM0IDI4LjMzNDkgMTIyLjg3MSAyOC45ODI0QzEyMS4zMDkgMjkuNjI5OCAxMTkuODg5IDMwLjU3ODcgMTE4LjY5NCAzMS43NzVMMTAwLjU2OSA0OS45TDEyMy41NjkgNzIuOUMxMjguOTE5IDcxLjAyNSAxMzUuMDQ0IDcyLjMwNjIgMTM5LjMwNiA3Ni41Njg3QzE0MS4zMzUgNzguNjAxNCAxNDIuNzUyIDgxLjE2MzggMTQzLjM5NCA4My45NjMyQzE0NC4wMzYgODYuNzYyNiAxNDMuODc4IDg5LjY4NjIgMTQyLjkzNyA5Mi40TDE2NS4xMDYgMTE0LjU2OUMxNzAuNDY5IDExMi43MTkgMTc2LjY1NiAxMTMuOTEyIDE4MC45MzcgMTE4LjIwNkMxODIuMzYxIDExOS42MyAxODMuNDkgMTIxLjMyIDE4NC4yNiAxMjMuMThDMTg1LjAzIDEyNS4wNCAxODUuNDI2IDEyNy4wMzMgMTg1LjQyNiAxMjkuMDQ2QzE4NS40MjUgMTMxLjA1OSAxODUuMDI5IDEzMy4wNTIgMTg0LjI1OCAxMzQuOTEyQzE4My40ODcgMTM2Ljc3MSAxODIuMzU4IDEzOC40NjEgMTgwLjkzNCAxMzkuODg0QzE3OS41MTEgMTQxLjMwOCAxNzcuODIxIDE0Mi40MzYgMTc1Ljk2MSAxNDMuMjA2QzE3NC4xMDEgMTQzLjk3NyAxNzIuMTA4IDE0NC4zNzMgMTcwLjA5NSAxNDQuMzcyQzE2OC4wODIgMTQ0LjM3MiAxNjYuMDg4IDE0My45NzUgMTY0LjIyOSAxNDMuMjA1QzE2Mi4zNjkgMTQyLjQzNCAxNjAuNjc5IDE0MS4zMDUgMTU5LjI1NiAxMzkuODgxQzE1NC43NTYgMTM1LjM4MSAxNTMuNjQ0IDEyOC43NTYgMTU1LjkxOSAxMjMuMjEyTDEzNS4yNDQgMTAyLjUzN1YxNTYuOTQ0QzEzNi43NDUgMTU3LjY4NiAxMzguMTE2IDE1OC42NjYgMTM5LjMwNiAxNTkuODQ0QzE0MC43MjkgMTYxLjI2NyAxNDEuODU4IDE2Mi45NTYgMTQyLjYyOSAxNjQuODE2QzE0My4zOTkgMTY2LjY3NSAxNDMuNzk1IDE2OC42NjggMTQzLjc5NSAxNzAuNjgxQzE0My43OTUgMTcyLjY5NCAxNDMuMzk5IDE3NC42ODcgMTQyLjYyOSAxNzYuNTQ2QzE0MS44NTggMTc4LjQwNiAxNDAuNzI5IDE4MC4wOTYgMTM5LjMwNiAxODEuNTE5QzEzNy44ODMgMTgyLjk0MiAxMzYuMTkzIDE4NC4wNzEgMTM0LjMzNCAxODQuODQxQzEzMi40NzQgMTg1LjYxMSAxMzAuNDgxIDE4Ni4wMDggMTI4LjQ2OSAxODYuMDA4QzEyNi40NTYgMTg2LjAwOCAxMjQuNDYzIDE4NS42MTEgMTIyLjYwNCAxODQuODQxQzEyMC43NDQgMTg0LjA3MSAxMTkuMDU0IDE4Mi45NDIgMTE3LjYzMSAxODEuNTE5QzExNi4yMDYgMTgwLjA5NiAxMTUuMDc2IDE3OC40MDcgMTE0LjMwNSAxNzYuNTQ4QzExMy41MzMgMTc0LjY4OCAxMTMuMTM2IDE3Mi42OTQgMTEzLjEzNiAxNzAuNjgxQzExMy4xMzYgMTY4LjY2OCAxMTMuNTMzIDE2Ni42NzUgMTE0LjMwNSAxNjQuODE1QzExNS4wNzYgMTYyLjk1NSAxMTYuMjA2IDE2MS4yNjYgMTE3LjYzMSAxNTkuODQ0QzExOS4xMTIgMTU4LjM2OSAxMjAuNzU2IDE1Ny4yNSAxMjIuNjUgMTU2LjVWMTAxLjU4N0MxMjAuODI1IDEwMC44MzcgMTE5LjExMiA5OS43MzEyIDExNy42MzEgOTguMjQzN0MxMTUuNDc5IDk2LjA5NDMgMTE0LjAxNiA5My4zNTI2IDExMy40MjggOTAuMzY4NEMxMTIuODQxIDg3LjM4NDEgMTEzLjE1NSA4NC4yOTI0IDExNC4zMzEgODEuNDg3NUw5MS42NDM3IDU4LjgxMjVMMzEuNzY4NyAxMTguNjI1QzMwLjU3MTYgMTE5LjgyMSAyOS42MjE5IDEyMS4yNDEgMjguOTczOSAxMjIuODA0QzI4LjMyNTkgMTI0LjM2NyAyNy45OTI0IDEyNi4wNDIgMjcuOTkyNCAxMjcuNzM0QzI3Ljk5MjQgMTI5LjQyNiAyOC4zMjU5IDEzMS4xMDIgMjguOTczOSAxMzIuNjY1QzI5LjYyMTkgMTM0LjIyOCAzMC41NzE2IDEzNS42NDggMzEuNzY4NyAxMzYuODQ0TDExOS4wOTQgMjI0LjE1NkMxMjAuMjg5IDIyNS4zNTIgMTIxLjcwOSAyMjYuMzAxIDEyMy4yNzEgMjI2Ljk0OUMxMjQuODM0IDIyNy41OTYgMTI2LjUwOSAyMjcuOTI5IDEyOC4yIDIyNy45MjlDMTI5Ljg5MSAyMjcuOTI5IDEzMS41NjYgMjI3LjU5NiAxMzMuMTI5IDIyNi45NDlDMTM0LjY5MSAyMjYuMzAxIDEzNi4xMTEgMjI1LjM1MiAxMzcuMzA2IDIyNC4xNTZMMjI0LjIyNSAxMzcuMzc1QzIyNS40MjIgMTM2LjE3OSAyMjYuMzcyIDEzNC43NTkgMjI3LjAyIDEzMy4xOTZDMjI3LjY2OCAxMzEuNjMzIDIyOC4wMDEgMTI5Ljk1OCAyMjguMDAxIDEyOC4yNjZDMjI4LjAwMSAxMjYuNTc0IDIyNy42NjggMTI0Ljg5OCAyMjcuMDIgMTIzLjMzNUMyMjYuMzcyIDEyMS43NzIgMjI1LjQyMiAxMjAuMzUyIDIyNC4yMjUgMTE5LjE1NiIvPjwvZz48ZGVmcz48Y2xpcFBhdGggaWQ9ImNsaXAwXzdfMjgzIj48cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0iI2ZmZiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMjggMjgpIi8+PC9jbGlwUGF0aD48L2RlZnM+PC9zdmc+CiAgICAgICAgPC9nPgogICAgICAgICAKICAgICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzMzAwLCAwKSI+CiAgICAgICAgICA8c3ZnIHdpZHRoPSIyNTYiIGhlaWdodD0iMjU2IiB2aWV3Qm94PSIwIDAgMjU2IDI1NiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHJlY3Qgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIHJ4PSI2MCIgZmlsbD0iIzI0MjkzOCIvPgo8cGF0aCBkPSJNMTI4IDM0TDIyMyAxOTguODUzSDMzTDEyOCAzNFoiIGZpbGw9IndoaXRlIi8+Cjwvc3ZnPgoKICAgICAgICA8L2c+CiAgICAgICAgCiAgPC9zdmc+CiAg" alt="Web and systems stack" />
</p><br><p align="center">
  <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMzUuMjUiIGhlaWdodD0iMjgiIHJvbGU9ImltZyIgYXJpYS1sYWJlbD0iRk9DVVM6IFhSIHwgQUkgfCBGVUxMLVNUQUNLIj48dGl0bGU+Rk9DVVM6IFhSIHwgQUkgfCBGVUxMLVNUQUNLPC90aXRsZT48ZyBzaGFwZS1yZW5kZXJpbmc9ImNyaXNwRWRnZXMiPjxyZWN0IHdpZHRoPSI2NC4yNSIgaGVpZ2h0PSIyOCIgZmlsbD0iIzU1NSIvPjxyZWN0IHg9IjY0LjI1IiB3aWR0aD0iMTcxIiBoZWlnaHQ9IjI4IiBmaWxsPSIjMTYxYjIyIi8+PC9nPjxnIGZpbGw9IiNmZmYiIHRleHQtYW5jaG9yPSJtaWRkbGUiIGZvbnQtZmFtaWx5PSJWZXJkYW5hLEdlbmV2YSxEZWphVnUgU2FucyxzYW5zLXNlcmlmIiB0ZXh0LXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIiBmb250LXNpemU9IjEwMCI+PHRleHQgdHJhbnNmb3JtPSJzY2FsZSguMSkiIHg9IjMyMS4yNSIgeT0iMTc1IiB0ZXh0TGVuZ3RoPSI0MDIuNSI+Rk9DVVM8L3RleHQ+PHRleHQgdHJhbnNmb3JtPSJzY2FsZSguMSkiIHg9IjE0OTcuNSIgeT0iMTc1IiB0ZXh0TGVuZ3RoPSIxNDcwIiBmb250LXdlaWdodD0iYm9sZCI+WFIgfCBBSSB8IEZVTEwtU1RBQ0s8L3RleHQ+PC9nPjwvc3ZnPg==" alt="Current focus" />
  <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMTAiIGhlaWdodD0iMjgiIHJvbGU9ImltZyIgYXJpYS1sYWJlbD0iT1BFTiBUTzogRlJFRUxBTkNFICZhbXA7IENPTExBQk9SQVRJT04iPjx0aXRsZT5PUEVOIFRPOiBGUkVFTEFOQ0UgJmFtcDsgQ09MTEFCT1JBVElPTjwvdGl0bGU+PGcgc2hhcGUtcmVuZGVyaW5nPSJjcmlzcEVkZ2VzIj48cmVjdCB3aWR0aD0iNzcuNzUiIGhlaWdodD0iMjgiIGZpbGw9IiM1NTUiLz48cmVjdCB4PSI3Ny43NSIgd2lkdGg9IjIzMi4yNSIgaGVpZ2h0PSIyOCIgZmlsbD0iI2U4MTkyYyIvPjwvZz48ZyBmaWxsPSIjZmZmIiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmb250LWZhbWlseT0iVmVyZGFuYSxHZW5ldmEsRGVqYVZ1IFNhbnMsc2Fucy1zZXJpZiIgdGV4dC1yZW5kZXJpbmc9Imdlb21ldHJpY1ByZWNpc2lvbiIgZm9udC1zaXplPSIxMDAiPjx0ZXh0IHRyYW5zZm9ybT0ic2NhbGUoLjEpIiB4PSIzODguNzUiIHk9IjE3NSIgdGV4dExlbmd0aD0iNTM3LjUiPk9QRU4gVE88L3RleHQ+PHRleHQgdHJhbnNmb3JtPSJzY2FsZSguMSkiIHg9IjE5MzguNzUiIHk9IjE3NSIgdGV4dExlbmd0aD0iMjA4Mi41IiBmb250LXdlaWdodD0iYm9sZCI+RlJFRUxBTkNFICZhbXA7IENPTExBQk9SQVRJT048L3RleHQ+PC9nPjwvc3ZnPg==" alt="Open to freelance and collaboration" />
</p><p align="center">
  <b>Build thoughtfully. Measure honestly. Ship reliably.</b>
</p><p align="center">
  <img
    width="100%"
    src="data:image/svg+xml;base64,CiAgICAgIDxzdmcKICAgICAgICB3aWR0aD0iODU0IgogICAgICAgIGhlaWdodD0iMTQwIgogICAgICAgIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIKICAgICAgICB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIKICAgICAgICBzdHlsZT0iei1pbmRleDoxO3Bvc2l0aW9uOnJlbGF0aXZlIgogICAgICAgIHZpZXdCb3g9IjAgMCA4NTQgMTQwIgogICAgICA+CiAgICAgICAgPHN0eWxlPgogICAgICAudGV4dCB7ICAgZm9udC1zaXplOiA3MHB4OyAgIGZvbnQtd2VpZ2h0OiA3MDA7ICAgZm9udC1mYW1pbHk6IC1hcHBsZS1zeXN0ZW0sQmxpbmtNYWNTeXN0ZW1Gb250LFNlZ29lIFVJLEhlbHZldGljYSxBcmlhbCxzYW5zLXNlcmlmLEFwcGxlIENvbG9yIEVtb2ppLFNlZ29lIFVJIEVtb2ppOyAgfSAuZGVzYyB7ICAgZm9udC1zaXplOiAyMHB4OyAgIGZvbnQtd2VpZ2h0OiA1MDA7ICAgZm9udC1mYW1pbHk6IC1hcHBsZS1zeXN0ZW0sQmxpbmtNYWNTeXN0ZW1Gb250LFNlZ29lIFVJLEhlbHZldGljYSxBcmlhbCxzYW5zLXNlcmlmLEFwcGxlIENvbG9yIEVtb2ppLFNlZ29lIFVJIEVtb2ppOyAgfSBwYXRoIHsgICB0cmFuc2Zvcm06IHJvdGF0ZSgxODBkZWcpOyAgIHRyYW5zZm9ybS1vcmlnaW46IDUwJSA1MCU7ICB9IAogICAgICAudGV4dCwgLmRlc2MgeyAgIGFuaW1hdGlvbjogdHdpbmtsaW5nIDRzIGVhc2UtaW4tb3V0IGluZmluaXRlOyAgfSBAa2V5ZnJhbWVzIHR3aW5rbGluZyB7ICAgNDAlIHsgICAgIG9wYWNpdHk6IDE7ICAgfSAgIDUwJSB7ICAgICBvcGFjaXR5OiAwLjU7ICAgfSAgIDYwJSB7ICAgICBvcGFjaXR5OiAxOyAgIH0gICA3MCUgeyAgICAgb3BhY2l0eTogMC41OyAgIH0gICA4MCUgeyAgICAgb3BhY2l0eTogMTsgICB9ICB9IAogICAgPC9zdHlsZT4KICAgICAgICA8ZGVmcz4KICAgICAgICAgICAgICA8bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhciIgeDE9IjAlIiB5MT0iMCUiIHgyPSIxMDAlIiB5Mj0iMCUiPgogICAgICAgICAgICAgICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iIzA1MDcwQSIvPjxzdG9wIG9mZnNldD0iNTUlIiBzdG9wLWNvbG9yPSIjMTExODI3Ii8+PHN0b3Agb2Zmc2V0PSIxMDAlIiBzdG9wLWNvbG9yPSIjRTgxOTJDIi8+CiAgICAgICAgICAgICAgPC9saW5lYXJHcmFkaWVudD4KICAgICAgICAgICAgPC9kZWZzPgogICAgICAgIAogICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg0MjcsIDcwKSBzY2FsZSgxLCAxKSB0cmFuc2xhdGUoLTQyNywgLTcwKSI+CiAgICAgICAgPHBhdGggZD0iIiBmaWxsPSJ1cmwoI2xpbmVhcikiIG9wYWNpdHk9IjAuNCIgPgogICAgICAgICAgPGFuaW1hdGUKICAgICAgICAgICAgICBhdHRyaWJ1dGVOYW1lPSJkIgogICAgICAgICAgICAgIGR1cj0iMjBzIgogICAgICAgICAgICAgIHJlcGVhdENvdW50PSJpbmRlZmluaXRlIgogICAgICAgICAgICAgIGtleVRpbWVzPSIwOzAuMzMzOzAuNjY3OzEiCiAgICAgICAgICAgICAgY2FsY21vZD0ic3BsaW5lIgogICAgICAgICAgICAgIGtleVNwbGluZXM9IjAuMiAwIDAuMiAxOzAuMiAwIDAuMiAxOzAuMiAwIDAuMiAxIgogICAgICAgICAgICAgIGJlZ2luPSIwcyIKICAgICAgICAgICAgICB2YWx1ZXM9Ik0wIDBMIDAgNjBRIDIxMy41IDEwMCA0MjcgNzBUIDg1NCA5NUwgODU0IDAgWjtNMCAwTCAwIDg1USAyMTMuNSAxMDAgNDI3IDgwVCA4NTQgNzBMIDg1NCAwIFo7TTAgMEwgMCAxMDVRIDIxMy41IDc1IDQyNyAxMDVUIDg1NCA3MEwgODU0IDAgWjtNMCAwTCAwIDYwUSAyMTMuNSAxMDAgNDI3IDcwVCA4NTQgOTVMIDg1NCAwIFoiPgogICAgICAgICAgPC9hbmltYXRlPgogICAgICAgIDwvcGF0aD4KICAgICAgICA8cGF0aCBkPSIiIGZpbGw9InVybCgjbGluZWFyKSIgb3BhY2l0eT0iMC40IiA+CiAgICAgICAgICA8YW5pbWF0ZQogICAgICAgICAgICBhdHRyaWJ1dGVOYW1lPSJkIgogICAgICAgICAgICBkdXI9IjIwcyIKICAgICAgICAgICAgcmVwZWF0Q291bnQ9ImluZGVmaW5pdGUiCiAgICAgICAgICAgIGtleVRpbWVzPSIwOzAuMzMzOzAuNjY3OzEiCiAgICAgICAgICAgIGNhbGNtb2Q9InNwbGluZSIKICAgICAgICAgICAga2V5U3BsaW5lcz0iMC4yIDAgMC4yIDE7MC4yIDAgMC4yIDE7MC4yIDAgMC4yIDEiCiAgICAgICAgICAgIGJlZ2luPSItMTBzIgogICAgICAgICAgICB2YWx1ZXM9Ik0wIDBMIDAgNzVRIDIxMy41IDEyMCA0MjcgOTBUIDg1NCAxMDBMIDg1NCAwIFo7TTAgMEwgMCA5MFEgMjEzLjUgNjAgNDI3IDYwVCA4NTQgODBMIDg1NCAwIFo7TTAgMEwgMCA4NVEgMjEzLjUgNjUgNDI3IDkwVCA4NTQgMTA1TCA4NTQgMCBaO00wIDBMIDAgNzVRIDIxMy41IDEyMCA0MjcgOTBUIDg1NCAxMDBMIDg1NCAwIFoiPgogICAgICAgICAgPC9hbmltYXRlPgogICAgICAgIDwvcGF0aD4KICAgICAgPC9nPgogICAgICAgICAKICAgICAgICAKICAgICAgPC9zdmc+CiAgICA="
    alt="Footer"
  />
</p>
</article></body></html>

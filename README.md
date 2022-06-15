<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>CSE-3523_(Microprocessor)</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	text-indent: -1.7em;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="8cfa116b-8125-4ad6-b138-924b2e6186ac" class="page sans"><header><img class="page-cover-image" src="https://www.intel.com/content/dam/www/public/us/en/newsroom/posts/galleries/2022-ces/ces-overview-feat-16x9.jpg" style="object-position:center 50%"/><div class="page-header-icon page-header-icon-with-cover"><img class="icon" src="https://cdn-icons-png.flaticon.com/512/1250/1250593.png"/></div><h1 class="page-title">CSE-3523_(Microprocessor)</h1></header><div class="page-body"><h3 id="35550e0d-bced-4e76-87f7-9f83d55e066a" class=""><mark class="highlight-yellow">What is Microprocessor?</mark></h3><p id="0ef4223a-bd5a-432a-b20d-d88a0cf3051e" class="">Ans: The microprocessor is useful in very <mark class="highlight-red">intensive</mark> processes. It only contains CPU but there are many other parts needed to work with the CPU to complete a process. These all other parts are connected externally.</p><p id="f6528205-9465-4c3e-aae6-e7075ae213aa" class="">……………………………………………………………</p><h3 id="cb8263a7-5d7f-4c56-aec7-4dff3b74bade" class="">What is <mark class="highlight-yellow">interrupt </mark>?</h3><p id="77c4ec1c-8441-4a4b-a00a-1e8e885f3f19" class="">Ans: A interrupt is a <mark class="highlight-red">signal</mark> from a device attached to a computer that causes the main program to stop and figure at what to do next. Simply, assigned  that gets attention of the CPU.</p><p id="6da4f72a-c624-4def-8747-ec53bf690fab" class="">……………………………………………………………</p><h3 id="f3dd4561-8126-4321-a4eb-bde0af8ab751" class=""><mark class="highlight-yellow">Hardware interrupt:</mark></h3><p id="faa7e749-13ed-4579-98ff-2bd26dcfbc81" class="">Hardware interrupt is caused by <mark class="highlight-yellow">any peripheral</mark> <mark class="highlight-yellow">device</mark> by sending a signal through a specified pin to the microprocessor.</p><p id="2653c86a-4346-48e9-841e-d98132ea2160" class="">The 8086 has <mark class="highlight-orange">two hardware interrupt pins</mark>, i.e. <mark class="highlight-orange">NMI </mark>and <mark class="highlight-orange">INTR</mark>. NMI is a non-maskable interrupt and INTR is a maskable interrupt having lower priority. One more interrupt pin associated is <mark class="highlight-orange">INTA called interrupt acknowledge</mark>.</p><p id="c0f2c126-22fd-4a09-bf7f-e478d7aa7539" class="">……………………………………………………………</p><h3 id="46e491b9-f160-457e-82ca-35f08dce84e6" class=""><mark class="highlight-yellow">NMI(Non-maskable interrupt):</mark></h3><p id="06bc820f-05b2-4982-bd65-f17a64af40f8" class="">It is a single non-maskable interrupt pin having higher priority than the maskable interrupt request pin and it is of type 2 interrupt when this interrupt is activated these action takes place.<div class="indented"><ul id="08a09c28-ab02-47ec-9045-44283d43c44c" class="bulleted-list"><li style="list-style-type:disc">Completes the current instruction that is in progress.</li></ul><ul id="106c3445-8d8e-4bc1-8983-7d84e6277a86" class="bulleted-list"><li style="list-style-type:disc">Pushes the flag register values on to the stack.</li></ul></div></p><p id="114649c7-0d76-4a89-94ae-491a003dac62" class="">……………………………………………………………</p><h3 id="3d210169-0785-47c3-86a9-7b3559696cf4" class="">Purpose of Interrupt:</h3><ol type="1" id="e3aa4fee-1eab-436f-81d8-cc1af3f6247a" class="numbered-list" start="1"><li>Interrupt are useful when interfacing I/O devices at relatively low data transfer rates, such as keyboard inputs.</li></ol><ol type="1" id="3a52859a-0df9-4091-9954-11359e31adde" class="numbered-list" start="2"><li>Interrupt processing allows while the keyboard execute other software while the keyboard operation is thinking about what to type next.</li></ol><p id="d8b62d80-b2fa-40ad-ad58-d46ba174b0d9" class="">……………………………………………………………</p><h3 id="3480d4a1-aa68-45fe-8d2b-5611f8239314" class="">A timeline that indicates interrupt</h3><p id="15ec3795-9880-4300-bbde-4f3142cacd82" class="">A timeline shows typing on a keyboard, a printer removing data from memory and a program </p><figure id="02d0b835-246c-44b6-b6ba-b00747e4df42" class="image"><a href="CSE-3523_(Microprocessor)%2002d0b835246c44b6b6bab00747e4df42/Untitled.png"><img style="width:790px" src="CSE-3523_(Microprocessor)%2002d0b835246c44b6b6bab00747e4df42/Untitled.png"/></a></figure><p id="9e1644ed-a184-4997-aca6-da9ce4f3bfa2" class="">……………………………………………………………</p><h3 id="af69dcdc-61e6-449c-92be-8f1c9c70dd45" class="">Operation of a real mode interrupt:</h3><p id="e0ab9ad3-f9b1-4219-a213-a2a46de6e6ef" class="">While the microprocessor completes executing the current instruction, this determines whether an interrupt is active through checking</p><ol type="1" id="9173b637-0b67-48b4-8eb7-c77802bb1fc3" class="numbered-list" start="1"><li>Instruction execution,</li></ol><ol type="1" id="ac8be8a3-7fcd-450d-be64-bc6f655037cc" class="numbered-list" start="2"><li>Single-step,</li></ol><ol type="1" id="503bc351-5c10-4e71-b96d-d2861c3fc5f5" class="numbered-list" start="3"><li>NMI,</li></ol><ol type="1" id="9d0dc872-cc65-4bf5-9c6a-69098070ec10" class="numbered-list" start="4"><li>Co-processor segment overrun,</li></ol><ol type="1" id="1595cdd4-8865-456a-be11-1efea0e0a053" class="numbered-list" start="5"><li>INTR, and</li></ol><ol type="1" id="539552b7-d0a5-49bb-9552-c8587cc055ac" class="numbered-list" start="6"><li>INT instruction in the order presented.</li></ol><p id="5f6bd60c-bc0b-4966-8aeb-254ec73b8d23" class="">……………………………………………………………</p><h3 id="1a9a307b-a887-404f-9118-0ccb96644015" class="">Operation of a real mode interrupt:</h3><ol type="1" id="ede019b1-0873-4037-b002-a73c46f46099" class="numbered-list" start="1"><li>Complete the current instruction</li></ol><ol type="1" id="3a1a4e9c-6040-4f4a-a3b4-6aa57d1582b3" class="numbered-list" start="2"><li>The contents of the flag register are pushed onto the stack</li></ol><ol type="1" id="fc420f72-621c-45c8-97b2-781d25e5386f" class="numbered-list" start="3"><li>Both of the interrupt(IF) flags and trap(TF) flags are  cleared. This disables the INTR</li></ol><p id="c3f50b84-65ff-4f39-9824-0c8ee68283b8" class="">……………………………………………………………</p><h3 id="bd380675-451e-4ed9-b099-4fee1553af39" class=""><strong>Draw and discuss power failure detection circuit interrupt NMI.</strong></h3><p id="bea07b1f-89a9-454d-9976-6e3225017434" class="">The non-maskable interrupt (NMI) is an edge-triggered input that requests an interrupt upon the positive-edge. Then after a positive edge, the NMI pin should remain logic 1 till it is recognized through the microprocessor.</p><p id="3c92b7f4-d5cb-4ac8-9e96-e90e95800a1b" class="">The NMI input is frequently used for parity errors and other main system faults, like power failures. Power failure is simply detected through monitoring the AC power line and causing an NMI interrupt when AC power drops out. Within response to that type of interrupt, the microprocessor stores all of the internal register into a battery backed-up-memory or an EEPROM. The below figure demonstrates a power failure detection circuit which provides a logic 1 to the NMI input while ever AC power is interrupted.</p><figure id="f9158acb-72cb-4445-a0c7-25bf6e1c4d9f" class="image"><a href="CSE-3523_(Microprocessor)%2002d0b835246c44b6b6bab00747e4df42/WhatsApp_Image_2022-06-15_at_1.43.25_PM.jpeg"><img style="width:1280px" src="CSE-3523_(Microprocessor)%2002d0b835246c44b6b6bab00747e4df42/WhatsApp_Image_2022-06-15_at_1.43.25_PM.jpeg"/></a></figure><p id="241cb78f-9965-4142-bb69-6d3cb5f77527" class="">……………………………………………………………</p><h3 id="9e94c6eb-aa07-496e-a9b0-9de101075f73" class=""><strong>Difference between Hardware Interrupt and Software Interrupt :</strong></h3><table id="5cc8deff-4b2a-4884-a69e-64a4b987b17a" class="simple-table"><tbody><tr id="7b90825f-a7c6-4604-a443-1b74a6c206bb"><td id="TANh" class=""><strong>Hardware Interrupt</strong></td><td id="MOeo" class=""><strong>Software Interrupt</strong></td></tr><tr id="aa84cbad-e27c-41e6-b15e-73aa35b04105"><td id="TANh" class="">Hardware interrupt is an interrupt generated from an external device or hardware.</td><td id="MOeo" class="">Software interrupt is the interrupt that is generated by any internal system of the computer.</td></tr><tr id="8b23d1d5-946a-4095-8026-3ad67cafbf2a"><td id="TANh" class="">It do not increment the program counter.</td><td id="MOeo" class="">It increment the program counter.</td></tr><tr id="89df2104-d713-4b23-8df3-b07fd5531cc3"><td id="TANh" class="">Hardware interrupt can be invoked with some external device such as request to start an I/O or occurrence of a hardware failure.</td><td id="MOeo" class="">Software interrupt can be invoked with the help of INT instruction.</td></tr><tr id="b648c01f-4aff-4d7e-8279-0f48bbe22d92"><td id="TANh" class="">It has lowest priority than software interrupts</td><td id="MOeo" class="">It has highest priority among all interrupts.</td></tr><tr id="b2564b7e-76f8-4bc1-90e5-468987d0b2e4"><td id="TANh" class="">Hardware interrupt is triggered by external hardware and is considered one of the ways to communicate with the outside peripherals, hardware.</td><td id="MOeo" class="">Software interrupt is triggered by software and considered one of the ways to communicate with kernel or to trigger system calls, especially during error or exception handling.</td></tr><tr id="f0e661d5-e2d4-4cd2-8968-4c9b44ef5c80"><td id="TANh" class="">It is an asynchronous event.</td><td id="MOeo" class="">It is synchronous event.</td></tr><tr id="85064752-fb32-49e7-a65e-7ab7bf52e681"><td id="TANh" class="">Hardware interrupts can be classified into two types they are: 1. Maskable Interrupt. 2. Non Maskable Interrupt.</td><td id="MOeo" class="">Software interrupts can be classified into two types they are: 1. Normal Interrupts. 2. Exception</td></tr><tr id="5c18eeb2-3d0c-47db-a7e3-e92d80f6ba73"><td id="TANh" class="">Keystroke depressions and mouse movements are examples of hardware interrupt.</td><td id="MOeo" class="">All system calls are examples of software interrupts</td></tr></tbody></table><p id="0091775c-d804-486c-80ef-4e9169dc62a6" class="">……………………………………………………………</p><h3 id="8c555879-a02a-428f-9ee1-4aa2db7aed3c" class=""><strong>What is a Thread?</strong></h3><p id="fef69b90-44bc-4ad3-96a9-5beade168718" class="">A thread is a path of execution within a process. A process can contain multiple threads.</p><p id="27b765cf-b184-4b60-abc6-869619f47478" class="">……………………………………………………………</p><h3 id="0c1c08a0-abad-463f-8568-04155024c47d" class="">What is cache memory?</h3><p id="ca867956-1a40-4a0d-adda-6db443438a96" class="">The data or contents of the main memory that are used again and again by CPU, are stored in the cache memory so that we can easily access that data in shorter time.</p><p id="86fab0a2-e4ea-453a-8f38-fe57d2f9b423" class="">Whenever the CPU needs to access memory, it first checks the cache memory. If the data is not found in cache memory then the CPU moves onto the main memory. It also transfers block of recent data into the cache and keeps on deleting the old data in cache to accommodate the new one.</p><p id="42cb0ced-acbf-4de9-88a6-54f02f09dc89" class="">……………………………………………………………</p><h3 id="92c34f5d-c97b-4f43-bab0-85e91dbcb7eb" class="">Differentiate between LI and L2 cache</h3><table id="dc41729e-5368-46b3-88c6-517378891c49" class="simple-table"><tbody><tr id="4678ce69-dfcb-4cf8-b8f4-0658931d67e4"><td id="tRsI" class="">L1</td><td id="rV&lt;I" class="">L2</td></tr><tr id="3acfe48e-000a-47f6-8f6b-bd623cd78eea"><td id="tRsI" class="">A cache memory that is directly built into the processor and is used to store the CPU’s recently accessed information.</td><td id="rV&lt;I" class="">A cache memory that is located outside and separated from the CPU chip core, although it is found on the same CPU chip package</td></tr><tr id="83ee6c00-3121-4739-b45b-be8e5539428c"><td id="tRsI" class="">Smallest cache</td><td id="rV&lt;I" class="">Larger than L1 but smaller than L3 cache</td></tr><tr id="b5a74057-0972-4257-948f-60fa80395a3c"><td id="tRsI" class="">Called level 1 or primary or internal cache</td><td id="rV&lt;I" class="">Called level 2, secondary or external cache Fastest cache</td></tr><tr id="f473aa51-bd4f-4c1c-9e36-2f447fe2bae5"><td id="tRsI" class=""></td><td id="rV&lt;I" class="">Slower than L1 but faster than L3</td></tr><tr id="2f80691c-6eb7-4d5c-912b-0915974772cb"><td id="tRsI" class="">Each core in the CPU has their own L1 cache memory</td><td id="rV&lt;I" class="">Each code in the CPU has their own L2 has their own memory</td></tr></tbody></table><p id="c353292c-f06e-4e00-9b7e-a868a2f4a364" class="">……………………………………………………………</p><h3 id="5a5ab8dd-33f5-4114-988c-caebb675f384" class="">DUAL CORE:</h3><p id="9e3287c8-7d1b-4271-9ada-7dd68b52b384" class="">Dual core is a CPU that has two distinct processors that work simultaneously in the same integrated circuit. This type of processor can function as efficiently as a single processor but can perform operations up to twice as quickly. Because each core has its own cache, the operating system is able to handle most tasks in parallel.</p><p id="43d44e83-1a5e-4c90-b830-3befebf7510b" class="">……………………………………………………………</p><h3 id="006e01f1-a395-4df3-90fb-e69735d45abd" class="">CORE 2 DUO</h3><p id="14f8ad2f-1e36-45de-890b-70310be4fd2d" class="">Core 2 Duo comes under series of dual-core processors which are invented by Intel. Intel named its series as Pentium Dual Core during starting of dual core processors, which referred to companies dual cores. Number of up-gradation and improvement in Intel first series processors resulted in them calling their processors as Core 2 Duo, with duo hinting two processors that are found on processor. These are known as 1st generation of dual processors. For example AMD refers to its dual core processors as X2.</p><p id="cdd52127-6acf-49ec-85e8-f06eb83e64a9" class="">……………………………………………………………</p><h3 id="f3ddb42a-82d5-4f82-94be-185ce1953e01" class="">What is meant by the term CORE?</h3><p id="001ca4dc-a03d-4df0-90c4-e012fbcb0b25" class="">A core, or CPU core, is <strong>the &quot;brain&quot; of a CPU</strong>. It receives instructions, and performs calculations, or operations, to satisfy those instructions. A CPU can have multiple cores. A processor with two cores is called a dual-core processor; with four cores, a quad-core; six cores, hexa-core; eight cores, octa-core.</p><p id="15c2e916-ec45-4162-a9bf-ce4574e21a89" class="">……………………………………………………………</p><h3 id="4fd4921c-3012-46d2-9afe-983789b89b4a" class="">What is embedded microprocessor systems?</h3><p id="16d77057-0d69-4474-8fa7-f8d8f1f5ce17" class="">An embedded system is <strong>a microprocessor-based computer hardware system with software that is designed to perform a dedicated function, either as an independent system or as a part of a large system</strong>. At the core is an integrated circuit designed to carry out computation for real-time operations.</p><p id="dc3a87b0-9eff-4872-a956-570317dc23ff" class="">……………………………………………………………</p><h3 id="6693a15c-68e5-418a-a015-b74634263674" class=""><strong>Difference between maskable and non maskable interrupt :</strong></h3><table id="25a5c44a-cad8-4b3b-86d9-cf496ebfcb15" class="simple-table"><tbody><tr id="8dd121dc-fdf1-4944-9641-387856cab4cd"><td id="OJOR" class=""><strong>Maskable Interrupt</strong></td><td id="rXif" class=""><strong>Non Maskable Interrupt</strong></td></tr><tr id="31b26825-ca62-49bc-9c38-3d11c394a2f2"><td id="OJOR" class="">Maskable interrupt is a hardware Interrupt that can be disabled or ignored by the instructions of CPU.</td><td id="rXif" class="">A non-maskable interrupt is a hardware interrupt that cannot be disabled or ignored by the instructions of CPU.</td></tr><tr id="41ebddd5-87da-4179-9d21-11632a81e3fa"><td id="OJOR" class="">When maskable interrupt occur, it can be handled after executing the current instruction.</td><td id="rXif" class="">When non-maskable interrupts occur, the current instructions and status are stored in stack for the CPU to handle the interrupt.</td></tr><tr id="a37ec646-11d5-4239-bf51-25b2d7ecb9cf"><td id="OJOR" class="">Maskable interrupts help to handle lower priority tasks.</td><td id="rXif" class="">Non-maskable interrupt help to handle higher priority tasks such as watchdog timer.</td></tr><tr id="81bcec77-18ef-42ed-b66e-5cd1ebf67a38"><td id="OJOR" class="">Maskable interrupts used to interface with peripheral device.</td><td id="rXif" class="">Non maskable interrupt used for emergency purpose e.g. power failure, smoke detector etc.</td></tr><tr id="5bd19452-ee17-4ab2-94a8-c27189fa0abd"><td id="OJOR" class="">In maskable interrupts, response time is high.</td><td id="rXif" class="">In non maskable interrupts, response time is low.</td></tr><tr id="670f29f9-4f92-4e35-aee9-184259ff7495"><td id="OJOR" class="">It may be vectored or non-vectored.</td><td id="rXif" class="">All are vectored interrupts.</td></tr><tr id="e4e5f017-ea22-4fce-81b1-b3af1e4c901c"><td id="OJOR" class="">Operation can be masked or made pending.</td><td id="rXif" class="">Operation Cannot be masked or made pending.</td></tr><tr id="aa17de98-9e79-4caa-a5ac-0cc5b825065f"><td id="OJOR" class="">RST6.5, RST7.5, and RST5.5 of 8085 are some common examples of maskable Interrupts.</td><td id="rXif" class="">Trap of 8085 microprocessor is an example for non-maskable interrupt.</td></tr></tbody></table><p id="e3cb2096-17ae-46f9-8de1-526a126ac606" class="">……………………………………………………………</p><h3 id="cb71d4a9-636c-4d6e-b052-bd190d1e9a0e" class=""><strong>Difference between Memory-Mapped I/O Interfacing and I/O Mapped I/O Interfacing :</strong></h3><table id="40843abc-a551-4894-bef4-a7e92cbd0f54" class="simple-table"><tbody><tr id="b6f962ef-aae2-4a02-81e3-2d2b5ae9e905"><td id="SNre" class="">Memory Mapped IO</td><td id="@bSt" class="">IO Mapped IO</td></tr><tr id="a78d7d50-ddd0-4c8c-91f6-4655067067ad"><td id="SNre" class="">IO devices are accessed like any other memory location.</td><td id="@bSt" class="">They cannot be accessed like any other memory location.</td></tr><tr id="9b9b62ad-da61-4103-9d9a-0bc245e62031"><td id="SNre" class="">They are assigned with 16-bit address values.</td><td id="@bSt" class="">They are assigned with 8-bit address values.</td></tr><tr id="13e25387-2d46-4db0-99a1-47e3c29d0b50"><td id="SNre" class="">The instruction used are LDA and STA, etc.</td><td id="@bSt" class="">The instruction used are IN and OUT.</td></tr><tr id="35df79d8-c537-4b58-928c-8981349ea092"><td id="SNre" class="">Cycles involved during operation are Memory Read, Memory Write.</td><td id="@bSt" class="">Cycles involved during operation are IO read and IO writes in the case of IO Mapped IO.</td></tr><tr id="002c27f5-859e-44bd-8fe7-204e070ba0e9"><td id="SNre" class="">Any register can communicate with the IO device in case of Memory Mapped IO.</td><td id="@bSt" class="">Only Accumulator can communicate with IO devices in case of IO Mapped IO.</td></tr><tr id="2cd66606-ebff-454a-a11b-b9b20a34ea16"><td id="SNre" class="">216 IO ports are possible to be used for interfacing in case of Memory Mapped IO.</td><td id="@bSt" class="">Only 256 I/O ports are available for interfacing in case of IO Mapped IO.</td></tr><tr id="7ec440b3-f9cb-44ee-862d-0c878acbe20e"><td id="SNre" class="">During writing or read cycles (IO/M` = 0 ) in case of Memory Mapped IO.</td><td id="@bSt" class="">During writing or read cycles (IO/M` = 1) in case of IO Mapped IO.</td></tr><tr id="5e5ebc57-1452-4c42-8d47-6035cac44ac7"><td id="SNre" class="">No separate control signal required since we have unified memory space in the case of Memory Mapped IO.</td><td id="@bSt" class="">Special control signals are used in the case of IO Mapped IO.</td></tr><tr id="843bbea2-dcd8-4af6-9db1-84b0a4e1c037"><td id="SNre" class="">Arithmetic and logical operations are performed directly on the data in the case of Memory Mapped IO.</td><td id="@bSt" class="">Arithmetic and logical operations cannot be performed directly on the data in the case of IO Mapped IO.</td></tr></tbody></table><p id="4909dacb-f04d-432d-b930-6521e2f95dff" class="">……………………………………………………………</p><h3 id="72f35e06-0931-4586-a133-c4775be514ed" class="">What are the function of IN and OUT instruction in perspective of 8086 microprocessor?</h3><p id="5cf894a4-5b34-41a0-b4b7-0c81d1add5fb" class="">IN − Used to read a byte or word from the provided port to the accumulator.</p><p id="e7069797-e922-49a9-9353-edfa6d1bbc32" class="">OUT − Used to send out a byte or word from the accumulator to the provided port.</p><p id="17b91b78-5edd-442d-9b87-f8a74ac71f27" class="">……………………………………………………………</p><h3 id="2fb8c09f-8cc8-419b-a4dc-f60093b61582" class="">What are the basic differences between microcontroller and microprocessor?</h3><figure id="07c93d6f-c350-43f6-9fa7-c5fcb3648eb8" class="image"><a href="CSE-3523_(Microprocessor)%2002d0b835246c44b6b6bab00747e4df42/Untitled%201.png"><img style="width:811px" src="CSE-3523_(Microprocessor)%2002d0b835246c44b6b6bab00747e4df42/Untitled%201.png"/></a></figure><p id="8bf97f08-3ad8-4973-8be9-f4755068bb9c" class="">……………………………………………………………</p><p id="bb63eb35-2445-4b49-a107-6066812e01ac" class="">Briefly describe the 8051  architecture with the help of figure.</p><p id="5350ec32-3698-4869-b2cb-fc5c40daf19e" class="">……………………………………………………………</p><h3 id="d6064bcc-899f-4d71-bd15-c058f3d6646f" class="">What is a system?</h3><p id="ad9d2e0a-25dd-4623-8730-3c0c461f1540" class="">Ans: A system is a arrangement where all its component walk according to the specific defined rules. It is method of organizing, working or performing one or more tasks.</p><p id="f1a9cde8-5ce3-4661-9a80-056565a7cf91" class="">……………………………………………………………</p><h3 id="1546bcd1-1cb0-4572-bd60-fdd730b78d8d" class="">What is a embedded system?</h3><p id="db107261-3bb9-4cc2-a18a-0f3ab0661bcc" class="">Embedded system is a combination of computer software and hardware which is either fixed in capability or programmable. An embedded system can be either an independent system or it can be a part of a large system. An embedded system is <strong>a microcontroller or microprocessor based system which is designed to perform a specific task</strong>. For example, a fire alarm is an embedded system; it will sense only smoke. It has hardware. It has application software.</p><h3 id="51a8d3db-8430-46b5-a097-892a4735b71f" class="">Following are important characteristics of an embedded system:</h3><ul id="b44148bc-9182-4fe9-a12b-067d48d51d8c" class="bulleted-list"><li style="list-style-type:disc">Requires real time performance</li></ul><ul id="ce060c12-bbb1-4dee-9091-d948415dd3dc" class="bulleted-list"><li style="list-style-type:disc">It should have high availability and reliability.</li></ul><ul id="bf4fa73e-06fc-4ade-9751-a67c41f139b0" class="bulleted-list"><li style="list-style-type:disc">Developed around a real-time operating system</li></ul><ul id="a20ed8ab-b30b-4226-9db0-af528972f9d4" class="bulleted-list"><li style="list-style-type:disc">Usually, have easy and a diskless operation, ROM boot</li></ul><ul id="3b25804e-5b14-4047-9d00-13051aafe4c6" class="bulleted-list"><li style="list-style-type:disc">Designed for one specific task</li></ul><ul id="d843d48f-59fa-4346-ac1f-e5bf636f5e21" class="bulleted-list"><li style="list-style-type:disc">It must be connected with peripherals to connect input and output devices.</li></ul><ul id="f477cbd6-c375-42ab-848d-b97f5226a014" class="bulleted-list"><li style="list-style-type:disc">Offers high reliability and stability</li></ul><ul id="d9f97fcb-94ea-446e-a787-fa1bec262b33" class="bulleted-list"><li style="list-style-type:disc">Needed minimal user interface</li></ul><ul id="e2b992a9-4e51-4d29-8dd2-1fc4da1e134c" class="bulleted-list"><li style="list-style-type:disc">Limited memory, low cost, fewer power consumptions</li></ul><ul id="2ea44c0e-75ab-476a-a844-823968f8a41f" class="bulleted-list"><li style="list-style-type:disc">It does not need any secondary memory in computer.</li></ul><p id="1597160f-8961-4944-b836-dff297f02625" class="">……………………………………………………………</p><h2 id="62da7bbf-7776-4a5d-8a97-6ee594da9f33" class=""><strong>What is Hardware Software Co-design?</strong></h2><p id="d377bd0c-ab7f-452d-bd31-732e600368f9" class="">Hardware-software co-design was a concept that began in the 1990s. Its core concept was the concurrent designs of hardware and software components of complex electronic systems. It aimed to incorporate the two technologies and exploit the synergy between the two. In essence, it was a way to merge hardware and software in an attempt to optimize and satisfy design constraints such as cost, performance, and power of the final product.</p><p id="c8d0dc1c-beb9-4c36-94ed-1e0bb72c0c2c" class="">At its inception, the best of both worlds&#x27; approach ultimately failed. Mainly because the idea and concept were sound, but the timing was not. At least in terms of the technology that it would require for the full benefit of this innovative concept to reach its maximum potential.</p><p id="1e67bb7c-22fb-4015-a7b7-4edb9e8c2013" class="">In any industry, forward-thinking is the only way to ensure advancement and longevity. Forward-thinking is precisely what hardware-software co-design represents. The proof of this is the fact that after nearly two decades, this concept is finally receiving the attention it deserves.</p><p id="a806c2f8-a1e7-4141-abab-ea6972141719" class="">……………………………………………………………</p><h1 id="3b670564-8ec2-4f54-991a-c8d1b48717df" class=""><strong>What is an 8051 Microcontroller?</strong></h1><p id="12f29fce-2c0c-46b4-8191-0e5003c00aaa" class="">The microcontroller like 8051 was designed in the year 1981 by Intel. The microcontroller is one kind of integrated circuit that includes 40-pins with dual inline package or DIP, RAM-128 bytes, ROM-4kb &amp; 16-bit timers–2. Based on the requirement, it includes addressable &amp; programmable 4 – parallel 8-bit ports. In the 8051 microcontroller architecture, the system bus plays a key role to connect all the devices to the central processing unit. This bus includes a data bus- an 8-bit, an address bus-16-bit &amp; bus control signals. Other devices can also be interfaced throughout the system bus like ports, memory, interrupt control, serial interface, the CPU, timers.</p><p id="fd31f708-43c3-4839-bad1-43090cd7d30c" class="">There are two buses in 8051 Microcontroller one for the program and another for data. As a result, it has two storage rooms for both programs and data of 64K by 8 sizes. The microcontroller comprises of 8-bit accumulator &amp; an 8-bit processing unit. It also consists of 8 bit B register as majorly functioning blocks and 8051 microcontroller programming is done with embedded C language using Keil software. It also has several other 8 bit and 16-bit registers.</p><p id="134f3165-fc7f-40db-a7ff-d6fbc5efddc2" class="">For internal functioning &amp; processing Microcontroller, 8051 comes with integrated built-in RAM. This is prime memory and is employed for storing temporary data. It is an unpredictable memory i.e. its data can get be lost when the power supply to the Microcontroller switched OFF.  This microcontroller is very simple to use, affordable less computing power, simple architecture &amp; instruction set.</p><p id="c265cf53-db99-4da4-ad19-d541479d2e48" class="">……………………………………………………………</p><p id="72eb7a33-9089-4d6e-8d2c-a76999631793" class="">Application of 8051 microcontroller:</p><ul id="02e3db2e-8bc1-4a92-839e-3d71c556c432" class="bulleted-list"><li style="list-style-type:disc">Consumer Appliances(TV tuners, remote control, computer)</li></ul><ul id="e5f5ac27-15e8-4504-b5d3-ab4e78c57cf5" class="bulleted-list"><li style="list-style-type:disc">Home Appliances(TVs, VCR, Video gamers)</li></ul><ul id="bc4a8d69-a93d-4bb9-bc69-d524bebe0f45" class="bulleted-list"><li style="list-style-type:disc">Communication System</li></ul><ul id="e2ab83b1-ebae-48df-9500-53d16eaacd87" class="bulleted-list"><li style="list-style-type:disc">Automobiles(Air bags, ABS)</li></ul><ul id="c30d8d5c-27dd-4072-9197-5f5a25e18651" class="bulleted-list"><li style="list-style-type:disc">Medical system</li></ul><ul id="ee4050b8-ee05-4465-9989-d7d0f3c8dcc7" class="bulleted-list"><li style="list-style-type:disc">Defense system</li></ul><ul id="2d899063-2829-4b7f-af02-8bb87c872e33" class="bulleted-list"><li style="list-style-type:disc">Robotics</li></ul><ul id="ade1fb62-c32b-498d-8cbd-7e42e3baee14" class="bulleted-list"><li style="list-style-type:disc">Remote sensing</li></ul><p id="957f8b2f-68ab-42e7-9b05-1edf1c222aeb" class="">……………………………………………………………</p><p id="6fbf3236-11d2-4128-b01c-1bb53723f099" class="">embedded system , embedded system model , embedded system example , embedded system characteristics , hardware software co - design ,  hardware software partioning , finite state machine model , SOC , SOC - example , characteristics , example</p><p id="303db351-7574-4aa4-b517-b578af22d113" class="">segment - 8
microcontroller , diff btwn MP &amp; microcontroller  (important), 8051 architecture draw , application &amp; example</p><p id="edd5aa1d-c741-4f9c-98ad-218deb5e1130" class="">seg - 7
interrupt , A time line that indicates interrupt usage in a typical system , (a) The interrupt vector table for the microprocessor and (b) the contents of an interrupt vector , (Divide error , NMI pin , overflow ) , Bound , IRET , INT5 , Real mode interrupt , Diff between real mode &amp; protect mode , draw interrupt pins in all versions , MI pin , NMI pin , FFH , 1AH to INTA , Seven INTR , 8259A draw &amp; description.</p><p id="0e16f167-de3f-4a57-a650-ef28baddac7c" class="">Microprocessor</p><p id="bbd2adb1-6fe4-45ef-81a4-4d17ec698fb1" class="">Microprocessor</p></div></article></body></html>
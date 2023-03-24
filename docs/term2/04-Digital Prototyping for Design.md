<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Digital Prototyping</title><style>
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

</style></head><body><article id="6fce6123-dd67-4cbc-a860-08ca395eda1a" class="page mono"><header><img class="page-cover-image" src="https://images.unsplash.com/photo-1562408590-e32931084e23?ixlib=rb-4.0.3&amp;q=80&amp;fm=jpg&amp;crop=entropy&amp;cs=tinysrgb" style="object-position:center 50%"/><h1 class="page-title">Digital Prototyping</h1></header><div class="page-body"><p id="1d2fdcfe-b391-47ac-8a8d-a7912d7b6764" class=""><strong><mark class="highlight-red">Feb 01, 2023</mark></strong></p><p id="c313554f-39bf-4115-bcb2-d071b9e71283" class="">
</p><p id="525d0c10-8861-471f-86d1-7fa4e94f0c6e" class="">How to integrate electronics into an idea? Interaction between humans &amp; machines.</p><p id="d24f803b-112a-4269-87cf-418cd62541cf" class="">Prototype - for proof of concept - Arduino board (Feather esp32)</p><p id="5dfcb452-3b11-4a63-891a-340a9738aaf9" class=""><mark class="highlight-gray_background">Schematic designs</mark></p><p id="920cbf2c-449f-4ad0-b68d-c30e0c227906" class="">
</p><p id="c050792f-8cb4-4cba-bde1-dc6aae3c721c" class=""><strong>How to select a board?</strong> Depending on what you want to do, the aspects like power, design etc.</p><p id="1b6b5ee4-fb90-4017-ab2f-cabc9a7eb6e2" class="">
</p><p id="74e7bc2d-ff24-4474-86e9-b9e030c74009" class="">- data sheet, pinout, power, how to program, how to setup in Arduino environment and how to install libraries for it.</p><p id="cd967041-7c5e-43f2-9749-452949399203" class="">
</p><p id="b005dcae-bf10-4cf6-aac4-457dd85272b1" class=""><strong>Data size</strong> of different computers - K, KB, MB, GB, TB</p><p id="798b14f9-8c37-4275-8941-c08f89ac3c7e" class=""><strong>Microcontroller</strong> - very small computer, built on a metal oxide board semiconductor circuit chip.</p><p id="eda362b2-5985-47c8-b121-e5adaab64fc5" class="">
</p><p id="4f16fe90-b34d-419d-9d03-695492e34fed" class=""><strong>Featherboards</strong> - produced by Adafruit - is not an Arudiono board in terms of the schematic design of the board.</p><p id="9c589546-4359-4a68-9480-6e99af0d3276" class="">Arduino releases a lot of core which consists of code that makes it easy peasy for us to use it and control things with it.</p><figure id="23524b74-a0bc-4fdd-a585-572dfe639055"><div class="source"><a href="https://www.google.com/url?sa=t&amp;rct=j&amp;q=&amp;esrc=s&amp;source=web&amp;cd=&amp;cad=rja&amp;uact=8&amp;ved=2ahUKEwjYkcPciPT8AhViVeUKHWxUCnoQtwJ6BAhMEAI&amp;url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DV4WtPv0yWek&amp;usg=AOvVaw2jlEQQCJfUQF9PDQzRmKvk">https://www.google.com/url?sa=t&amp;rct=j&amp;q=&amp;esrc=s&amp;source=web&amp;cd=&amp;cad=rja&amp;uact=8&amp;ved=2ahUKEwjYkcPciPT8AhViVeUKHWxUCnoQtwJ6BAhMEAI&amp;url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DV4WtPv0yWek&amp;usg=AOvVaw2jlEQQCJfUQF9PDQzRmKvk</a></div></figure><p id="403d7586-cf11-4f06-9e59-db3cc292bb7c" class="">
</p><p id="ea981390-4e8c-472a-b75d-0277311f7261" class=""><strong>The Arduino project</strong> - freedom to use, understand, modify and share your tools. <em>Open-source information used and modified must be also shared as open-source.</em></p><p id="9b69c607-5f12-4d30-9daf-e48b0f607103" class="">Copy-left model of copyright license, eg. Blender, Arduino.</p><p id="92e15f0b-c4f5-40c7-8956-33167481b5c7" class="">
</p><p id="d96275bb-041a-4739-9995-109d054e1bf3" class=""><strong>Arduino components </strong>- the hardware, software and community</p><p id="defae343-ab1f-4f6e-80db-6115b20eccfa" class="">Open hardware - you can buy a cheap board and use the same design of Arduino but just not use the actual name.</p><p id="51c7140b-0270-40dc-b713-25d69ea7c074" class="">Software - offer us a simple interface to talk between the microcontroller and the board.</p><p id="d3341df7-8cdd-4c63-872d-6b4be4164a3a" class="">Community - big community with basic and expert level of knowledge people to share ideas and questions.</p><figure id="e78684d4-f1c4-4df7-82d6-5f33dab19fa0"><div class="source"><a href="https://www.youtube.com/watch?v=UoBUXOOdLXY">https://www.youtube.com/watch?v=UoBUXOOdLXY</a></div></figure><p id="23de07c8-2ed8-4763-9222-777ca50808c9" class="">
</p><p id="b53e5c04-fd39-446d-b4e1-8143b67500d1" class="">
</p><p id="ed6db217-ce13-49e9-9494-29929e39761c" class=""><strong>Things to keep in mind :</strong></p><p id="4b46350c-cb1a-4c9e-a37e-fbc4c72d58a2" class="">Power -</p><ul id="7b91d312-d3c5-481e-81d0-219592bbda69" class="bulleted-list"><li style="list-style-type:disc">what kind of power do you need?</li></ul><ul id="00f40142-8cbd-430c-a138-2423a84cf2d8" class="bulleted-list"><li style="list-style-type:disc">doe it need to be portable or is it stable?</li></ul><ul id="bf4c4106-7c4f-4486-bf69-b8e67c0f5540" class="bulleted-list"><li style="list-style-type:disc">How much power?</li></ul><ul id="fde3d69f-2cdf-4370-91e3-04781991b65f" class="bulleted-list"><li style="list-style-type:disc">Can it be powered differently to reduce consumption within the design or use different sources of energy?</li></ul><ul id="fb1a03b3-896f-4f16-a2a0-de718f486fa6" class="bulleted-list"><li style="list-style-type:disc">PoE - Can it use ethernet instead so it get Internet and power at the same time?</li></ul><p id="3a48ff16-e6c4-4c79-a18d-d617c7f0cad8" class="">
</p><p id="0b8fc9ac-a89f-4256-abc7-12885cb1124e" class="">Input -</p><p id="5d5396c9-5ccd-491a-b6bb-5395d97bb4d0" class="">pins, how many do you need, helps you decide which board to use.</p><p id="daf669e4-bf8b-4a22-8421-352ccb9e9815" class="">does the board have enough of the right kind of pins you need for your project?</p><p id="26396a26-c6da-41dc-8ee3-1bb6ab4bc902" class="">
</p><p id="f215bc11-1b83-4f83-a0ea-3c284dc003d1" class="">Network -</p><p id="12aa21f7-c18d-41c0-b5ef-a6fe43b95745" class="">keep it local unless it really needs to communicate with other devices.</p><p id="4d16a6fb-fbef-40b3-8cf0-570ee98a12ab" class="">How much range do you need? short/ long distance? Cabled or wireless connection?</p><p id="811dabda-047b-44a0-8bd4-fc8dceedca4d" class="">
</p><p id="0498c3ea-7042-4df4-b8c2-8b4511c56038" class="">Data/ Processing capabilities -</p><p id="fe18e996-25ce-4ee7-8818-26477ad859b3" class="">What processing speed do you need?</p><p id="09df6b01-36d3-4afd-bc41-db0aadb635f7" class="">How much RAM, memory do you need?</p><p id="559faae1-c96e-4b18-aafe-e9e62dc810af" class="">Flash size - how big can your code be which you flash into the board.</p><p id="7949d482-e069-48fa-b3ca-fb3acf1c773a" class="">What kind of data does it need to process? use SBC for audio/video at high speed/resolution.</p><p id="d1019ba1-376e-45c1-adfb-d83ab65eb8a6" class="">Data storage - do you need to store it on the board? need memory? use a board with SD card compatibility.</p><p id="97dcd380-e679-4bb8-9f7e-f822719f043e" class="">
</p><p id="e15505df-46c1-4420-b256-e18fae678c60" class="">Usability</p><p id="1170a258-7515-49b2-86c7-0499000faf05" class="">size - to fit into your project context</p><p id="260ac1ec-4699-4116-99ae-26397a2d4b97" class="">power - how much power is required to use it</p><p id="eae628d9-524e-4e01-9c13-34adb58310cf" class="">user interface - how easy or difficult is it to use it</p><p id="62190b07-9cdc-46d8-b494-f2f27e31aef7" class="">documentation - does it have all the right documentation of how to use it properly?</p><p id="c7acf40c-7531-4389-892b-5b2c8b3458f8" class="">tutorial availability - same as ^</p><p id="517abf69-57f1-4c94-a577-34b806caa6a9" class="">
</p><p id="521e5a5e-66bf-422f-b7ed-4a6ff2bed605" class="">programming interface-</p><p id="71f58af5-6690-44d0-8795-7788db2534f7" class="">you have to check if your board is supported by arduino.</p><p id="d8557b0a-54d0-4365-9787-414fb482f130" class="">
</p><p id="37f301ff-0482-43b9-bb74-d148f2cb75fb" class="">
</p><p id="fb6c8daa-e13a-492b-b69b-ae23b287709a" class="">Go for C language if you&#x27;ve never coded before.</p><p id="71533ac7-0ad0-4730-85eb-cc78927d1b46" class="">Python demands a lot more storage and doesn’t offer that much control.</p><p id="c1910e00-6f5c-47ad-bccf-1de836b5db2c" class="">
</p><p id="f1f4fa1f-89de-438f-9c6a-9383e538c872" class="">Debugging - of course check your code but quite often its your cables that are mismatched, loose or not enough voltage( if power is not okay, your device won’t work). </p><p id="1ef98349-0528-4fa9-8f73-e463ff6de3c4" class="">
</p><p id="6e8a3037-b9e6-4150-92af-dddee1436c8e" class="">Power or heat</p><p id="f83704db-b35e-4ab6-a484-57aa7a951eff" class="">power - your device should be powered properly, should have enough power or you’ll get a bad reading.</p><p id="812d82e3-62a7-4f7a-9f49-995b1b3bf20a" class="">heating - if your chip is overheating, it will do crazy things that you won’t be able to understand.</p><p id="3f490935-0af9-4f3e-b658-20a573c9dcdc" class="">
</p><p id="febbf281-dc62-41fd-97b6-b6bb553a03c5" class="">serial.print- as much information as you can send to yourself of your device, you should.</p><p id="e3116dee-8c54-435f-a712-e0f0de4fa049" class="">
</p><p id="a5b93410-07d2-4e79-8c05-1349ff6c2f12" class=""><mark class="highlight-blue_background">Functions learned on DAY 01</mark></p><p id="d491c89e-adbd-4466-8a55-84ca084a50f6" class=""><mark class="highlight-blue_background"><em>buzzer / piezo speakertone(), noTone() functions</em></mark></p><p id="2e7c7a9b-dfcf-4025-b5e1-9185a7c82eff" class="">Found it frustrating as I wanted to try out a particular tune but most of the examples online were for the Arduino Uno board, I guess it&#x27;s because this board is an older board. The feather esp32 microcontroller has more capabilities. So then I decided to try and find a very basic code which I then tried to understand. The circuit was fairly simple to set up and for the code I had to define which pin I would be using on the microcontroller to control the buzzer. After that you just have to </p><p id="77c45388-4d9c-4c29-bbbe-14599caef51d" class="">
</p><p id="2f3ba32d-6515-4ae4-910c-491211225411" class=""><mark class="highlight-red"><strong>Feb 02, 2023</strong></mark></p><p id="bf5e9158-1cb7-430a-b137-fc56ad83fce4" class="">CAM</p><ul id="9a0ccfd5-8309-4b67-9480-7e040ae303ed" class="bulleted-list"><li style="list-style-type:disc">When you transform a design to a language that the manufacturing machines can understand.</li></ul><ul id="7ecebe77-3895-40eb-8544-7e83249bc4a5" class="bulleted-list"><li style="list-style-type:disc">Rhino is Cad</li></ul><ul id="49b9bad4-d615-40f3-8d08-66733c22b723" class="bulleted-list"><li style="list-style-type:disc">Cura is a CAM</li></ul><ul id="63a7c37a-8973-4207-a41c-2002ec77add6" class="bulleted-list"><li style="list-style-type:disc">Fusion is an all in one tool, CAD, CAM, generative design and beam.</li></ul><p id="10e38b67-8c15-4352-b0b9-828c96ff0580" class="">
</p><p id="3b51a105-6702-42a8-80f9-b91ebcce2488" class="">CPU vs GPU</p><p id="51ccff64-8ed7-4a10-9d4c-1082036da52f" class="">CPU does big mathematical equations, complex ones, but one by one.</p><p id="72599546-8a90-4c7f-a8bf-3ec859ab7369" class="">GPU is dumb but it has the ability to calculate small operation, large number of them all at the same time.</p><p id="78fbf91d-2e99-4d77-9c34-86bf0e61247d" class="">
</p><p id="44ca00c8-2317-4ecb-8f57-cc2ec19cc942" class="">Vector (x2 x y2 = R)</p><p id="54ea8355-c7ef-4431-a2f5-4a51ab698f86" class="">no texture</p><p id="40789951-23e4-4e83-b38c-8f2ecf785d6b" class="">Pixel</p><p id="3b9c9b80-4aeb-4dfd-ba9c-6b23f8e06d15" class="">pixels are the smallest unit of bitmap images, which are also called raster images or bitmap.</p><p id="516648e3-d32e-4d5f-9510-0ffef562d814" class="">An image with more pixels multiplied by more pixels will be a much larger and sharper image as well. We have the flexibility of using a large pixel image on a larger surface as well as reducing the size, it will remain sharp. Wheres, a lower pixel images cannot be used on a larger surface area, its quality &amp; sharpness will deteriorate considerably.</p><p id="0975eb6e-3689-47d7-b681-1ee3148a8a6e" class="">
</p><p id="53106b27-a851-4094-84be-0c968433de63" class="">sRGB</p><p id="77f85b8d-87de-40c5-b586-d1102c86bb40" class="">Resolution</p><p id="49f14c01-ff10-47a4-8399-b142572a4b60" class="">More pixels needs more compressor speed so your device then won’t last for so long because you&#x27;ll have to keep giving your device energy.</p><p id="f572a3e0-d4ad-4905-98b4-b1b52d40f5fd" class="">
</p><p id="c14b37f1-2c52-4902-a3dd-88325742de15" class="">JPEG file loosing pixels - find readings about it, compresses and de-compresses every time you open the file.</p><p id="5e0f5e72-7aa7-46ad-bac2-35701c0f74bd" class="">PNG - best file sharing format, doesn’t need any compressor.</p><p id="2a082434-2761-41fb-9911-d1ab15cf5683" class="">TIFF - multi-layer file format, compressionless, transparent format.</p><p id="b81bf8e1-40ef-446c-9662-086ee51c59d5" class="">
</p><p id="a42f78d0-2fdb-4e47-b00d-d962cc11beed" class="">
</p><p id="96337a7e-01fe-460b-874a-ebb23207dd6c" class="">x | y | z POINTS - define position of 3d modelling.</p><p id="e264b6fd-3cbb-4e1a-b3a9-ad88181ed53c" class="">Mesh / Nurbs - U &amp; V surface space</p><p id="26bd8e7f-2529-4648-8ad8-8033b10ff52d" class="">
</p><p id="2a3b8fbf-5257-4716-bc43-897b891f8454" class="">Nurbs - Non-uniform rational B-splines</p><p id="b6108053-7684-4746-83aa-fa439b29109a" class="">you can connect several of these and create a surface.</p><p id="ad824141-8f38-4cb3-b6de-cb35824e3ce7" class="">Easy to modify, smooth surface.</p><p id="c899b454-b610-45dd-8373-54874eafe1fc" class="">You need a powerful CPU</p><p id="5142da58-4ca0-4da5-93f1-6debdfab9d71" class="">
</p><p id="709bfc7a-e40c-4636-bd83-8c1651f94429" class="">Mesh - collection of vertices, edges and faces.</p><p id="c73747c2-f9a9-4af9-92b0-2c9e39ddee1a" class="">You need a good GPU</p><p id="c9764a5d-f98b-43ab-ba69-756ccd2c2499" class="">Triangular, Quadrilateral, Hexagonal mesh types</p><p id="ef17ae27-299f-4a61-9c5a-bba418b70304" class="">3D scanner is always a mesh file format because it look for these mesh point.</p><p id="17cb169f-ab5c-424a-aa6d-0502cc3f3547" class="">
</p><p id="9391f474-c026-4d95-a463-f6298ebf7c05" class="">You can sketch a model in NURBS and when you need to manufacture it then you translate it to a MESH format.</p><p id="5ecbd836-5eca-4305-b258-9d293ce3b5a9" class="">
</p><p id="d1d7cd2f-fc54-4291-832b-059fbd653e27" class="">MAP A texture</p><p id="6125d7d8-30b9-4593-914a-62a6a6909ca2" class="">.obj file format for a texture.</p><p id="f934054d-2f40-4e94-b6df-00062ee7c201" class="">3D sculpting</p><p id="1a7499c4-025c-4626-a360-2ce57d6c54b9" class="">
</p><figure id="9ef9d222-fe1c-4629-a102-942ceecdd27d" class="image"><a href="Digital%20Prototyping%206fce6123dd674cbca86008ca395eda1a/Untitled.png"><img style="width:1800px" src="Digital%20Prototyping%206fce6123dd674cbca86008ca395eda1a/croissant.png"/></a></figure><p id="8762810d-e575-4bdc-bbbf-f3e9264c0d17" class="">
</p><p id="e0e0b442-a495-4987-8a11-caa79c2bb220" class="">
</p><p id="871e600f-0394-48ad-88db-0f4af44628db" class=""><strong>Parametric design
</strong> is a process based on algorithmic thinking that allows the expression of parameters and rules that together define, codify and clarify the relationship between design intent and design response.</p><p id="31efadbc-1ed2-4e08-953a-9aa2506dd14a" class="">Coding modelling ^</p><p id="ee20969a-1538-4010-9b0b-efe7c9c3362e" class="">
</p><p id="dffc76a5-1823-41b8-94f5-3d854f66753b" class="">Idea - Login - Design</p><p id="b944fe2f-2b65-45c8-ac77-870973dfa16f" class="">
</p><p id="40c2b1b1-1880-4c8f-9d56-8dcee523ad74" class="">x,y,z,r,h - Five variables you define and can change for parametric modelling.</p><p id="fcfc9780-86e1-43eb-8e06-cbe2e6cabc90" class="">
</p><p id="7caa33de-e15f-4a89-a047-dbfd34a4910b" class="">
</p><div id="3f83822b-f7e0-4fed-a759-193291c2a928" class="column-list"><div id="8b63263f-8e19-4ea5-bfd6-e2c8ba6982c0" style="width:50%" class="column"><figure id="e6757e16-3689-469f-829a-a7f4a826eb17" class="image" style="text-align:left"><a href="Digital%20Prototyping%206fce6123dd674cbca86008ca395eda1a/Untitled%201.png"><img style="width:300px" src="Digital%20Prototyping%206fce6123dd674cbca86008ca395eda1a/holocaust.png"/></a></figure></div><div id="ce5535c6-d33e-4d62-8bb4-faf43e32d04e" style="width:50%" class="column"><p id="5abbb3ee-3fe5-4213-9c93-a5dc8752a531" class="">Array - x spacing and y spacing</p><p id="808d28b3-1855-4820-a482-c81de675eca3" class="">array of 5 lines with specific dimension</p><p id="b469f3e7-bf04-4f03-a743-e7a869f4ab0f" class="">at each array you place a cube with x,y dimension.</p></div></div><p id="53dab517-609a-4334-bbb1-b1dc24f769dc" class="">
</p><p id="065f96f7-3376-444e-9f7a-8f0251531cbc" class="">
Topological Optimisation - mathematical method that optimises material layout within a given design space, for a given set of loads, boundary conditions and constraints with the goal of maximising the performance of the system. </p><p id="58f98ec3-a1de-4e72-a204-90b0ccb61be0" class="">
</p><p id="f3d8b309-0e7d-4fe6-9cfe-ff1073a16a6b" class="">FEM (<em>finite element modeling)</em></p><ul id="9c66ca77-01d6-4d60-9c8f-91673a1174d3" class="bulleted-list"><li style="list-style-type:disc">FEM is an approximation method that subdivides a complex problem space, or <em>domain</em>
, into numerous small, simpler pieces (the finite elements) whose behavior can be described with comparatively simple equations.</li></ul><ul id="27ee954c-ceca-47dc-b932-8671fb0d62de" class="bulleted-list"><li style="list-style-type:disc">FEM was originally developed for engineering analysis to model and analyze complex systems in mechanical, civil, and aeronautical engineering. It has as its foundation the basic concepts of mechanics, such as Newton’s laws of motion, conservation of mass and energy, equilibrium, and the laws of thermodynamics.</li></ul><figure id="5c329986-a808-4835-8bea-957c503b9f89"><a href="https://blog.spatial.com/finite-element-modeling" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">An Introduction to Finite Element Modeling</div><div class="bookmark-description">Suppose you&#x27;re an aerospace engineer with a great idea for a new type of jet engine design, but you don&#x27;t know the sizes, shapes, and materials to use for the parts that will give you maximum power output with minimum fuel consumption, and that won&#x27;t break under the various thermal and mechanical stresses likely to be seen over all possible operating conditions.</div></div><div class="bookmark-href"><img src="https://blog.spatial.com/hs-fs/hub/10956/file-2191099304-png/Images/garland_favicon.png" class="icon bookmark-icon"/>https://blog.spatial.com/finite-element-modeling</div></div><img src="https://blog.spatial.com/hubfs/AdobeStock_296970902.jpeg#keepProtocol" class="bookmark-image"/></a></figure><p id="51a523e3-b7ef-4ba4-a6ee-b3b39f79fde8" class="">
</p><p id="396fab8d-9b68-4903-8fc9-41a77e8ad6ff" class="">Material Reduction</p><p id="834d0db7-ba02-4587-8b18-480e49799a45" class="">Shortened Design Process</p><p id="2ad4d72b-363a-4007-bdf9-c90713dd62f1" class="">Maximum Performance</p><p id="29388c76-ff2c-4f77-a655-f7b76e60f2d2" class="">
</p><p id="b0ccb7ac-c24a-4fb2-b3a0-828d0643fa49" class="">swarm algorithm</p><p id="86719077-2698-4d32-91a8-9a55ad9c9bd5" class="">ant topological behaviour - Marco Dario</p><p id="fd2d2bcc-bc4d-408b-be26-d9a629603ab3" class="">forces always go to the shortest path.</p><p id="a775ac6b-bd6e-43e0-a484-b57bca25dacf" class="">eg. Tokyo subway system</p><p id="93e79f95-783c-4f7e-b99f-113650250dd5" class="">
</p><p id="19360f25-d99a-4ac8-9f91-fb74add35c4d" class="">
</p><p id="740535b4-59d1-40e3-ae93-80901a6311f3" class="">
</p><p id="7635eb1e-3839-49ea-bc0c-1c5401a1bf7e" class="">
</p><p id="3cfc00b1-21f0-459d-ae8a-56d0b97b1df3" class="">
</p><p id="01a55310-bdc4-4d19-aff5-cd780f17e0fa" class="">
</p><p id="dda0982b-9c8d-4463-ac70-b1e10999ae6d" class="">
</p><p id="f6627703-35a0-4e38-a55c-9a6a966a243d" class="">
</p><p id="626a64ee-f6fe-4f13-be70-61b28fcde0c2" class="">
</p><p id="33ffeb27-8dc6-408f-8133-7a7b48393a46" class="">
</p><p id="2f7abe70-e2a0-41e8-8bdf-b45f6eb76c57" class="">
</p><p id="af745117-a27a-4143-ba3d-a822722ec730" class="">
</p><p id="4ff5ef35-a528-4eb9-87d4-f54a48de5466" class="">
</p><p id="556f78fc-68c9-40ff-8831-a4f3bf7d14b4" class="">
</p><p id="126133cb-eddb-4322-940d-cf3b4c32e53a" class="">
</p><p id="822a950e-cb11-4d31-9c3f-9c8026ca743e" class="">
</p><p id="7cf5c299-f751-4d57-99bb-14e0da581885" class="">
</p></div></article></body></html>



<p id="a5b93410-07d2-4e79-8c05-1349ff6c2f12" class=""><mark class="highlight-blue_background">Learnings of DAY02</mark></p><p id="d491c89e-adbd-4466-8a55-84ca084a50f6" class=""><mark class="highlight-blue_background"><em>buzzer / piezo speakertone(), noTone() functions</em></mark></p><p id="2e7c7a9b-dfcf-4025-b5e1-9185a7c82eff" class="">We were introduced to a wide range of AI tools for 3d rendering and model making. I have used Adobe dimension and SketchUp in the past for making 3d Models. I have only ever made static 3d models so i'm excited to learn how to animate them using other tools. I have animations on Flash and Adobe Animate before. We were given a task to make music on the Esp32 board and I really wanted to get the super mario tune on it. I found a couple of examples for it on the net but the code was rather complicated for me to understand. I tried using them a couple times but failed. A classmate of mine even asked ChatGPT to give the code for music. I felt it would be more useful for me to try something simple but understand the code completely so here is my very sad attempt at making music. A lot of the examples online were for the Arduino Uno board, maybe because it is an older board.. I think I will get one of those to try out as well.</p><p id="77c45388-4d9c-4c29-bbbe-14599caef51d" class="">

<div style="position: relative; width: 100%; height: 0; padding-top: 100.0000%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFZyr5DDtM&#x2F;watch?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFZyr5DDtM&#x2F;watch?utm_content=DAFZyr5DDtM&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Arduino music</a>

<p id="9c3bdd15-5726-40b7-9f6c-8419b9e9d586" class="">G code - we write in G code for the machine | M code - for the actions</p><p id="79c80a04-0390-4623-a96c-fc65f42185b0" class="">Robotic arm - x,y,z,a,b,c (6-axis)</p><p id="bfc86d6f-c90b-4d9d-a758-490986e77831" class="">
</p><p id="5aa42276-37b8-456d-9efd-77e7983d4541" class="">LASER = Light Application by Stimulated Emission of Radiation - focused photons at a series of frequency through optics.</p><p id="ace2cd9c-7ed2-4aa0-92fd-37e5ce01a7d7" class="">
</p><p id="403b5ced-e933-455d-9708-172595025ac9" class="">Red - infrared - fast frequency</p><p id="737d081b-7f90-4519-a360-e9903e174454" class="">Radio waves - can kill us</p><p id="dbf8fe07-52ef-4f0a-9cee-5b7d35754c08" class="">Ultraviolet - if we lose the ozone layer then the sun will send more UV rays.</p><p id="87884bf2-b5aa-4bcd-9a06-6af22ffedf89" class="">X-rays - can penetrate through us</p><p id="6e4feb09-2360-4984-ae25-8cde9d351403" class="">Gamma rays - nuclear energy produces a lot of these.</p><p id="1adfb285-463a-4c84-9644-0e011b325f25" class="">
</p><p id="8c463df7-0436-4c47-a22f-b90af65a4bfa" class="">Laser cutting - low density materials - plastics, wood, cardboard, fabrics, etc.</p><p id="fb1991d0-40ab-4485-97d7-a66852607fe6" class="">
</p><p id="e00d2a13-0fae-4aa9-a0ab-2df31f699e74" class="">Parts of layer cutter</p><p id="4a129710-f97d-4129-a827-bc86bb787c5d" class="">Laser source | options | 3(+) axis CNC | controller</p><p id="c8ce647b-ba4e-4f03-babb-a0c3d4c0d074" class="">
</p><p id="029edd36-3f9a-4dab-b359-132b1f09b132" class="">Micro controller vs. micro processor (READ)</p><p id="c8ac2d47-369e-4a00-88dc-ba6ec7f862d6" class="">
</p><p id="2b4f18c8-48dd-437d-a6b3-a902df0f5267" class="">Micro-controller don’t stop working unless there’s an issue with your code. </p><figure id="257eaab9-4225-45c2-aafc-dbcb16c845d6" class="image"><a href="Digital%20Prototyping%206fce6123dd674cbca86008ca395eda1a/Untitled.jpeg"><img style="width:4032px" src="Digital%20Prototyping%206fce6123dd674cbca86008ca395eda1a/Untitled.jpeg"/></a></figure><p id="ed0dc766-c0af-4b6c-9127-855c19bd7460" class="">
</p><p id="a67f4eef-1a77-4859-8a6f-0d6487bc3172" class="">nesting tool - deep nest, rhino nest, svgnest</p><p id="8d65bf83-8fdb-4259-b15a-4ccd738eb750" class="">tolerance</p><p id="93e79f95-783c-4f7e-b99f-113650250dd5" class="">kerf - the width of the material you are losing while cutting</p><p id="9cb05740-01c1-4d4b-9238-ba8f0b737c7e" class="">
</p><p id="19360f25-d99a-4ac8-9f91-fb74add35c4d" class="">Slicer Fusion - stacking, waffle, paper folding</p><figure id="f7a4a4d2-17e5-419f-b8de-73bb98409236"><a href="https://www.google.com/url?sa=t&amp;rct=j&amp;q=&amp;esrc=s&amp;source=web&amp;cd=&amp;cad=rja&amp;uact=8&amp;ved=2ahUKEwjAx4Xc3IX9AhUGHOwKHd50D5cQFnoECBwQAQ&amp;url=https%3A%2F%2Fknowledge.autodesk.com%2Fsupport%2Ffusion-360%2Ftroubleshooting%2Fcaas%2Fdownloads%2Fcontent%2Fslicer-for-fusion-360.html&amp;usg=AOvVaw1KMAnoIXbIJM6h0VKvtOj2" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Slicer for Fusion 360</div><div class="bookmark-description">Slicer for Fusion 360 is no longer maintained on the Autodesk Fusion 360 App Store. The technology is deprecated and is no longer being maintained and supported by Autodesk. Provided below is the final release of Slicer for both Mac OS and Windows.</div></div><div class="bookmark-href"><img src="https://damassets.autodesk.net/content/dam/autodesk/logos/autodesk-symbol-32x32.svg" class="icon bookmark-icon"/>https://www.google.com/url?sa=t&amp;rct=j&amp;q=&amp;esrc=s&amp;source=web&amp;cd=&amp;cad=rja&amp;uact=8&amp;ved=2ahUKEwjAx4Xc3IX9AhUGHOwKHd50D5cQFnoECBwQAQ&amp;url=https%3A%2F%2Fknowledge.autodesk.com%2Fsupport%2Ffusion-360%2Ftroubleshooting%2Fcaas%2Fdownloads%2Fcontent%2Fslicer-for-fusion-360.html&amp;usg=AOvVaw1KMAnoIXbIJM6h0VKvtOj2</div></div><img src="https://knowledge.autodesk.com/sites/all/themes/autodesk_foundation5/images/standard/autodeskLogo-125x125.png" class="bookmark-image"/></a></figure><p id="740535b4-59d1-40e3-ae93-80901a6311f3" class="">
</p><p id="82a1b485-b936-4640-9ceb-c79bec1369cf" class=""><strong>vinyl cutter</strong></p><p id="ff35e9ef-adec-484f-b57b-785d924aa364" class="">
</p><p id="d128881b-129f-4771-a1e5-ca6be3dce70c" class="">inside to outside cutting</p><p id="d23fa97b-51fb-4590-a78d-3cf7f528b283" class="">force the machine to do it by drawing in those colours to order the cutting process.</p><p id="6d15895b-c131-43cc-ae9e-a4bb4c89a419" class="">
</p><p id="7f86bcdf-94f6-4436-ad97-c090ab4d877c" class="">vector vs. rastor</p><p id="427cf03b-c62a-49da-9e09-e6c5216aa0cb" class="">rastor will remove that whole part (hatch pattern)</p><p id="e9b30a6e-5864-4f4a-be89-e191b3dce41e" class="">vector will just be a line cut</p><p id="c101db38-af81-41dd-8f03-8fb32041a46a" class="">
</p><p id="4245bceb-535b-4ce0-b2d5-ce8cff82f1c4" class="">all machine work in mm dimensions.</p><p id="1f94fd45-b024-43cc-9530-93d2345cfb7e" class="">
</p><p id="24fe17fb-94e1-4396-9031-e8ff61ec2472" class="">vinyl cutter - you can cut really long designs</p><p id="57f3def5-c37c-409e-8bf7-50e7e5bd271d" class="">control over - speed, temperature, power, force and how long the blade is.</p><p id="6bc33747-612f-4048-8eb5-29490c3ea74b" class="">thicker material will need a longer blade</p>

<p id="a5b93410-07d2-4e79-8c05-1349ff6c2f12" class=""><mark class="highlight-blue_background">Learnings of DAY03</mark></p><p id="d491c89e-adbd-4466-8a55-84ca084a50f6" class=""><mark class="highlight-blue_background"><em>Laser cutting & Acrylic</em></mark></p><p id="2e7c7a9b-dfcf-4025-b5e1-9185a7c82eff" class="">I had my first interaction with using the laser cutter this week. I thought about what would be more useful in terms of application for my personal project. As I am interested in working with biomaterials and seeing how i can conduct workshops to teach people how to extend the journey of a material. I thought about what I could make that could be used in a workshop. I feel quite often to feel inspired to make something, you should be able to see and appreciate what you have. This led me to the idea of having a compartmentalised box to store different materials - both waste and ingredients for making biomaterials. An almacen of sorts for making biomaterials. Since these would be 'Materials' of the future, I wanted to write the word 'futura' on it. While lacer cutting, the laser behaved funnily and the text did not get engraved properly. I found this website - <a href="https://en.makercase.com/#/">Makercase</a></p><p id="77c45388-4d9c-4c29-bbbe-14599caef51d" class="">for making different types of boxes. I thought this would make this a little easier as it had the inbuilt kerf option for laser cutting. After a couple of tests on the laser cutter, I had to finally change a lot of the box design on Rhino. At the end, while putting the box together, I still faced issues with the middle panels as there wasn't enough breathing space, I think the slots had to be even more wide. The inspiration for this acrylic box with compartments was so that you can see the various textures, colors and ingredients of the materials and get more inclined to collect waste for making biomaterials. I find that when you can see the quanity and quality of your materials, it makes the whole thing more efficient and lends that level of transparency with your projects as well..</p><p id="77c45388-4d9c-4c29-bbbe-14599caef51d" class="">

<div style="position: relative; width: 100%; height: 0; padding-top: 100.0000%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFbDk9arfU&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFbDk9arfU&#x2F;view?utm_content=DAFbDk9arfU&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Laser Cutting</a>

<p id="a5b93410-07d2-4e79-8c05-1349ff6c2f12" class=""><mark class="highlight-blue_background">Learnings of DAY04</mark></p><p id="d491c89e-adbd-4466-8a55-84ca084a50f6" class=""><mark class="highlight-blue_background"><em>LDR sensor & Morse Code</em></mark></p><p id="2e7c7a9b-dfcf-4025-b5e1-9185a7c82eff" class="">I found this task extremely difficult as it required me to first understand what and how an LDR works. An LDR is basically a sensor that receives light and can react to it. By connecting a button that signals to obtain the reading from the LDR, to trigger an LED light, I got confused a couple of times. So I decided to start with just connecting the LDR and seeing the reading of it in the serial moniter. Next I took a look at the serial plotter to see how sensitive it was to the light. I decided to cover the whole breadboard with a coffee box to see what difference it would make, I even put my phone torch above it to see how that would affect the LDR reading. I was happy with the progress I was making so I went on to attach an LED to the circuit to see how I could control the LDR reading with an LED and a button. I was able to build this circuit but as the task was to print a dot and a dash, I found it difficult. I wrote the code so that if the reading was above 1000 in the serial moniter, to print a dot or a dash. I decided to add a line which said if this was the reading for more than 50 milliseconds then print a dash "-" else print a dot "." but i was unable to use the else if statement as I didn't want to print anything if the button is not pressed, although the LDR still has a reading without the button being pressed.</p><p id="77c45388-4d9c-4c29-bbbe-14599caef51d" class="">

<div style="position: relative; width: 100%; height: 0; padding-top: 100.0000%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFbDr9ssfU&#x2F;watch?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFbDr9ssfU&#x2F;watch?utm_content=DAFbDr9ssfU&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">LDR sensor</a>

![](../images/andaaza_output.JPEG)
<p id="a5b93410-07d2-4e79-8c05-1349ff6c2f12" class=""><mark class="highlight-blue_background">Learning of Challenge 01</mark></p><p id="d491c89e-adbd-4466-8a55-84ca084a50f6" class=""><mark class="highlight-blue_background"><em>3D printer + turn table</em></mark></p><p id="2e7c7a9b-dfcf-4025-b5e1-9185a7c82eff" class="">I think it's safe to say my group took the longest to decide what direction to take for this challenge. I had never worked with either of them before and that's why getting our ideas to converge was rather difficult. We then decided to see what the common themes that were emerging were and thought how we could work with as many of those as possible. This led us to work on creating a way to engrave messages/feeling (through audio input) onto an object (we use in a our daily lives) so it can be used as a way to communicate with others. We looked around class and found an old 3D printer and began to open it up. We felt quite bad to 'destroy' it but thought of it in a way to make something even better! The process of making the turn table took the least amount of effort from everything and we were able to take it one step further to control the direction of it using a control switch. This was the most fascinating feature. We were able to laser cut a lot of the parts except a holder for the pen/carving tool. As a first prototype of this, I am very happy with the how much we were able to achieve. I found the two weeks rather hectic and challenging with not enough time to reflect. I am excited to work on this project further with my teammates and develop it more.</p><p id="77c45388-4d9c-4c29-bbbe-14599caef51d" class="">

<p id="a5b93410-07d2-4e79-8c05-1349ff6c2f12" class=""><mark class="highlight-blue_background">Challenge 01</mark></p><p id="d491c89e-adbd-4466-8a55-84ca084a50f6" class=""><mark class="highlight-blue_background"><em>Andaaza</em></mark></p>
 <a href="https://www.canva.com/design/DAFaumtP7p8/6alduDLkCOwk2gHwn5hSnA/view?utm_content=DAFaumtP7p8&utm_campaign=designshare&utm_medium=link&utm_source=viewer">Presentation</a></p><p id="77c45388-4d9c-4c29-bbbe-14599caef51d" class="">


 <h3>3D Printing</h3>

 ![](../images/whistle1.jpeg)
 ![](../images/whistle2.jpeg)

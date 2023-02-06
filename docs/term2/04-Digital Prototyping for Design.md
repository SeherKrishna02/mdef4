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
![](../images/croissant.png)
</p><p id="871e600f-0394-48ad-88db-0f4af44628db" class=""><strong>Parametric design</strong> is a process based on algorithmic thinking that allows the expression of parameters and rules that together define, codify and clarify the relationship between design intent and design response.</p><p id="31efadbc-1ed2-4e08-953a-9aa2506dd14a" class="">Coding modelling ^</p><p id="ee20969a-1538-4010-9b0b-efe7c9c3362e" class="">
</p><p id="dffc76a5-1823-41b8-94f5-3d854f66753b" class="">Idea - Login - Design</p><p id="b944fe2f-2b65-45c8-ac77-870973dfa16f" class="">
</p><p id="40c2b1b1-1880-4c8f-9d56-8dcee523ad74" class="">x,y,z,r,h - Five variables you define and can change for parametric modelling.</p><p id="fcfc9780-86e1-43eb-8e06-cbe2e6cabc90" class="">
![](../images/holocaust.jpg)
<p id="5abbb3ee-3fe5-4213-9c93-a5dc8752a531" class="">Array - x spacing and y spacing</p><p id="808d28b3-1855-4820-a482-c81de675eca3" class="">array of 5 lines with specific dimension</p><p id="b469f3e7-bf04-4f03-a743-e7a869f4ab0f" class="">at each array you place a cube with x,y dimension.</p></div></div><p id="53dab517-609a-4334-bbb1-b1dc24f769dc" class="">
</p><p id="065f96f7-3376-444e-9f7a-8f0251531cbc" class="">Topological Optimisation - mathematical method that optimises material layout within a given design space, for a given set of loads, boundary conditions and constraints with the goal of maximising the performance of the system. </p><p id="58f98ec3-a1de-4e72-a204-90b0ccb61be0" class="">
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

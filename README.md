<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AI_数独</font></font></h1><a id="user-content-ai_sudoku" class="anchor" aria-label="永久链接：AI_Sudoku" href="#ai_sudoku"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://www.python.org/" rel="nofollow"><img src="https://camo.githubusercontent.com/3c55df0eaf0804dba65a57bfd09fd26419a1bec537962d966ace4e4959b51f5a/687474703a2f2f466f7254686542616467652e636f6d2f696d616765732f6261646765732f6d6164652d776974682d707974686f6e2e737667" alt="forthebadge 用 python 制作" data-canonical-src="http://ForTheBadge.com/images/badges/made-with-python.svg" style="max-width: 100%;"></a>
<a href="http://ForTheBadge.com" rel="nofollow"><img src="https://camo.githubusercontent.com/fbf103996c80488f3b9847a0db948016e6aea4a7f263e2144e0fdeb8425c58f9/687474703a2f2f466f7254686542616467652e636f6d2f696d616765732f6261646765732f63632d302e737667" alt="forthebadge cc-0" data-canonical-src="http://ForTheBadge.com/images/badges/cc-0.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GUI 智能数独解算器尝试从照片中提取数独谜题并解决它。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录：</font></font></h2><a id="user-content-table-of-contents" class="anchor" aria-label="永久链接： 目录：" href="#table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://github.com/neeru1207/AI_Sudoku/blob/master/README.md#installation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></a></p>
<p dir="auto"><a href="https://github.com/neeru1207/AI_Sudoku/blob/master/README.md#usage"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法</font></font></a></p>
<p dir="auto"><a href="https://github.com/neeru1207/AI_Sudoku/blob/master/README.md#working"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在职的</font></font></a></p>
<ul dir="auto">
<li><a href="https://github.com/neeru1207/AI_Sudoku/blob/master/README.md#image-preprocessing"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图像预处理</font></font></a></li>
<li><a href="https://github.com/neeru1207/AI_Sudoku/blob/master/README.md#recognition"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">认出</font></font></a></li>
</ul>
<p dir="auto"><a href="https://github.com/neeru1207/AI_Sudoku/blob/master/README.md#todo"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">去做</font></font></a></p>
<p dir="auto"><a href="https://github.com/neeru1207/AI_Sudoku/blob/master/README.md#contributing"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2><a id="user-content-installation" class="anchor" aria-label="永久链接：安装" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><a href="https://www.python.org/downloads/" rel="nofollow"><font style="vertical-align: inherit;">从这里</font></a><font style="vertical-align: inherit;">下载并安装Python3</font></font><a href="https://www.python.org/downloads/" rel="nofollow"><font style="vertical-align: inherit;"></font></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我建议使用</font></font><a href="https://virtualenv.pypa.io/en/latest/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">virtualenv</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。通过打开终端并输入以下命令来下载 virtualenv：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install virtualenv</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install virtualenv" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建一个名为 sudokuenv 的虚拟环境。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视窗</font></font></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>virtualenv sudokuenv
<span class="pl-c1">cd</span> sudokuenv/Scripts
activate</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="virtualenv sudokuenv
cd sudokuenv/Scripts
activate" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux：</font></font></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">source</span> sudokuenv/bin/activate</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="source sudokuenv/bin/activate" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">克隆此存储库，如果您下载了 .zip 或 .tar 文件，请将其解压缩并 cd 到克隆的存储库中。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如：</font></font></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">cd</span> A:<span class="pl-cce">\A</span>I_Sudoku-master</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cd A:\AI_Sudoku-master" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过键入以下内容安装所需的软件包：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install -r requirements.txt</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install -r requirements.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法</font></font></h2><a id="user-content-usage" class="anchor" aria-label="永久链接：用法" href="#usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在运行应用程序之前，请注意您可以将</font><strong><font style="vertical-align: inherit;">Run.py中的</font></strong></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">modeltype</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">变量设置</font><font style="vertical-align: inherit;">为“CNN”或“KNN”，以选择卷积神经网络或 K 最近邻算法进行识别。默认情况下，它设置为“KNN”，并且我使用 KNN 本身获得了更高的精度，因此我建议您不要更改它。</font></font><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s">'''Run this file to run the application'''</span>
<span class="pl-k">from</span> <span class="pl-v">MainUI</span> <span class="pl-k">import</span> <span class="pl-v">MainUI</span>
<span class="pl-k">from</span> <span class="pl-v">CNN</span> <span class="pl-k">import</span> <span class="pl-v">CNN</span>
<span class="pl-k">from</span> <span class="pl-v">KNN</span> <span class="pl-k">import</span> <span class="pl-v">KNN</span>
<span class="pl-k">import</span> <span class="pl-s1">os</span>
<span class="pl-c"># Change the model type variable value to "CNN" to use the Convolutional Neural Network</span>
<span class="pl-c"># Change the model type variable value to "KNN" to use the K Nearest Neighbours Classifier</span>
<span class="pl-s1">modeltype</span> <span class="pl-c1">=</span> <span class="pl-s">"KNN"</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="'''Run this file to run the application'''
from MainUI import MainUI
from CNN import CNN
from KNN import KNN
import os
# Change the model type variable value to &quot;CNN&quot; to use the Convolutional Neural Network
# Change the model type variable value to &quot;KNN&quot; to use the K Nearest Neighbours Classifier
modeltype = &quot;KNN&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">键入以下命令来运行应用程序。您</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">连接到互联网，创建</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">knn.sav</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件可能需要 5-10 分钟，请耐心等待。此延迟仅在第一次运行期间发生，因为一旦创建，应用程序将使用本地文件</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python Run.py</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python Run.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行应用程序后会立即打开 GUI 主页。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/1.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/1.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您需要通过 GUI 主页选择数独谜题的图像。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/2.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/2.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一旦您按下</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Next</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，就会发生图像处理的多个阶段，这些阶段由 GUI 显示，直至识别。以下是其中两个阶段的快照：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/4.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/4.png" alt="" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/7.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/7.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于识别，</font><font style="vertical-align: inherit;">可以使用</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CNN</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KNN</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 。可以按照第一点中提到的方式切换此选项。识别后，将显示看板，您可以纠正看板上任何错误识别的条目。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/18.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/18.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最后点击</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">reveal Solution</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">即可显示解决方案。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/19.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/19.png" alt="" style="max-width: 100%;"></a></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在职的</font></font></h2><a id="user-content-working" class="anchor" aria-label="永久链接：工作" href="#working"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图像预处理</font></font></h3><a id="user-content-image-preprocessing" class="anchor" aria-label="永久链接：图像预处理" href="#image-preprocessing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高斯模糊</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用高斯函数进行模糊。这是为了减少噪音和细节。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/4.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/4.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自适应高斯阈值</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用高斯函数的自适应阈值处理可以考虑图像不同部分的不同照明。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/5.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/5.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">反转</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以使数字和线条变白，同时使背景变黑。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/6.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/6.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用加号 3X3 内核进行膨胀</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，以填充板线中的任何裂缝并加厚板线。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/7.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/7.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">洪水填充</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于棋盘可能是最大的斑点，也称为具有最大面积的连接组件，因此从不同的种子点进行洪水填充并找到所有连接的组件，然后找到最大的洪水填充面积区域将给出棋盘。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/8.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/8.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最大</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的斑点</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（又称木板）是在上一步之后找到的。我们称之为外箱</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/9.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/9.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">稍微腐蚀</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网格以消除我们之前对外盒进行的膨胀的影响。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/10.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/10.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">霍夫线变换</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以查找检测到的外箱中的所有线。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/11.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/11.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">合并</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相关行。霍夫变换找到的彼此接近的线融合在一起。</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">寻找极限线</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。我们通过选择距离顶部最近的斜率几乎为 0 的线作为上边缘，距离底部最近的斜率几乎为 0 的线作为下边缘，距离左侧最近的斜率几乎无穷大的线作为左边缘来找到边界线。边和距右侧最近且斜率几乎无穷大的线作为右边缘。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/12.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/12.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到四个交点</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。找到这些线的四个交点并沿着线绘制。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/13.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/13.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扭曲视角</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。我们使用端点找到透视矩阵，校正透视并将板从原始图像中裁剪出来。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/14.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/14.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阈值化和反转网格</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。上一步的裁剪图像经过自适应阈值处理和反转。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/15.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/15.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网格切成 81 个切片，以获得数独板每个单元格的图像。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/16.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/16.png" alt="" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">涂黑并使数字居中</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。除数字之外的任何白色斑块都通过从外层点作为种子用黑色进行泛洪填充来去除。然后找到数字的近似边界框并将其居中于图像中。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/neeru1207/AI_Sudoku/blob/master/Screenshots/17.png"><img src="https://github.com/neeru1207/AI_Sudoku/raw/master/Screenshots/17.png" alt="" style="max-width: 100%;"></a></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">认出</font></font></h3><a id="user-content-recognition" class="anchor" aria-label="永久链接： 认可" href="#recognition"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卷积神经网络</font></font></h4><a id="user-content-convolutional-neural-network" class="anchor" aria-label="永久链接：卷积神经网络" href="#convolutional-neural-network"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><a href="https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53" rel="nofollow"><font style="vertical-align: inherit;">在这里</font></a><font style="vertical-align: inherit;">阅读有关 CNN 的内容</font></font><a href="https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53" rel="nofollow"><font style="vertical-align: inherit;"></font></a></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">层</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个卷积层，一个被展平为隐藏层的最大池化层，后面是一些 Dropout 正则化层，另一个隐藏层，最后是输出层。每个内层使用</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReLu</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，而输出层使用</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">softmax</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编译</font></font></strong> <em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Adam</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">优化器和</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">稀疏分类交叉熵</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">损失。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">训练</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该模型在</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MNIST</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手写数字数据集上进行训练，该数据集包含大约 70,000 张 28X28 图像。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">准确度</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试集的准确度约为 98%。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">K 最近邻</font></font></h4><a id="user-content-k-nearest-neighbours" class="anchor" aria-label="永久链接：K 最近邻" href="#k-nearest-neighbours"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><a href="https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761" rel="nofollow"><font style="vertical-align: inherit;">在这里</font></a><font style="vertical-align: inherit;">阅读有关 KNN 的信息</font></font><a href="https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761" rel="nofollow"><font style="vertical-align: inherit;"></font></a></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用的K</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">值为3。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">训练</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MNIST</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手写数字数据集上进行训练，该数据集包含大约 70,000 张 28X28 图像。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">准确度</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试集的准确度约为 97%。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">去做</font></font></h2><a id="user-content-todo" class="anchor" aria-label="永久链接：待办事项" href="#todo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提高准确性。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解决发现的错误/问题。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">优化代码以使其更快。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h2><a id="user-content-contributing" class="anchor" aria-label="永久链接：贡献" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欢迎投稿😄</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拉取请求</font></font></h3><a id="user-content-pull-requests" class="anchor" aria-label="永久链接：拉取请求" href="#pull-requests"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">只是一些指导方针：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用适当的注释编写干净的代码并添加适当的错误处理。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试应用程序并确保没有出现错误/问题。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提出拉取请求，经过我方面的检查后，我将很高兴感谢您的贡献。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问题</font></font></h3><a id="user-content-issues" class="anchor" aria-label="永久链接：问题" href="#issues"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您发现任何错误/问题，请提出问题。</font></font></p>
</article></div>

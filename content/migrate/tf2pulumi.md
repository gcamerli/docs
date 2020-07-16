---
title: Convert Your Terraform to a Real Language
url: /tf2pulumi
layout: tf2pulumi
meta_desc: How to migrate to Pulumi from Terraform for huge productivity gains, and a unified programming model for Devs and DevOps.
---

<!--
TODO:
    - Upload code.
    - Multi-file projects.
    - Download button.
    - Syntax highlighting.
    - Retry...the first time it's slow (plugin download).
    - C# doesn't seem to work.
-->

<h3 class="text-gray-700 text-center">Step 1. Enter your Terraform</h3>
<div class="text-gray-500 text-center m-1 -mb-2 text-xs">
    (Don't worry, we send it over SSL and don't store it on our servers.)
</div>

{{< chooser input-kind "url,code,upload" >}}

{{% choosable input-kind "url" %}}

<input id="terraform-url" type="text" class="px-6 py-4 text-gray-700 text-sm w-full" value="https://">
</input>

{{% /choosable %}}

{{% choosable input-kind "code" %}}

<textarea id="terraform-code" rows="10" class="w-full px-6 py-4 text-gray-700 text-sm font-mono">
</textarea>

{{% /choosable %}}

{{% choosable input-kind "upload" %}}

<input id="terraform-upload" type="file" class="px-6 py-4 text-gray-700 text-sm w-full" onclick="alert('Not Yet Implemented -- check back soon! :-)'); return false">
</input>

{{% /choosable %}}

{{< /chooser >}}

<h3 class="text-gray-700 text-center">Step 2. Pick your Language</h3>

<div class="text-center w-full">
    <div class="inline-flex items-center bg-gray-200 rounded-lg p-2 text-center">
        <span title="JavaScript">
            <svg class="h-8 ml-1 rounded" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M0 0H100V100H0V0Z" fill="#F7DF1E"/>
                <path d="M26.2938 83.5672L33.9461 78.9359C35.4227 81.5535 36.7656 83.7684 39.9871 83.7684C43.075 83.7684 45.0223 82.5606 45.0223 77.8621V45.9098H54.4195V77.9949C54.4195 87.7281 48.7141 92.1586 40.3899 92.1586C32.8723 92.1586 28.5086 88.2652 26.2934 83.5664L26.2938 83.5672ZM59.5238 82.5602L67.1754 78.1301C69.1898 81.4195 71.8078 83.8359 76.4391 83.8359C80.3332 83.8359 82.816 81.8891 82.816 79.2039C82.816 75.982 80.2652 74.8406 75.9692 72.9617L73.6203 71.9539C66.8402 69.0684 62.343 65.4434 62.343 57.791C62.343 50.7426 67.7129 45.3723 76.1039 45.3723C82.0781 45.3723 86.3742 47.4535 89.4617 52.8906L82.1445 57.5899C80.5332 54.7035 78.7887 53.5625 76.1035 53.5625C73.3512 53.5625 71.6059 55.3078 71.6059 57.5899C71.6059 60.409 73.3512 61.5508 77.3785 63.2961L79.7277 64.3027C87.716 67.7266 92.2133 71.2168 92.2133 79.0699C92.2133 87.5285 85.568 92.1598 76.6402 92.1598C67.9141 92.1598 62.2754 87.9981 59.5234 82.5606" fill="black"/>
            </svg>
        </span>
        <span title="TypeScript">
            <svg class="mx-4 h-8 rounded" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M0 50V0H100V100H0" fill="#3B7BC6"/>
                <path d="M21.925 50.175V54.25H34.925V91.25H44.15V54.25H57.15V50.25C57.15 48 57.15 46.175 57.05 46.125C57.05 46.05 49.125 46.025 39.5 46.025L22 46.1V50.2L21.925 50.175ZM80.35 46C82.9 46.6 84.85 47.75 86.6 49.575C87.525 50.575 88.9 52.325 89 52.775C89 52.925 84.675 55.85 82.05 57.475C81.95 57.55 81.55 57.125 81.15 56.475C79.85 54.625 78.525 53.825 76.45 53.675C73.45 53.475 71.45 55.05 71.45 57.675C71.45 58.475 71.6 58.925 71.9 59.575C72.575 60.95 73.825 61.775 77.7 63.475C84.85 66.55 87.95 68.575 89.825 71.475C91.95 74.725 92.425 79.825 91 83.65C89.4 87.825 85.5 90.65 79.925 91.575C78.175 91.875 74.175 91.825 72.3 91.5C68.3 90.75 64.475 88.75 62.125 86.175C61.2 85.175 59.425 82.5 59.525 82.325L60.475 81.725L64.225 79.55L67.05 77.9L67.7 78.775C68.525 80.075 70.375 81.825 71.45 82.425C74.7 84.1 79.05 83.875 81.2 81.925C82.125 81.075 82.525 80.175 82.525 78.925C82.525 77.775 82.35 77.25 81.775 76.375C80.975 75.275 79.375 74.375 74.875 72.375C69.7 70.175 67.5 68.775 65.45 66.625C64.275 65.325 63.2 63.3 62.7 61.625C62.325 60.175 62.2 56.625 62.55 55.2C63.625 50.2 67.4 46.7 72.8 45.7C74.55 45.35 78.675 45.5 80.4 45.95L80.35 46Z" fill="white"/>
            </svg>
        </span>
        <span title="Python">
            <svg class="mr-3 h-8" viewBox="0 0 101 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M50.0246 0C24.4415 0 26.0389 11.0665 26.0389 11.0665L26.0673 22.5318H50.4807V25.974H16.3706C16.3706 25.974 0 24.122 0 49.8705C0 75.6197 14.2887 74.7066 14.2887 74.7066H22.8161V62.7579C22.8161 62.7579 22.3564 48.505 36.8767 48.505H61.0905C61.0905 48.505 74.6945 48.7243 74.6945 35.3901V13.3428C74.6945 13.3428 76.7607 0 50.0246 0ZM36.563 7.71017C37.1399 7.70965 37.7112 7.82262 38.2443 8.0426C38.7774 8.26258 39.2618 8.58526 39.6697 8.99217C40.0777 9.39908 40.4012 9.88224 40.6217 10.414C40.8422 10.9458 40.9555 11.5157 40.955 12.0911C40.9555 12.6666 40.8422 13.2365 40.6217 13.7683C40.4012 14.3 40.0777 14.7832 39.6697 15.1901C39.2618 15.597 38.7774 15.9197 38.2443 16.1397C37.7112 16.3596 37.1399 16.4726 36.563 16.4721C35.9861 16.4726 35.4147 16.3596 34.8816 16.1397C34.3486 15.9197 33.8642 15.597 33.4562 15.1901C33.0483 14.7832 32.7248 14.3 32.5043 13.7683C32.2838 13.2365 32.1705 12.6666 32.171 12.0911C32.1705 11.5157 32.2838 10.9458 32.5043 10.414C32.7248 9.88224 33.0483 9.39908 33.4562 8.99217C33.8642 8.58526 34.3486 8.26258 34.8816 8.0426C35.4147 7.82262 35.9861 7.70965 36.563 7.71017Z" fill="url(#paint0_linear)"/>
                <path d="M50.7511 100C76.3341 100 74.7368 88.9335 74.7368 88.9335L74.7084 77.4686H50.2945V74.0264H84.4046C84.4046 74.0264 100.775 75.8784 100.775 50.1291C100.775 24.3802 86.4865 25.2934 86.4865 25.2934H77.9591V37.2417C77.9591 37.2417 78.4188 51.4946 63.8985 51.4946H39.6847C39.6847 51.4946 26.0807 51.2753 26.0807 64.6099V86.6576C26.0807 86.6576 24.0149 100 50.7507 100H50.7511ZM64.2126 92.2906C63.6357 92.2911 63.0644 92.1782 62.5313 91.9582C61.9982 91.7382 61.5138 91.4156 61.1059 91.0086C60.698 90.6017 60.3745 90.1186 60.1539 89.5868C59.9334 89.055 59.8202 88.4851 59.8207 87.9097C59.8201 87.3342 59.9333 86.7642 60.1538 86.2324C60.3743 85.7006 60.6978 85.2174 61.1058 84.8105C61.5137 84.4035 61.9981 84.0808 62.5312 83.8608C63.0643 83.6408 63.6357 83.5278 64.2126 83.5283C64.7895 83.5278 65.3609 83.6408 65.894 83.8607C66.4271 84.0807 66.9114 84.4034 67.3194 84.8103C67.7273 85.2172 68.0508 85.7004 68.2713 86.2321C68.4919 86.7639 68.6051 87.3338 68.6046 87.9093C68.6051 88.4847 68.4919 89.0547 68.2713 89.5864C68.0508 90.1182 67.7273 90.6013 67.3194 91.0082C66.9114 91.4152 66.4271 91.7378 65.894 91.9578C65.3609 92.1778 64.7895 92.2908 64.2126 92.2902V92.2906Z" fill="url(#paint1_linear)"/>
                <defs>
                    <linearGradient id="paint0_linear" x1="9.68446" y1="8.9944" x2="59.5016" y2="58.4384" gradientUnits="userSpaceOnUse">
                        <stop stop-color="#387EB8"/>
                        <stop offset="1" stop-color="#366994"/>
                    </linearGradient>
                    <linearGradient id="paint1_linear" x1="40.3383" y1="40.6641" x2="93.8424" y2="91.3702" gradientUnits="userSpaceOnUse">
                        <stop stop-color="#FFE052"/>
                        <stop offset="1" stop-color="#FFC331"/>
                    </linearGradient>
                </defs>
            </svg>
        </span>
        <span title="Go">
            <svg class="h-4 mr-3" viewBox="0 0 200 75" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M15.0928 22.7088C14.7022 22.7088 14.6061 22.5127 14.8006 22.2202L16.8451 19.5815C17.0404 19.2882 17.5264 19.0929 17.9154 19.0929H52.6786C53.0693 19.0929 53.1654 19.3862 52.9708 19.6795L51.3146 22.2202C51.1193 22.5135 50.6333 22.8068 50.3412 22.8068L15.0912 22.7088H15.0928ZM0.389698 31.7009C-0.000925616 31.7009 -0.0970191 31.5049 0.0975117 31.2124L2.14204 28.5736C2.33735 28.2803 2.82329 28.0851 3.21235 28.0851H47.6162C48.0068 28.0851 48.2005 28.3784 48.1029 28.6716L47.324 31.0163C47.2263 31.4084 46.8372 31.6029 46.4474 31.6029L0.389698 31.7009ZM23.9545 40.6931C23.5639 40.6931 23.4678 40.3998 23.6623 40.1065L25.0256 37.663C25.2209 37.3697 25.61 37.0764 25.999 37.0764H45.474C45.8646 37.0764 46.0583 37.3697 46.0583 37.7602L45.863 40.1049C45.863 40.497 45.4724 40.7887 45.1818 40.7887L23.9537 40.6907L23.9545 40.6931ZM125.032 20.9491L108.671 25.2495C107.21 25.6416 107.113 25.7381 105.846 24.2724C104.386 22.61 103.315 21.5278 101.27 20.5586C95.1356 17.5285 89.195 18.4084 83.645 22.025C77.0231 26.3254 73.6153 32.6788 73.7122 40.5958C73.8098 48.4141 79.1653 54.8663 86.8583 55.9421C93.4801 56.822 99.0301 54.4757 103.413 49.4915C104.289 48.4172 105.069 47.2433 106.042 45.8749H87.2489C85.2044 45.8749 84.7176 44.6045 85.3989 42.9421C86.6645 39.912 89.002 34.8298 90.3653 32.2883C90.6575 31.7017 91.3387 30.7246 92.7996 30.7246H128.245C128.05 33.3634 128.05 36.0021 127.66 38.6417C126.59 45.6789 123.961 52.1295 119.676 57.7991C112.665 67.0837 103.512 72.8513 91.9239 74.4158C82.3809 75.6861 73.52 73.8292 65.7286 67.9651C58.5146 62.49 54.4325 55.2568 53.3615 46.2654C52.0958 35.6116 55.2115 26.0337 61.6388 17.6273C68.5528 8.53716 77.7059 2.77033 88.9043 0.718139C98.0574 -0.944314 106.821 0.131575 114.709 5.5071C119.87 8.92767 123.57 13.6194 126.006 19.289C126.59 20.1688 126.201 20.6574 125.032 20.9514V20.9491Z" fill="#00ACD7"/>
                <path d="M157.262 75C148.401 74.804 140.318 72.2554 133.502 66.3976C127.757 61.4126 124.154 55.0584 122.986 47.5335C121.233 36.4883 124.252 26.7136 130.874 18.0155C137.983 8.63206 146.551 3.74508 158.139 1.69289C168.072 -0.0667977 177.421 0.91107 185.892 6.6779C193.585 11.9554 198.356 19.0914 199.622 28.4741C201.278 41.6694 197.48 52.4204 188.424 61.6086C181.997 68.1565 174.11 72.2624 165.053 74.1194C162.425 74.6079 159.796 74.7059 157.264 74.9992L157.262 75ZM180.438 35.5128C180.34 34.2425 180.34 33.2646 180.146 32.2875C178.392 22.6108 169.532 17.1372 160.281 19.2882C151.225 21.3404 145.382 27.1065 143.24 36.2954C141.487 43.9192 145.188 51.6418 152.199 54.7683C157.554 57.113 162.91 56.8205 168.071 54.1817C175.764 50.1824 179.951 43.9192 180.439 35.5128H180.438Z" fill="#00ACD7"/>
            </svg>
        </span>
        <span title=".NET Core">
            <svg class="h-8 mr-1 rounded" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 64 64"><defs><style>.cls-1{fill:#5c2d91;}.cls-2,.cls-3{fill:#fff;}.cls-2{opacity:0.1;}.cls-4{fill:#f2f2f2;}</style></defs><title>logo_NETcore</title><circle class="cls-1" cx="32" cy="32" r="32"/><path class="cls-2" d="M9.82,9A32,32,0,1,0,55,54.18Z"/><path class="cls-3" d="M7.4,37.25a1.35,1.35,0,0,1-1-.42,1.38,1.38,0,0,1-.41-1,1.4,1.4,0,0,1,.41-1,1.34,1.34,0,0,1,1-.43,1.37,1.37,0,0,1,1,.43,1.39,1.39,0,0,1,.42,1,1.37,1.37,0,0,1-.42,1A1.38,1.38,0,0,1,7.4,37.25Z"/><path class="cls-3" d="M27.27,37H24.65L15.28,22.46a6,6,0,0,1-.58-1.14h-.08a18.72,18.72,0,0,1,.1,2.5V37H12.59V18.77h2.77l9.12,14.28q.57.89.74,1.22h.05a19.28,19.28,0,0,1-.13-2.68V18.77h2.13Z"/><path class="cls-3" d="M41.69,37H32V18.77h9.24V20.7H34.18v6.06h6.58v1.92H34.18V35h7.52Z"/><path class="cls-3" d="M56,20.7H50.7V37H48.57V20.7H43.33V18.77H56Z"/><path class="cls-4" d="M26.12,49.4a4.93,4.93,0,0,1-2.32.49,3.74,3.74,0,0,1-2.87-1.15,4.26,4.26,0,0,1-1.08-3,4.46,4.46,0,0,1,1.21-3.26,4.12,4.12,0,0,1,3.08-1.24,4.93,4.93,0,0,1,2,.35v1a4,4,0,0,0-2-.5,3.06,3.06,0,0,0-2.35,1,3.64,3.64,0,0,0-.9,2.58,3.47,3.47,0,0,0,.84,2.45,2.86,2.86,0,0,0,2.21.91,4.14,4.14,0,0,0,2.19-.56Z"/><path class="cls-4" d="M30.21,49.89A2.78,2.78,0,0,1,28.08,49a3.11,3.11,0,0,1-.79-2.23,3.24,3.24,0,0,1,.83-2.36,3,3,0,0,1,2.23-.85,2.69,2.69,0,0,1,2.09.83,3.28,3.28,0,0,1,.75,2.29,3.22,3.22,0,0,1-.81,2.3A2.84,2.84,0,0,1,30.21,49.89Zm.07-5.47a1.83,1.83,0,0,0-1.46.63,2.59,2.59,0,0,0-.54,1.74,2.45,2.45,0,0,0,.54,1.68,1.85,1.85,0,0,0,1.46.62,1.76,1.76,0,0,0,1.43-.6,2.62,2.62,0,0,0,.5-1.72,2.66,2.66,0,0,0-.5-1.73A1.75,1.75,0,0,0,30.28,44.42Z"/><path class="cls-4" d="M37.86,44.72a1.18,1.18,0,0,0-.73-.19,1.23,1.23,0,0,0-1,.58,2.68,2.68,0,0,0-.41,1.58v3.06h-1v-6h1V45h0a2.1,2.1,0,0,1,.63-1,1.43,1.43,0,0,1,.94-.35,1.57,1.57,0,0,1,.57.08Z"/><path class="cls-4" d="M43.72,47H39.49A2.24,2.24,0,0,0,40,48.54a1.86,1.86,0,0,0,1.42.54,3,3,0,0,0,1.86-.67v.9a3.48,3.48,0,0,1-2.09.57,2.54,2.54,0,0,1-2-.82,3.35,3.35,0,0,1-.73-2.3,3.28,3.28,0,0,1,.79-2.28,2.55,2.55,0,0,1,2-.88,2.26,2.26,0,0,1,1.82.76,3.18,3.18,0,0,1,.64,2.12Zm-1-.81a2,2,0,0,0-.4-1.29,1.37,1.37,0,0,0-1.1-.46,1.55,1.55,0,0,0-1.15.49,2.21,2.21,0,0,0-.59,1.27Z"/></svg>
        </span>
    </div>
</div>

{{< chooser language "javascript,typescript,python,go,csharp" >}}

{{% choosable language "javascript" %}}

<div class="highlight">
    <pre class="chroma"><code id="pulumi-code-javascript" class="language-javascript" data-lang="javascript">// Hit "CONVERT" below to get the code!</code></pre>
    <div class="copy-button-container">
        <pulumi-tooltip class="hydrated">
            <span class="tooltip-target" aria-labelledby="e5d01457-503c-4908-a0eb-a9ef5250579d">
                <button class="copy-button"><i class="far fa-copy copy text-xl"></i></button>
            </span>
            <span class="tooltip-content" role="tooltip" id="e5d01457-503c-4908-a0eb-a9ef5250579d">
                <span slot="content">Click to copy</span>
            </span>
        </pulumi-tooltip>
    </div>
</div>


{{% /choosable %}}

{{% choosable language "typescript" %}}

<div class="highlight">
    <pre class="chroma"><code id="pulumi-code-typescript" class="language-typescript" data-lang="typescript">// Hit "CONVERT" below to get the code!</code></pre>
    <div class="copy-button-container">
        <pulumi-tooltip class="hydrated">
            <span class="tooltip-target" aria-labelledby="e5d01457-503c-4908-a0eb-a9ef5250579d">
                <button class="copy-button"><i class="far fa-copy copy text-xl"></i></button>
            </span>
            <span class="tooltip-content" role="tooltip" id="e5d01457-503c-4908-a0eb-a9ef5250579d">
                <span slot="content">Click to copy</span>
            </span>
        </pulumi-tooltip>
    </div>
</div>

{{% /choosable %}}

{{% choosable language "python" %}}

<div class="highlight">
    <pre class="chroma"><code id="pulumi-code-python" class="language-python" data-lang="python"># Hit "CONVERT" below to get the code!</code></pre>
    <div class="copy-button-container">
        <pulumi-tooltip class="hydrated">
            <span class="tooltip-target" aria-labelledby="e5d01457-503c-4908-a0eb-a9ef5250579d">
                <button class="copy-button"><i class="far fa-copy copy text-xl"></i></button>
            </span>
            <span class="tooltip-content" role="tooltip" id="e5d01457-503c-4908-a0eb-a9ef5250579d">
                <span slot="content">Click to copy</span>
            </span>
        </pulumi-tooltip>
    </div>
</div>

{{% /choosable %}}

{{% choosable language "go" %}}

<div class="highlight">
    <pre class="chroma"><code id="pulumi-code-go" class="language-go" data-lang="go">// Hit "CONVERT" below to get the code!</code></pre>
    <div class="copy-button-container">
        <pulumi-tooltip class="hydrated">
            <span class="tooltip-target" aria-labelledby="e5d01457-503c-4908-a0eb-a9ef5250579d">
                <button class="copy-button"><i class="far fa-copy copy text-xl"></i></button>
            </span>
            <span class="tooltip-content" role="tooltip" id="e5d01457-503c-4908-a0eb-a9ef5250579d">
                <span slot="content">Click to copy</span>
            </span>
        </pulumi-tooltip>
    </div>
</div>

{{% /choosable %}}

{{% choosable language "csharp" %}}

<div class="highlight">
    <pre class="chroma"><code id="pulumi-code-csharp" class="language-csharp" data-lang="csharp">// Hit "CONVERT" below to get the code!</code></pre>
    <div class="copy-button-container">
        <pulumi-tooltip class="hydrated">
            <span class="tooltip-target" aria-labelledby="e5d01457-503c-4908-a0eb-a9ef5250579d">
                <button class="copy-button"><i class="far fa-copy copy text-xl"></i></button>
            </span>
            <span class="tooltip-content" role="tooltip" id="e5d01457-503c-4908-a0eb-a9ef5250579d">
                <span slot="content">Click to copy</span>
            </span>
        </pulumi-tooltip>
    </div>
</div>

{{% /choosable %}}

{{< /chooser >}}

<div id="pulumi-errors" class="text-center text-sm font-bold font-mono" style="color:#ff0000"></div>
<div id="pulumi-warnings" class="text-center text-sm font-bold font-mono" style="color:#ff9900"></div>

<h3 class="text-gray-700 text-center">Step 3. Convert!</h3>

<script>
// Extracts a query string variable from the browser's location.
function getQueryVariable(variable) {
    var query = window.location.search.substring(1);
    var vars = query.split("&");

    for (var i = 0; i < vars.length; i++) {
        var pair = vars[i].split("=");

        if (pair[0] === variable) {
            return decodeURIComponent(pair[1].replace(/\+/g, "%20"));
        }
    }
}

// Now set up our event handler for conversion.
function convertCode() {
    // Get the currently chosen language.
    // TODO: I suspect there's a better way to do this!
    let language = "";
    $("pulumi-chooser > ul > li.active > a").each(function (i, e) {
        language = e.innerText.toLowerCase();
    });
    let languageTextbox = language;
    if (language === "c#") {
        language = "csharp";
        languageTextbox = "csharp";
    } else if (language === "javascript") {
        language = "typescript";
        languageTextbox = "javascript";
    }
    console.log(language);

    // Clear the current fields.
    $("#pulumi-errors").text("");
    $("#pulumi-warnings").text("");
    $("#pulumi-code-" + languageTextbox).text("...");

    // Now read the various possible code sources.
    let tfCode = $("#terraform-code").val();
    let tfUrl = $("#terraform-url").val();
    if (tfUrl === "https://") {
        tfUrl = "";
    }
    // let tfUpload = document.getElementById("terraform-upload").value;

    // Post to the endpoint and then, afterwards, add the result to the textbox.
    const payload = JSON.stringify({
        code: tfCode,
        url: tfUrl,
        language: language,
    });
    $(document.body).css({"cursor": "wait"});
    $("#convert-button").css({"cursor": "wait"});
    $.post({
        url: "https://7r4m6oz4s5.execute-api.us-west-2.amazonaws.com/stage/convert",
        data: payload,
        dataType: "json",
    }).done(function(data) {
        $("#pulumi-code-" + languageTextbox).text(data.code);
        if (data.diagnostics) {
            $("#pulumi-warnings").text(data.diagnostics);
        }
    }).fail(function(err) {
        let errorText = "An unspecified error occurred";
        if (err) {
            if (err.responseText) {
                errorText = err.responseText;
                try {
                    let errdata = JSON.parse(err.responseText);
                    if (errdata.error) {
                        errorText = errdata.error;
                    }
                } catch {
                    // ignore.
                }
            }
            errorText += " [" + err.statusText + " " + err.status + "]";
        }
        $("#pulumi-errors").text(errorText);
    }).always(function() {
        $(document.body).css({"cursor": "default"});
        $("#convert-button").css({"cursor": "pointer"});
    });
}

window.onload = function() {
    // If there are querystring parameters populate the fields.
    let tfUrl = getQueryVariable("url");
    if (tfUrl) {
        $("#terraform-url").val(tfUrl);
        selectInputKind("url");
    }

    // Adjust some of the UI elements.
    $("#terraform-url").click(function() {
        $(this).select();
    });

    // If you hit enter in the URL bar, submit.
    $("#terraform-url").keypress(function (e) {
        if (e.which == 13) {
            convertCode();
            return false;
        }
    });
}
</script>

<div class="text-center pt-8">
    <a id="convert-button" class="btn btn-lg mr-4" onclick="convertCode()">Convert</a>
</div>
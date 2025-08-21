<animateTransform attributeName="transform" attributeType="XML" type="rotate" values="10 0 0; -12 0 0; 10 0 0" dur="1.2s" repeatCount="indefinite"/>
</g>


<!-- Body -->
<g filter="url(#shadow)">
<ellipse cx="110" cy="130" rx="68" ry="54" fill="url(#fur)"/>
</g>


<!-- Head group for subtle bob -->
<g id="head" transform="translate(0 -2)">
<animateTransform attributeName="transform" type="translate" values="0 -2; 0 0; 0 -2" dur="1.6s" repeatCount="indefinite"/>


<!-- Ears -->
<g>
<path d="M62 62 L78 22 L94 62 Z" fill="url(#fur)"/>
<path d="M62 62 L78 28 L90 62 Z" fill="url(#innerEar)"/>
<path d="M126 62 L142 22 L158 62 Z" fill="url(#fur)"/>
<path d="M130 62 L142 28 L154 62 Z" fill="url(#innerEar)"/>
</g>


<!-- Face -->
<circle cx="110" cy="90" r="46" fill="url(#fur)"/>


<!-- Eyes (blink) -->
<g>
<ellipse cx="92" cy="90" rx="8" ry="10" fill="#0e0e0e">
<animate attributeName="ry" values="10;1;10" dur="3.4s" repeatCount="indefinite"/>
</ellipse>
<ellipse cx="128" cy="90" rx="8" ry="10" fill="#0e0e0e">
<animate attributeName="ry" values="10;1;10" dur="3.4s" begin="0.1s" repeatCount="indefinite"/>
</ellipse>
<!-- Eye shine -->
<circle cx="95" cy="86" r="2" fill="#ffffff" opacity="0.8"/>
<circle cx="131" cy="86" r="2" fill="#ffffff" opacity="0.8"/>
</g>


<!-- Nose & mouth -->
<polygon points="110,102 116,108 104,108" fill="#e28a8a"/>
<path d="M110 108 q -6 8 -14 8" stroke="#1a1a1a" stroke-width="2" fill="none" stroke-linecap="round"/>
<path d="M110 108 q 6 8 14 8" stroke="#1a1a1a" stroke-width="2" fill="none" stroke-linecap="round"/>


<!-- Whiskers -->
<g stroke="#e0e0e0" stroke-width="2" stroke-linecap="round">
<path d="M78 104 H52"/>
<path d="M80 110 H54"/>
<path d="M142 104 H168"/>
<path d="M140 110 H166"/>
</g>


<!-- Cheek blush (pulse) -->
<g opacity="0.7">
<circle cx="86" cy="106" r="8" fill="#ff8aa0">
<animate attributeName="r" values="8;10;8" dur="1.8s" repeatCount="indefinite"/>
</circle>
<circle cx="134" cy="106" r="8" fill="#ff8aa0">
<animate attributeName="r" values="8;10;8" dur="1.8s" begin="0.2s" repeatCount="indefinite"/>
</circle>
</g>
</g>


<!-- Tiny heart pop -->
<g>
<path id="heart" d="M110 52 c-4 -8 -18 -6 -18 6 c0 12 18 18 18 28 c0 -10 18 -16 18 -28 c0 -12 -14 -14 -18 -6z" fill="#ff5d8f" opacity="0">
<animate attributeName="opacity" values="0;1;0" dur="2.5s" repeatCount="indefinite"/>
<animateTransform attributeName="transform" type="translate" values="0 0; 0 -8; 0 0" dur="2.5s" repeatCount="indefinite"/>
</path>
</g>
</svg>
<!---
msulthannasyira/msulthannasyira is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

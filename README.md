<!DOCTYPE html>
<!-- saved from url=(0039)https://vn9th.github.io/VidyaNirman9th/ -->
<html lang="en" class="scroll-smooth"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vidya Nirman | विद्या निर्माण - Class 9th Interactive Portal</title>
    <link rel="icon" type="image/png" href="./Vidya Nirman _ विद्या निर्माण - Class 9th Interactive Portal_files/logo.png">
    <!-- Tailwind CSS CDN -->
    <script src="./Vidya Nirman _ विद्या निर्माण - Class 9th Interactive Portal_files/saved_resource"></script>
    
    <!-- FontAwesome Icons CDN -->
    <link rel="stylesheet" href="./Vidya Nirman _ विद्या निर्माण - Class 9th Interactive Portal_files/all.min.css">
    
    <!-- Google Fonts: Cinzel, Noto Serif Devanagari, Plus Jakarta Sans -->
    <link rel="preconnect" href="https://fonts.googleapis.com/">
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="">
    <link href="./Vidya Nirman _ विद्या निर्माण - Class 9th Interactive Portal_files/css2" rel="stylesheet">

    <style>
        :root {
            --bg-maroon-dark: #0F0103;
            --bg-maroon-deep: #220308;
            --bg-maroon-mid: #3B0810;
            --gold-primary: #D4AF37;
            --gold-bright: #FFD700;
            --gold-glow: rgba(212, 175, 55, 0.45);
            --saffron: #FF8C00;
            --parchment: #FFF9E6;
        }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: var(--bg-maroon-dark);
            color: var(--parchment);
            overflow-x: hidden;
        }

        .font-devanagari {
            font-family: 'Noto Serif Devanagari', serif;
        }

        .font-cinzel {
            font-family: 'Cinzel', serif;
        }

        /* Traditional Jali Grid Pattern Background */
        .jali-pattern {
            background-image: radial-gradient(circle, rgba(212, 175, 55, 0.12) 1.2px, transparent 1.2px);
            background-size: 26px 26px;
        }

        /* Shimmering Metallic Gold Gradient Text */
        .text-gold-gradient {
            background: linear-gradient(135deg, #FFF0B3 0%, #FFD700 35%, #D4AF37 65%, #996515 100%);
            background-size: 200% auto;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: shine 7s linear infinite;
        }

        @keyframes shine {
            to { background-position: 200% center; }
        }

        /* Gold Gradient Cards & Glowing Borders */
        .border-gold-glow {
            border: 1px solid rgba(212, 175, 55, 0.35);
            box-shadow: 0 6px 24px -2px rgba(212, 175, 55, 0.15);
            transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1);
        }

        .border-gold-glow:hover {
            border-color: rgba(255, 215, 0, 0.85);
            box-shadow: 0 12px 35px -2px rgba(212, 175, 55, 0.45);
            transform: translateY(-4px);
        }

        .bg-gold-gradient {
            background: linear-gradient(135deg, #FFD700 0%, #D4AF37 50%, #B8860B 100%);
        }

        .bg-maroon-card {
            background: linear-gradient(145deg, rgba(48, 5, 12, 0.92), rgba(20, 2, 5, 0.96));
            backdrop-filter: blur(12px);
        }

        /* Rotating Mandala Elements */
        @keyframes spinSlow {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }

        @keyframes spinSlowReverse {
            from { transform: rotate(0deg); }
            to { transform: rotate(-360deg); }
        }

        .spin-slow {
            animation: spinSlow 55s linear infinite;
        }

        .spin-slow-reverse {
            animation: spinSlowReverse 70s linear infinite;
        }

        /* Floating Animation */
        @keyframes floatUpDown {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }

        .animate-float {
            animation: floatUpDown 4.2s ease-in-out infinite;
        }

        /* Flame/Diya Pulsing Glow */
        @keyframes flamePulse {
            0%, 100% { filter: drop-shadow(0 0 6px rgba(255, 140, 0, 0.8)); transform: scale(1); }
            50% { filter: drop-shadow(0 0 14px rgba(255, 215, 0, 0.95)); transform: scale(1.08); }
        }

        .animate-flame {
            animation: flamePulse 2s ease-in-out infinite;
        }

        /* 3D Tilt Card Base */
        .tilt-card {
            transform-style: preserve-3d;
            transition: transform 0.25s ease-out, box-shadow 0.25s ease-out;
        }

        /* Marquee Continuous Banner */
        @keyframes marquee {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }
        .animate-marquee {
            display: inline-block;
            white-space: nowrap;
            animation: marquee 30s linear infinite;
        }
        .animate-marquee:hover {
            animation-play-state: paused;
        }

        /* Custom Golden Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0F0103;
        }
        ::-webkit-scrollbar-thumb {
            background: #D4AF37;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #FFD700;
        }
    </style>
<style>*, ::before, ::after{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }/* ! tailwindcss v3.4.17 | MIT License | https://tailwindcss.com */*,::after,::before{box-sizing:border-box;border-width:0;border-style:solid;border-color:#e5e7eb}::after,::before{--tw-content:''}:host,html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;tab-size:4;font-family:ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";font-feature-settings:normal;font-variation-settings:normal;-webkit-tap-highlight-color:transparent}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;font-feature-settings:normal;font-variation-settings:normal;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-feature-settings:inherit;font-variation-settings:inherit;font-size:100%;font-weight:inherit;line-height:inherit;letter-spacing:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}button,input:where([type=button]),input:where([type=reset]),input:where([type=submit]){-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0;padding:0}legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}dialog{padding:0}textarea{resize:vertical}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]:where(:not([hidden=until-found])){display:none}.pointer-events-none{pointer-events:none}.fixed{position:fixed}.absolute{position:absolute}.relative{position:relative}.sticky{position:sticky}.inset-0{inset:0px}.-bottom-1{bottom:-0.25rem}.-bottom-52{bottom:-13rem}.-left-52{left:-13rem}.-right-1{right:-0.25rem}.-right-24{right:-6rem}.-right-52{right:-13rem}.-top-24{top:-6rem}.-top-52{top:-13rem}.right-4{right:1rem}.top-0{top:0px}.top-4{top:1rem}.z-0{z-index:0}.z-10{z-index:10}.z-50{z-index:50}.col-span-2{grid-column:span 2 / span 2}.mx-auto{margin-left:auto;margin-right:auto}.my-3{margin-top:0.75rem;margin-bottom:0.75rem}.my-6{margin-top:1.5rem;margin-bottom:1.5rem}.mb-1{margin-bottom:0.25rem}.mb-10{margin-bottom:2.5rem}.mb-12{margin-bottom:3rem}.mb-14{margin-bottom:3.5rem}.mb-16{margin-bottom:4rem}.mb-2{margin-bottom:0.5rem}.mb-3{margin-bottom:0.75rem}.mb-4{margin-bottom:1rem}.mb-6{margin-bottom:1.5rem}.mb-8{margin-bottom:2rem}.ml-1{margin-left:0.25rem}.mr-1{margin-right:0.25rem}.mr-2{margin-right:0.5rem}.mt-1{margin-top:0.25rem}.mt-2{margin-top:0.5rem}.mt-3{margin-top:0.75rem}.block{display:block}.flex{display:flex}.inline-flex{display:inline-flex}.grid{display:grid}.hidden{display:none}.h-1{height:0.25rem}.h-12{height:3rem}.h-20{height:5rem}.h-28{height:7rem}.h-72{height:18rem}.h-8{height:2rem}.h-\[700px\]{height:700px}.h-full{height:100%}.h-px{height:1px}.min-h-screen{min-height:100vh}.w-12{width:3rem}.w-28{width:7rem}.w-72{width:18rem}.w-8{width:2rem}.w-\[700px\]{width:700px}.w-full{width:100%}.max-w-2xl{max-width:42rem}.max-w-3xl{max-width:48rem}.max-w-6xl{max-width:72rem}.max-w-7xl{max-width:80rem}.max-w-lg{max-width:32rem}.max-w-md{max-width:28rem}.max-w-xl{max-width:36rem}.shrink-0{flex-shrink:0}@keyframes bounce{0%, 100%{transform:translateY(-25%);animation-timing-function:cubic-bezier(0.8,0,1,1)}50%{transform:none;animation-timing-function:cubic-bezier(0,0,0.2,1)}}.animate-bounce{animation:bounce 1s infinite}.grid-cols-1{grid-template-columns:repeat(1, minmax(0, 1fr))}.grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.flex-col{flex-direction:column}.flex-wrap{flex-wrap:wrap}.items-center{align-items:center}.justify-center{justify-content:center}.justify-between{justify-content:space-between}.gap-1\.5{gap:0.375rem}.gap-2{gap:0.5rem}.gap-2\.5{gap:0.625rem}.gap-3{gap:0.75rem}.gap-3\.5{gap:0.875rem}.gap-4{gap:1rem}.gap-6{gap:1.5rem}.gap-8{gap:2rem}.space-x-12 > :not([hidden]) ~ :not([hidden]){--tw-space-x-reverse:0;margin-right:calc(3rem * var(--tw-space-x-reverse));margin-left:calc(3rem * calc(1 - var(--tw-space-x-reverse)))}.space-x-6 > :not([hidden]) ~ :not([hidden]){--tw-space-x-reverse:0;margin-right:calc(1.5rem * var(--tw-space-x-reverse));margin-left:calc(1.5rem * calc(1 - var(--tw-space-x-reverse)))}.space-y-2 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.5rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.5rem * var(--tw-space-y-reverse))}.space-y-2\.5 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.625rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.625rem * var(--tw-space-y-reverse))}.space-y-3 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.75rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.75rem * var(--tw-space-y-reverse))}.space-y-4 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1rem * var(--tw-space-y-reverse))}.divide-y > :not([hidden]) ~ :not([hidden]){--tw-divide-y-reverse:0;border-top-width:calc(1px * calc(1 - var(--tw-divide-y-reverse)));border-bottom-width:calc(1px * var(--tw-divide-y-reverse))}.divide-amber-500\/10 > :not([hidden]) ~ :not([hidden]){border-color:rgb(245 158 11 / 0.1)}.overflow-hidden{overflow:hidden}.overflow-x-auto{overflow-x:auto}.scroll-smooth{scroll-behavior:smooth}.rounded{border-radius:0.25rem}.rounded-2xl{border-radius:1rem}.rounded-3xl{border-radius:1.5rem}.rounded-full{border-radius:9999px}.rounded-lg{border-radius:0.5rem}.rounded-md{border-radius:0.375rem}.rounded-xl{border-radius:0.75rem}.border{border-width:1px}.border-2{border-width:2px}.border-y{border-top-width:1px;border-bottom-width:1px}.border-b{border-bottom-width:1px}.border-l-2{border-left-width:2px}.border-t{border-top-width:1px}.border-amber-400{--tw-border-opacity:1;border-color:rgb(251 191 36 / var(--tw-border-opacity, 1))}.border-amber-400\/40{border-color:rgb(251 191 36 / 0.4)}.border-amber-400\/50{border-color:rgb(251 191 36 / 0.5)}.border-amber-400\/60{border-color:rgb(251 191 36 / 0.6)}.border-amber-400\/80{border-color:rgb(251 191 36 / 0.8)}.border-amber-500\/20{border-color:rgb(245 158 11 / 0.2)}.border-amber-500\/30{border-color:rgb(245 158 11 / 0.3)}.border-amber-500\/40{border-color:rgb(245 158 11 / 0.4)}.border-cyan-500\/30{border-color:rgb(6 182 212 / 0.3)}.border-cyan-500\/40{border-color:rgb(6 182 212 / 0.4)}.border-emerald-500\/30{border-color:rgb(16 185 129 / 0.3)}.border-emerald-500\/40{border-color:rgb(16 185 129 / 0.4)}.bg-\[\#0A0002\]{--tw-bg-opacity:1;background-color:rgb(10 0 2 / var(--tw-bg-opacity, 1))}.bg-\[\#0F0103\]{--tw-bg-opacity:1;background-color:rgb(15 1 3 / var(--tw-bg-opacity, 1))}.bg-\[\#0F0103\]\/90{background-color:rgb(15 1 3 / 0.9)}.bg-\[\#180206\]{--tw-bg-opacity:1;background-color:rgb(24 2 6 / var(--tw-bg-opacity, 1))}.bg-\[\#1A0206\]{--tw-bg-opacity:1;background-color:rgb(26 2 6 / var(--tw-bg-opacity, 1))}.bg-\[\#220308\]{--tw-bg-opacity:1;background-color:rgb(34 3 8 / var(--tw-bg-opacity, 1))}.bg-amber-400{--tw-bg-opacity:1;background-color:rgb(251 191 36 / var(--tw-bg-opacity, 1))}.bg-amber-500{--tw-bg-opacity:1;background-color:rgb(245 158 11 / var(--tw-bg-opacity, 1))}.bg-amber-500\/10{background-color:rgb(245 158 11 / 0.1)}.bg-amber-500\/20{background-color:rgb(245 158 11 / 0.2)}.bg-amber-500\/30{background-color:rgb(245 158 11 / 0.3)}.bg-amber-900\/60{background-color:rgb(120 53 15 / 0.6)}.bg-amber-950{--tw-bg-opacity:1;background-color:rgb(69 26 3 / var(--tw-bg-opacity, 1))}.bg-amber-950\/60{background-color:rgb(69 26 3 / 0.6)}.bg-amber-950\/80{background-color:rgb(69 26 3 / 0.8)}.bg-cyan-500\/20{background-color:rgb(6 182 212 / 0.2)}.bg-cyan-900\/60{background-color:rgb(22 78 99 / 0.6)}.bg-cyan-950{--tw-bg-opacity:1;background-color:rgb(8 51 68 / var(--tw-bg-opacity, 1))}.bg-emerald-500\/20{background-color:rgb(16 185 129 / 0.2)}.bg-emerald-900\/60{background-color:rgb(6 78 59 / 0.6)}.bg-emerald-950{--tw-bg-opacity:1;background-color:rgb(2 44 34 / var(--tw-bg-opacity, 1))}.bg-slate-950\/80{background-color:rgb(2 6 23 / 0.8)}.bg-gradient-to-b{background-image:linear-gradient(to bottom, var(--tw-gradient-stops))}.bg-gradient-to-r{background-image:linear-gradient(to right, var(--tw-gradient-stops))}.from-\[\#0F0103\]{--tw-gradient-from:#0F0103 var(--tw-gradient-from-position);--tw-gradient-to:rgb(15 1 3 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-\[\#3B0810\]{--tw-gradient-from:#3B0810 var(--tw-gradient-from-position);--tw-gradient-to:rgb(59 8 16 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-amber-500{--tw-gradient-from:#f59e0b var(--tw-gradient-from-position);--tw-gradient-to:rgb(245 158 11 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-amber-500\/10{--tw-gradient-from:rgb(245 158 11 / 0.1) var(--tw-gradient-from-position);--tw-gradient-to:rgb(245 158 11 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-amber-500\/30{--tw-gradient-from:rgb(245 158 11 / 0.3) var(--tw-gradient-from-position);--tw-gradient-to:rgb(245 158 11 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-amber-600{--tw-gradient-from:#d97706 var(--tw-gradient-from-position);--tw-gradient-to:rgb(217 119 6 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-cyan-600{--tw-gradient-from:#0891b2 var(--tw-gradient-from-position);--tw-gradient-to:rgb(8 145 178 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-emerald-600{--tw-gradient-from:#059669 var(--tw-gradient-from-position);--tw-gradient-to:rgb(5 150 105 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-transparent{--tw-gradient-from:transparent var(--tw-gradient-from-position);--tw-gradient-to:rgb(0 0 0 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.via-\[\#220308\]{--tw-gradient-to:rgb(34 3 8 / 0)  var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), #220308 var(--tw-gradient-via-position), var(--tw-gradient-to)}.via-\[\#2A050C\]{--tw-gradient-to:rgb(42 5 12 / 0)  var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), #2A050C var(--tw-gradient-via-position), var(--tw-gradient-to)}.via-amber-400{--tw-gradient-to:rgb(251 191 36 / 0)  var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), #fbbf24 var(--tw-gradient-via-position), var(--tw-gradient-to)}.via-amber-400\/20{--tw-gradient-to:rgb(251 191 36 / 0)  var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), rgb(251 191 36 / 0.2) var(--tw-gradient-via-position), var(--tw-gradient-to)}.via-amber-500\/30{--tw-gradient-to:rgb(245 158 11 / 0)  var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), rgb(245 158 11 / 0.3) var(--tw-gradient-via-position), var(--tw-gradient-to)}.via-yellow-400{--tw-gradient-to:rgb(250 204 21 / 0)  var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), #facc15 var(--tw-gradient-via-position), var(--tw-gradient-to)}.to-\[\#0F0103\]{--tw-gradient-to:#0F0103 var(--tw-gradient-to-position)}.to-\[\#1A0005\]{--tw-gradient-to:#1A0005 var(--tw-gradient-to-position)}.to-\[\#1F0207\]{--tw-gradient-to:#1F0207 var(--tw-gradient-to-position)}.to-amber-500\/10{--tw-gradient-to:rgb(245 158 11 / 0.1) var(--tw-gradient-to-position)}.to-amber-600{--tw-gradient-to:#d97706 var(--tw-gradient-to-position)}.to-amber-700\/30{--tw-gradient-to:rgb(180 83 9 / 0.3) var(--tw-gradient-to-position)}.to-amber-800{--tw-gradient-to:#92400e var(--tw-gradient-to-position)}.to-cyan-800{--tw-gradient-to:#155e75 var(--tw-gradient-to-position)}.to-emerald-800{--tw-gradient-to:#065f46 var(--tw-gradient-to-position)}.to-transparent{--tw-gradient-to:transparent var(--tw-gradient-to-position)}.object-cover{object-fit:cover}.p-1{padding:0.25rem}.p-2{padding:0.5rem}.p-2\.5{padding:0.625rem}.p-3{padding:0.75rem}.p-4{padding:1rem}.p-6{padding:1.5rem}.p-8{padding:2rem}.px-2{padding-left:0.5rem;padding-right:0.5rem}.px-2\.5{padding-left:0.625rem;padding-right:0.625rem}.px-3{padding-left:0.75rem;padding-right:0.75rem}.px-3\.5{padding-left:0.875rem;padding-right:0.875rem}.px-4{padding-left:1rem;padding-right:1rem}.px-5{padding-left:1.25rem;padding-right:1.25rem}.px-6{padding-left:1.5rem;padding-right:1.5rem}.px-8{padding-left:2rem;padding-right:2rem}.py-0\.5{padding-top:0.125rem;padding-bottom:0.125rem}.py-1{padding-top:0.25rem;padding-bottom:0.25rem}.py-1\.5{padding-top:0.375rem;padding-bottom:0.375rem}.py-12{padding-top:3rem;padding-bottom:3rem}.py-16{padding-top:4rem;padding-bottom:4rem}.py-2{padding-top:0.5rem;padding-bottom:0.5rem}.py-2\.5{padding-top:0.625rem;padding-bottom:0.625rem}.py-20{padding-top:5rem;padding-bottom:5rem}.py-3{padding-top:0.75rem;padding-bottom:0.75rem}.py-3\.5{padding-top:0.875rem;padding-bottom:0.875rem}.py-4{padding-top:1rem;padding-bottom:1rem}.pb-16{padding-bottom:4rem}.pl-4{padding-left:1rem}.pt-10{padding-top:2.5rem}.pt-2{padding-top:0.5rem}.pt-4{padding-top:1rem}.text-left{text-align:left}.text-center{text-align:center}.text-right{text-align:right}.font-mono{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace}.text-2xl{font-size:1.5rem;line-height:2rem}.text-3xl{font-size:1.875rem;line-height:2.25rem}.text-4xl{font-size:2.25rem;line-height:2.5rem}.text-\[10px\]{font-size:10px}.text-\[11px\]{font-size:11px}.text-base{font-size:1rem;line-height:1.5rem}.text-lg{font-size:1.125rem;line-height:1.75rem}.text-sm{font-size:0.875rem;line-height:1.25rem}.text-xl{font-size:1.25rem;line-height:1.75rem}.text-xs{font-size:0.75rem;line-height:1rem}.font-black{font-weight:900}.font-bold{font-weight:700}.font-extrabold{font-weight:800}.font-medium{font-weight:500}.font-semibold{font-weight:600}.uppercase{text-transform:uppercase}.italic{font-style:italic}.leading-none{line-height:1}.leading-relaxed{line-height:1.625}.leading-tight{line-height:1.25}.tracking-tight{letter-spacing:-0.025em}.tracking-tighter{letter-spacing:-0.05em}.tracking-wide{letter-spacing:0.025em}.tracking-wider{letter-spacing:0.05em}.tracking-widest{letter-spacing:0.1em}.text-amber-100{--tw-text-opacity:1;color:rgb(254 243 199 / var(--tw-text-opacity, 1))}.text-amber-200{--tw-text-opacity:1;color:rgb(253 230 138 / var(--tw-text-opacity, 1))}.text-amber-200\/80{color:rgb(253 230 138 / 0.8)}.text-amber-200\/90{color:rgb(253 230 138 / 0.9)}.text-amber-300{--tw-text-opacity:1;color:rgb(252 211 77 / var(--tw-text-opacity, 1))}.text-amber-300\/80{color:rgb(252 211 77 / 0.8)}.text-amber-300\/90{color:rgb(252 211 77 / 0.9)}.text-amber-400{--tw-text-opacity:1;color:rgb(251 191 36 / var(--tw-text-opacity, 1))}.text-amber-400\/40{color:rgb(251 191 36 / 0.4)}.text-amber-950{--tw-text-opacity:1;color:rgb(69 26 3 / var(--tw-text-opacity, 1))}.text-cyan-200{--tw-text-opacity:1;color:rgb(165 243 252 / var(--tw-text-opacity, 1))}.text-cyan-300{--tw-text-opacity:1;color:rgb(103 232 249 / var(--tw-text-opacity, 1))}.text-cyan-400{--tw-text-opacity:1;color:rgb(34 211 238 / var(--tw-text-opacity, 1))}.text-emerald-200{--tw-text-opacity:1;color:rgb(167 243 208 / var(--tw-text-opacity, 1))}.text-emerald-300{--tw-text-opacity:1;color:rgb(110 231 183 / var(--tw-text-opacity, 1))}.text-emerald-400{--tw-text-opacity:1;color:rgb(52 211 153 / var(--tw-text-opacity, 1))}.text-slate-200{--tw-text-opacity:1;color:rgb(226 232 240 / var(--tw-text-opacity, 1))}.text-slate-300{--tw-text-opacity:1;color:rgb(203 213 225 / var(--tw-text-opacity, 1))}.text-slate-400{--tw-text-opacity:1;color:rgb(148 163 184 / var(--tw-text-opacity, 1))}.text-slate-950{--tw-text-opacity:1;color:rgb(2 6 23 / var(--tw-text-opacity, 1))}.text-white{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.text-yellow-300{--tw-text-opacity:1;color:rgb(253 224 71 / var(--tw-text-opacity, 1))}.underline{-webkit-text-decoration-line:underline;text-decoration-line:underline}.opacity-0{opacity:0}.opacity-10{opacity:0.1}.opacity-70{opacity:0.7}.shadow{--tw-shadow:0 1px 3px 0 rgb(0 0 0 / 0.1), 0 1px 2px -1px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 1px 3px 0 var(--tw-shadow-color), 0 1px 2px -1px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-2xl{--tw-shadow:0 25px 50px -12px rgb(0 0 0 / 0.25);--tw-shadow-colored:0 25px 50px -12px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-lg{--tw-shadow:0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 10px 15px -3px var(--tw-shadow-color), 0 4px 6px -4px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-md{--tw-shadow:0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 4px 6px -1px var(--tw-shadow-color), 0 2px 4px -2px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-xl{--tw-shadow:0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 20px 25px -5px var(--tw-shadow-color), 0 8px 10px -6px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-amber-500\/10{--tw-shadow-color:rgb(245 158 11 / 0.1);--tw-shadow:var(--tw-shadow-colored)}.shadow-amber-500\/20{--tw-shadow-color:rgb(245 158 11 / 0.2);--tw-shadow:var(--tw-shadow-colored)}.shadow-amber-500\/25{--tw-shadow-color:rgb(245 158 11 / 0.25);--tw-shadow:var(--tw-shadow-colored)}.shadow-amber-500\/30{--tw-shadow-color:rgb(245 158 11 / 0.3);--tw-shadow:var(--tw-shadow-colored)}.blur-3xl{--tw-blur:blur(64px);filter:var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow)}.backdrop-blur-md{--tw-backdrop-blur:blur(12px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.transition-all{transition-property:all;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.transition-colors{transition-property:color, background-color, border-color, fill, stroke, -webkit-text-decoration-color;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, -webkit-text-decoration-color;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.transition-transform{transition-property:transform;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.duration-300{transition-duration:300ms}.selection\:bg-amber-500 *::selection{--tw-bg-opacity:1;background-color:rgb(245 158 11 / var(--tw-bg-opacity, 1))}.selection\:text-red-950 *::selection{--tw-text-opacity:1;color:rgb(69 10 10 / var(--tw-text-opacity, 1))}.selection\:bg-amber-500::selection{--tw-bg-opacity:1;background-color:rgb(245 158 11 / var(--tw-bg-opacity, 1))}.selection\:text-red-950::selection{--tw-text-opacity:1;color:rgb(69 10 10 / var(--tw-text-opacity, 1))}.placeholder\:text-amber-100\/40::placeholder{color:rgb(254 243 199 / 0.4)}.hover\:scale-105:hover{--tw-scale-x:1.05;--tw-scale-y:1.05;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.hover\:scale-\[1\.02\]:hover{--tw-scale-x:1.02;--tw-scale-y:1.02;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.hover\:scale-\[1\.03\]:hover{--tw-scale-x:1.03;--tw-scale-y:1.03;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.hover\:border-amber-300:hover{--tw-border-opacity:1;border-color:rgb(252 211 77 / var(--tw-border-opacity, 1))}.hover\:border-amber-400:hover{--tw-border-opacity:1;border-color:rgb(251 191 36 / var(--tw-border-opacity, 1))}.hover\:border-cyan-400:hover{--tw-border-opacity:1;border-color:rgb(34 211 238 / var(--tw-border-opacity, 1))}.hover\:border-emerald-400:hover{--tw-border-opacity:1;border-color:rgb(52 211 153 / var(--tw-border-opacity, 1))}.hover\:bg-amber-500:hover{--tw-bg-opacity:1;background-color:rgb(245 158 11 / var(--tw-bg-opacity, 1))}.hover\:bg-amber-500\/20:hover{background-color:rgb(245 158 11 / 0.2)}.hover\:bg-amber-600:hover{--tw-bg-opacity:1;background-color:rgb(217 119 6 / var(--tw-bg-opacity, 1))}.hover\:bg-amber-800:hover{--tw-bg-opacity:1;background-color:rgb(146 64 14 / var(--tw-bg-opacity, 1))}.hover\:bg-amber-900\/60:hover{background-color:rgb(120 53 15 / 0.6)}.hover\:bg-amber-950\/30:hover{background-color:rgb(69 26 3 / 0.3)}.hover\:bg-amber-950\/60:hover{background-color:rgb(69 26 3 / 0.6)}.hover\:bg-cyan-600:hover{--tw-bg-opacity:1;background-color:rgb(8 145 178 / var(--tw-bg-opacity, 1))}.hover\:bg-cyan-800:hover{--tw-bg-opacity:1;background-color:rgb(21 94 117 / var(--tw-bg-opacity, 1))}.hover\:bg-emerald-600:hover{--tw-bg-opacity:1;background-color:rgb(5 150 105 / var(--tw-bg-opacity, 1))}.hover\:bg-emerald-800:hover{--tw-bg-opacity:1;background-color:rgb(6 95 70 / var(--tw-bg-opacity, 1))}.hover\:from-amber-500:hover{--tw-gradient-from:#f59e0b var(--tw-gradient-from-position);--tw-gradient-to:rgb(245 158 11 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.hover\:from-cyan-500:hover{--tw-gradient-from:#06b6d4 var(--tw-gradient-from-position);--tw-gradient-to:rgb(6 182 212 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.hover\:from-emerald-500:hover{--tw-gradient-from:#10b981 var(--tw-gradient-from-position);--tw-gradient-to:rgb(16 185 129 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.hover\:to-amber-700:hover{--tw-gradient-to:#b45309 var(--tw-gradient-to-position)}.hover\:to-cyan-700:hover{--tw-gradient-to:#0e7490 var(--tw-gradient-to-position)}.hover\:to-emerald-700:hover{--tw-gradient-to:#047857 var(--tw-gradient-to-position)}.hover\:text-amber-200:hover{--tw-text-opacity:1;color:rgb(253 230 138 / var(--tw-text-opacity, 1))}.hover\:text-amber-400:hover{--tw-text-opacity:1;color:rgb(251 191 36 / var(--tw-text-opacity, 1))}.hover\:text-slate-950:hover{--tw-text-opacity:1;color:rgb(2 6 23 / var(--tw-text-opacity, 1))}.hover\:text-white:hover{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.hover\:underline:hover{-webkit-text-decoration-line:underline;text-decoration-line:underline}.focus\:border-amber-400:focus{--tw-border-opacity:1;border-color:rgb(251 191 36 / var(--tw-border-opacity, 1))}.focus\:outline-none:focus{outline:2px solid transparent;outline-offset:2px}.active\:scale-95:active{--tw-scale-x:.95;--tw-scale-y:.95;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.group:hover .group-hover\:rotate-12{--tw-rotate:12deg;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.group:hover .group-hover\:scale-110{--tw-scale-x:1.1;--tw-scale-y:1.1;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.group:hover .group-hover\:border-amber-300{--tw-border-opacity:1;border-color:rgb(252 211 77 / var(--tw-border-opacity, 1))}@media (min-width: 640px){.sm\:col-span-1{grid-column:span 1 / span 1}.sm\:inline-flex{display:inline-flex}.sm\:w-64{width:16rem}.sm\:w-auto{width:auto}.sm\:grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.sm\:grid-cols-4{grid-template-columns:repeat(4, minmax(0, 1fr))}.sm\:flex-row{flex-direction:row}.sm\:justify-start{justify-content:flex-start}.sm\:p-10{padding:2.5rem}.sm\:px-6{padding-left:1.5rem;padding-right:1.5rem}.sm\:text-left{text-align:left}.sm\:text-3xl{font-size:1.875rem;line-height:2.25rem}.sm\:text-4xl{font-size:2.25rem;line-height:2.5rem}.sm\:text-6xl{font-size:3.75rem;line-height:1}.sm\:text-sm{font-size:0.875rem;line-height:1.25rem}}@media (min-width: 768px){.md\:grid-cols-3{grid-template-columns:repeat(3, minmax(0, 1fr))}.md\:grid-cols-4{grid-template-columns:repeat(4, minmax(0, 1fr))}.md\:pb-24{padding-bottom:6rem}.md\:pt-16{padding-top:4rem}.md\:text-7xl{font-size:4.5rem;line-height:1}}@media (min-width: 1024px){.lg\:flex{display:flex}.lg\:hidden{display:none}.lg\:grid-cols-4{grid-template-columns:repeat(4, minmax(0, 1fr))}.lg\:grid-cols-7{grid-template-columns:repeat(7, minmax(0, 1fr))}.lg\:flex-row{flex-direction:row}.lg\:justify-start{justify-content:flex-start}.lg\:gap-8{gap:2rem}.lg\:px-8{padding-left:2rem;padding-right:2rem}.lg\:text-left{text-align:left}}</style></head>
<body class="relative min-h-screen jali-pattern selection:bg-amber-500 selection:text-red-950">

    <!-- Floating Golden Spark & Ember Particles Canvas -->
    <canvas id="emberCanvas" class="fixed inset-0 pointer-events-none z-0 opacity-70" width="1024" height="641"></canvas>

    <!-- Traditional Decorative Watermark Mandalas -->
    <div class="fixed -top-52 -left-52 pointer-events-none z-0 opacity-10">
        <svg class="w-[700px] h-[700px] text-amber-400 spin-slow" viewBox="0 0 100 100" fill="currentColor">
            <path d="M50 0 L55 35 L90 10 L65 45 L100 50 L65 55 L90 90 L55 65 L50 100 L45 65 L10 90 L35 55 L0 50 L35 45 L10 10 L45 35 Z"></path>
            <circle cx="50" cy="50" r="30" fill="none" stroke="currentColor" stroke-width="2"></circle>
            <circle cx="50" cy="50" r="20" fill="none" stroke="currentColor" stroke-width="1" stroke-dasharray="2 2"></circle>
        </svg>
    </div>
    <div class="fixed -bottom-52 -right-52 pointer-events-none z-0 opacity-10">
        <svg class="w-[700px] h-[700px] text-amber-400 spin-slow-reverse" viewBox="0 0 100 100" fill="currentColor">
            <path d="M50 0 L55 35 L90 10 L65 45 L100 50 L65 55 L90 90 L55 65 L50 100 L45 65 L10 90 L35 55 L0 50 L35 45 L10 10 L45 35 Z"></path>
            <circle cx="50" cy="50" r="35" fill="none" stroke="currentColor" stroke-width="1.5"></circle>
        </svg>
    </div>

    <!-- Navigation Header -->
    <header class="sticky top-0 z-50 bg-[#0F0103]/90 backdrop-blur-md border-b border-amber-500/30 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            
            <!-- Brand Logo & Devanagari Shloka -->
            <a href="https://vn9th.github.io/VidyaNirman9th/#home" class="flex items-center gap-3.5 group">
                <div class="relative flex items-center justify-center">
                    <div class="w-12 h-12 rounded-full border-2 border-amber-400/80 flex items-center justify-center bg-[#220308] shadow-lg shadow-amber-500/20 group-hover:border-amber-300 transition-colors overflow-hidden">
                        <img src="./Vidya Nirman _ विद्या निर्माण - Class 9th Interactive Portal_files/logo.png" alt="Vidya Nirman Logo" class="w-full h-full object-cover">
                    </div>
                    <svg class="absolute inset-0 w-12 h-12 text-amber-400/40 spin-slow pointer-events-none" viewBox="0 0 100 100">
                        <circle cx="50" cy="50" r="48" fill="none" stroke="currentColor" stroke-width="2" stroke-dasharray="6 4"></circle>
                    </svg>
                </div>
                <div>
                    <h1 class="font-cinzel text-2xl font-black tracking-wider text-gold-gradient leading-none">VIDYA NIRMAN</h1>
                    <span class="font-devanagari text-xs text-amber-300/90 tracking-widest block mt-1 font-semibold">सा विद्या या विमुक्तये</span>
                </div>
            </a>

            <!-- Desktop Menu Links -->
            <nav class="hidden lg:flex items-center space-x-6 text-xs font-bold uppercase tracking-wider">
                <a href="https://vn9th.github.io/VidyaNirman9th/#home" class="text-amber-100 hover:text-amber-400 transition-colors flex items-center gap-1.5"><i class="fa-solid fa-house text-amber-400"></i> Home</a>
                <a href="https://vn9th.github.io/VidyaNirman9th/#portals" class="text-amber-100 hover:text-amber-400 transition-colors flex items-center gap-1.5"><i class="fa-solid fa-book-open text-amber-400"></i> Learning Portals</a>
                <a href="https://vn9th.github.io/VidyaNirman9th/#quests" class="text-amber-100 hover:text-amber-400 transition-colors flex items-center gap-1.5"><i class="fa-solid fa-trophy text-amber-400"></i> Quest Arenas</a>
                <a href="https://vn9th.github.io/VidyaNirman9th/#directory" class="text-amber-100 hover:text-amber-400 transition-colors flex items-center gap-1.5"><i class="fa-solid fa-list-check text-amber-400"></i> Direct Links</a>
                <a href="https://vn9th.github.io/VidyaNirman9th/#founders" class="text-amber-100 hover:text-amber-400 transition-colors flex items-center gap-1.5"><i class="fa-solid fa-users text-amber-400"></i> Founders</a>
                <a href="https://vn9th.github.io/VidyaNirman9th/#notices" class="text-amber-100 hover:text-amber-400 transition-colors flex items-center gap-1.5"><i class="fa-solid fa-bullhorn text-amber-400"></i> Notices</a>
            </nav>

            <!-- Grand Quest Action Button -->
            <div class="flex items-center gap-3">
                <a href="https://vn9th.github.io/VidyaNirman9th/grand-quest.html" class="hidden sm:inline-flex items-center gap-2 px-4 py-2 rounded-full bg-gradient-to-r from-amber-500 via-yellow-400 to-amber-600 text-slate-950 font-black text-xs uppercase tracking-wider shadow-lg shadow-amber-500/25 hover:scale-105 transition-all">
                    <i class="fa-solid fa-crown text-amber-950"></i>
                    <span>Grand Quest</span>
                </a>

                <button id="mobileMenuBtn" class="lg:hidden text-amber-400 p-2.5 rounded-lg bg-amber-500/10 hover:bg-amber-500/20 border border-amber-500/30">
                    <i class="fa-solid fa-bars text-xl"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Navigation Drawer -->
        <div id="mobileMenu" class="hidden lg:hidden bg-[#180206] border-b border-amber-500/30 px-6 py-4 space-y-3">
            <a href="https://vn9th.github.io/VidyaNirman9th/#home" class="mobile-link block text-amber-100 hover:text-amber-400 py-1 font-semibold"><i class="fa-solid fa-house mr-2 text-amber-400"></i> Home</a>
            <a href="https://vn9th.github.io/VidyaNirman9th/#portals" class="mobile-link block text-amber-100 hover:text-amber-400 py-1 font-semibold"><i class="fa-solid fa-book-open mr-2 text-amber-400"></i> Learning Portals</a>
            <a href="https://vn9th.github.io/VidyaNirman9th/#quests" class="mobile-link block text-amber-100 hover:text-amber-400 py-1 font-semibold"><i class="fa-solid fa-trophy mr-2 text-amber-400"></i> Quest Arenas</a>
            <a href="https://vn9th.github.io/VidyaNirman9th/grand-quest.html" class="mobile-link block text-amber-300 font-bold py-1"><i class="fa-solid fa-crown mr-2 text-amber-400"></i> GRAND-QUEST Championship</a>
            <a href="https://vn9th.github.io/VidyaNirman9th/#directory" class="mobile-link block text-amber-100 hover:text-amber-400 py-1 font-semibold"><i class="fa-solid fa-list-check mr-2 text-amber-400"></i> Portal Directory</a>
            <a href="https://vn9th.github.io/VidyaNirman9th/#founders" class="mobile-link block text-amber-100 hover:text-amber-400 py-1 font-semibold"><i class="fa-solid fa-users mr-2 text-amber-400"></i> Leadership &amp; Founders</a>
            <a href="https://vn9th.github.io/VidyaNirman9th/#notices" class="mobile-link block text-amber-100 hover:text-amber-400 py-1 font-semibold"><i class="fa-solid fa-bullhorn mr-2 text-amber-400"></i> Notice Board</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="relative pt-10 pb-16 md:pt-16 md:pb-24 overflow-hidden z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center relative">
            
            <!-- Traditional Shloka Banner Crest -->
            <div class="inline-flex items-center gap-3 px-6 py-2.5 rounded-full bg-gradient-to-r from-amber-500/10 via-amber-400/20 to-amber-500/10 border border-amber-400/40 text-amber-200 text-xs sm:text-sm font-semibold mb-6 animate-float shadow-lg shadow-amber-500/10">
                <i class="fa-solid fa-om text-amber-400 text-base"></i>
                <span class="font-devanagari tracking-wide font-bold">"विद्यां ददाति विनयं, विनयाद् याति पात्रताम्"</span>
                <i class="fa-solid fa-dharmachakra text-amber-400 text-base"></i>
            </div>

            <h1 class="font-cinzel text-4xl sm:text-6xl md:text-7xl font-black text-gold-gradient tracking-tight leading-none mb-3">
                VIDYA NIRMAN
            </h1>

            <p class="font-devanagari text-xl sm:text-3xl text-amber-200/90 max-w-3xl mx-auto mb-6 font-bold">
                विद्या निर्माण — Class 9th Interactive Learning Ecosystem
            </p>

            <p class="text-slate-300 text-xs sm:text-sm max-w-2xl mx-auto mb-10 leading-relaxed font-medium">
                Welcome to the digital Gurukul designed specifically for Class 9th CBSE &amp; ICSE students. Explore dedicated subject learning portals and compete in interactive Quest Arenas engineered by founders <strong class="text-amber-300">Anmol Tiwari</strong> and <strong class="text-amber-300">Amrit Singh</strong>.
            </p>

            <!-- Quick Access Gateway Ribbon -->
            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-7 gap-2.5 max-w-6xl mx-auto mb-12">
                
                <a href="https://vn9th.github.io/VidyaNirman9th/vidyanirman-bio.html" class="p-3 rounded-xl bg-maroon-card border-gold-glow hover:bg-amber-950/60 transition-all text-center group">
                    <i class="fa-solid fa-dna text-emerald-400 text-lg mb-1 group-hover:scale-110 transition-transform block"></i>
                    <span class="text-[10px] font-bold text-amber-200 block uppercase">VN Bio</span>
                </a>

                <a href="https://vn9th.github.io/VidyaNirman9th/physics.html" class="p-3 rounded-xl bg-maroon-card border-gold-glow hover:bg-amber-950/60 transition-all text-center group">
                    <i class="fa-solid fa-atom text-cyan-400 text-lg mb-1 group-hover:scale-110 transition-transform block"></i>
                    <span class="text-[10px] font-bold text-amber-200 block uppercase">VN Physics</span>
                </a>

                <a href="https://vn9th.github.io/VidyaNirman9th/vidyanirman-chemistry.html" class="p-3 rounded-xl bg-maroon-card border-gold-glow hover:bg-amber-950/60 transition-all text-center group">
                    <i class="fa-solid fa-flask text-amber-400 text-lg mb-1 group-hover:scale-110 transition-transform block"></i>
                    <span class="text-[10px] font-bold text-amber-200 block uppercase">VN Chem</span>
                </a>

                <a href="https://vn9th.github.io/VidyaNirman9th/bio-quest.html" class="p-3 rounded-xl bg-maroon-card border-gold-glow hover:bg-amber-950/60 transition-all text-center group">
                    <i class="fa-solid fa-vial text-emerald-300 text-lg mb-1 group-hover:scale-110 transition-transform block"></i>
                    <span class="text-[10px] font-bold text-amber-200 block uppercase">Bio Quest</span>
                </a>

                <a href="https://vn9th.github.io/VidyaNirman9th/physics-quest.html" class="p-3 rounded-xl bg-maroon-card border-gold-glow hover:bg-amber-950/60 transition-all text-center group">
                    <i class="fa-solid fa-bolt text-cyan-300 text-lg mb-1 group-hover:scale-110 transition-transform block"></i>
                    <span class="text-[10px] font-bold text-amber-200 block uppercase">Phys Quest</span>
                </a>

                <a href="https://vn9th.github.io/VidyaNirman9th/chemistry-quest.html" class="p-3 rounded-xl bg-maroon-card border-gold-glow hover:bg-amber-950/60 transition-all text-center group">
                    <i class="fa-solid fa-fire-burner text-amber-300 text-lg mb-1 group-hover:scale-110 transition-transform block"></i>
                    <span class="text-[10px] font-bold text-amber-200 block uppercase">Chem Quest</span>
                </a>

                <a href="https://vn9th.github.io/VidyaNirman9th/grand-quest.html" class="p-3 rounded-xl bg-gradient-to-b from-amber-500/30 to-amber-700/30 border border-amber-400 hover:scale-105 transition-all text-center group col-span-2 sm:col-span-1">
                    <i class="fa-solid fa-trophy text-yellow-300 text-lg mb-1 group-hover:scale-110 transition-transform block animate-bounce"></i>
                    <span class="text-[10px] font-black text-amber-300 block uppercase tracking-tighter">Grand Quest</span>
                </a>

            </div>

        </div>
    </section>

    <!-- Notice Board Marquee -->
    <section id="notices" class="py-3 bg-[#220308] border-y border-amber-500/30 relative z-10 overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 flex items-center gap-3">
            <div class="flex items-center gap-2 bg-amber-500 text-slate-950 font-black px-3.5 py-1.5 rounded-lg text-[11px] uppercase tracking-wider shrink-0 shadow-md">
                <i class="fa-solid fa-bullhorn animate-bounce"></i> Live Updates
            </div>
            
            <div class="overflow-hidden w-full relative">
                <div class="animate-marquee font-semibold text-xs text-amber-200 space-x-12">
                    <span class="inline-flex items-center gap-2">🏆 <strong class="text-amber-400">GRAND-QUEST Championship:</strong> Registrations live for Class 9th All-Subject Championship Quiz! (<a href="https://vn9th.github.io/VidyaNirman9th/grand-quest.html" class="underline text-yellow-300">Enter Arena</a>)</span>
                    <span class="inline-flex items-center gap-2">🧬 <strong class="text-amber-400">VIDYANIRMAN BIO:</strong> Cell Organelles 3D Visualizer &amp; Tissues module updated (<a href="https://vn9th.github.io/VidyaNirman9th/vidyanirman-bio.html" class="underline text-yellow-300">Open Bio Portal</a>)</span>
                    <span class="inline-flex items-center gap-2">⚛️ <strong class="text-amber-400">VIDYANIRMAN PHYSICS:</strong> Newton's Motion Laws &amp; Gravitation numericals uploaded (<a href="https://vn9th.github.io/VidyaNirman9th/physics.html" class="underline text-yellow-300">Open Physics Portal</a>)</span>
                    <span class="inline-flex items-center gap-2">🧪 <strong class="text-amber-400">VIDYANIRMAN CHEMISTRY:</strong> Mole Concept &amp; Bohr Model interactive notes live (<a href="https://vn9th.github.io/VidyaNirman9th/vidyanirman-chemistry.html" class="underline text-yellow-300">Open Chem Portal</a>)</span>
                </div>
            </div>
        </div>
    </section>

    <!-- GRAND QUEST Spotlight Hero Banner -->
    <section class="py-12 relative z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-gradient-to-r from-[#3B0810] via-[#2A050C] to-[#1A0005] rounded-3xl p-8 sm:p-10 border-2 border-amber-400/80 shadow-2xl relative overflow-hidden group">
                
                <div class="absolute -top-24 -right-24 w-72 h-72 bg-amber-500/10 rounded-full blur-3xl pointer-events-none"></div>

                <div class="flex flex-col lg:flex-row items-center justify-between gap-8 relative z-10">
                    <div class="space-y-4 text-center lg:text-left max-w-2xl">
                        <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-amber-500/20 border border-amber-400/50 text-amber-300 text-xs font-bold uppercase">
                            <i class="fa-solid fa-crown text-amber-400"></i> The Ultimate Arena
                        </div>
                        <h2 class="font-cinzel text-3xl sm:text-4xl font-black text-gold-gradient leading-tight">
                            GRAND-QUEST CHAMPIONSHIP
                        </h2>
                        <p class="text-slate-300 text-xs sm:text-sm leading-relaxed">
                            Test your complete Class 9th mastery across Biology, Physics, and Chemistry in one comprehensive timer-driven tournament arena. Win certificates, top the state leaderboard, and prove your academic excellence.
                        </p>
                        <div class="flex flex-wrap items-center justify-center lg:justify-start gap-4 pt-2">
                            <span class="text-xs text-amber-200/90 bg-amber-950/80 px-3 py-1.5 rounded-lg border border-amber-500/30">
                                <i class="fa-solid fa-layer-group text-amber-400 mr-1"></i> Covers Bio, Phys &amp; Chem
                            </span>
                            <span class="text-xs text-amber-200/90 bg-amber-950/80 px-3 py-1.5 rounded-lg border border-amber-500/30">
                                <i class="fa-solid fa-stopwatch text-amber-400 mr-1"></i> Timed Adaptive Battle
                            </span>
                        </div>
                    </div>

                    <div class="flex flex-col sm:flex-row items-center gap-4 shrink-0">
                        <a href="https://vn9th.github.io/VidyaNirman9th/grand-quest.html" class="w-full sm:w-auto px-8 py-4 rounded-2xl bg-gold-gradient text-slate-950 font-black text-sm uppercase tracking-wider shadow-xl shadow-amber-500/30 hover:scale-105 active:scale-95 transition-all flex items-center justify-center gap-2">
                            <span>Enter Grand-Quest</span>
                            <i class="fa-solid fa-arrow-right"></i>
                        </a>
                        <button onclick="openPortalModal('GRAND-QUEST Championship', 'grand-quest.html', 'All-Subject Championship Quiz covering Biology, Physics, and Chemistry for Class 9th.')" class="w-full sm:w-auto px-6 py-4 rounded-2xl bg-amber-950/80 text-amber-200 border border-amber-500/40 hover:border-amber-300 text-xs font-bold transition-all">
                            <i class="fa-solid fa-magnifying-glass mr-1"></i> Inspect Link
                        </button>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Learning Portals Section (VIDYANIRMAN BIO, PHYSICS, CHEMISTRY) -->
    <section id="portals" class="py-16 relative z-10 bg-gradient-to-b from-[#0F0103] via-[#220308] to-[#0F0103] border-t border-amber-500/20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center mb-14">
                <span class="text-amber-400 text-xs font-black uppercase tracking-widest bg-amber-500/10 px-3 py-1 rounded-full border border-amber-500/30">Interactive Syllabi</span>
                <h2 class="font-cinzel text-3xl sm:text-4xl font-black text-gold-gradient mt-2">Vidya Nirman Learning Portals</h2>
                <div class="w-28 h-1 bg-gradient-to-r from-transparent via-amber-400 to-transparent mx-auto mt-3"></div>
                <p class="text-slate-400 text-xs sm:text-sm mt-3 max-w-xl mx-auto">Structured concept modules, 3D visualizers, formula sheets, and chapter summaries designed for Class 9th success.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                
                <!-- PORTAL 1: VIDYANIRMAN BIO -->
                <div class="bg-maroon-card p-8 rounded-2xl border-gold-glow flex flex-col justify-between tilt-card group">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="bg-emerald-500/20 text-emerald-300 text-[10px] font-extrabold px-3 py-1 rounded-md border border-emerald-500/30 uppercase tracking-wide">CLASS 9 BIOLOGY</span>
                            <i class="fa-solid fa-dna text-emerald-400 text-2xl group-hover:rotate-12 transition-transform"></i>
                        </div>
                        <h3 class="font-cinzel text-xl font-bold text-amber-100 mb-2">VIDYANIRMAN BIO</h3>
                        <p class="text-slate-300 text-xs leading-relaxed mb-6">
                            Deep dive into Class 9th Life Sciences: Cell Structure &amp; Functions, Plant and Animal Tissues, Improvement in Food Resources, and Biodiversity.
                        </p>

                        <ul class="space-y-2.5 mb-8 text-xs text-slate-300">
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-400 text-[10px]"></i> Interactive Organelle Diagrams</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-400 text-[10px]"></i> Tissue Classification Maps</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-400 text-[10px]"></i> NCERT Practice Revision Guides</li>
                        </ul>
                    </div>

                    <div class="space-y-2 border-t border-amber-500/20 pt-4">
                        <a href="https://vn9th.github.io/VidyaNirman9th/vidyanirman-bio.html" class="w-full py-3 px-4 rounded-xl bg-gradient-to-r from-emerald-600 to-emerald-800 hover:from-emerald-500 hover:to-emerald-700 text-white font-bold text-xs uppercase tracking-wider transition-all flex items-center justify-center gap-2 shadow-lg">
                            <span>Open Vidyanirman Bio</span>
                            <i class="fa-solid fa-arrow-right"></i>
                        </a>
                        <button onclick="openPortalModal('VIDYANIRMAN BIO', 'vidyanirman-bio.html', 'Class 9th Biology Learning Portal featuring Cell Organelles, Tissues, and Bio Concept Maps.')" class="w-full py-2 px-3 rounded-lg bg-amber-950/60 text-amber-300 text-[11px] font-semibold hover:bg-amber-900/60 transition-colors">
                            <i class="fa-solid fa-circle-info mr-1"></i> Preview Portal Details
                        </button>
                    </div>
                </div>

                <!-- PORTAL 2: VIDYANIRMAN PHYSICS -->
                <div class="bg-maroon-card p-8 rounded-2xl border-gold-glow flex flex-col justify-between tilt-card group">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="bg-cyan-500/20 text-cyan-300 text-[10px] font-extrabold px-3 py-1 rounded-md border border-cyan-500/30 uppercase tracking-wide">CLASS 9 PHYSICS</span>
                            <i class="fa-solid fa-atom text-cyan-400 text-2xl group-hover:spin-slow transition-transform"></i>
                        </div>
                        <h3 class="font-cinzel text-xl font-bold text-amber-100 mb-2">VIDYANIRMAN PHYSICS</h3>
                        <p class="text-slate-300 text-xs leading-relaxed mb-6">
                            Master Class 9th Physics: Distance &amp; Displacement, Motion Graphs, Newton's Laws of Motion, Universal Gravitation, Work, Power &amp; Sound Waves.
                        </p>

                        <ul class="space-y-2.5 mb-8 text-xs text-slate-300">
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-cyan-400 text-[10px]"></i> Numerical Problem Solver Guides</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-cyan-400 text-[10px]"></i> Kinematic Graph Visualizers</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-cyan-400 text-[10px]"></i> Gravitation Formula Sheets</li>
                        </ul>
                    </div>

                    <div class="space-y-2 border-t border-amber-500/20 pt-4">
                        <a href="https://vn9th.github.io/VidyaNirman9th/physics.html" class="w-full py-3 px-4 rounded-xl bg-gradient-to-r from-cyan-600 to-cyan-800 hover:from-cyan-500 hover:to-cyan-700 text-white font-bold text-xs uppercase tracking-wider transition-all flex items-center justify-center gap-2 shadow-lg">
                            <span>Open Vidyanirman Physics</span>
                            <i class="fa-solid fa-arrow-right"></i>
                        </a>
                        <button onclick="openPortalModal('VIDYANIRMAN PHYSICS', 'vidyanirman-physics.html', 'Class 9th Physics Learning Portal with Kinematics, Dynamics, and Gravitation modules.')" class="w-full py-2 px-3 rounded-lg bg-amber-950/60 text-amber-300 text-[11px] font-semibold hover:bg-amber-900/60 transition-colors">
                            <i class="fa-solid fa-circle-info mr-1"></i> Preview Portal Details
                        </button>
                    </div>
                </div>

                <!-- PORTAL 3: VIDYANIRMAN CHEMISTRY -->
                <div class="bg-maroon-card p-8 rounded-2xl border-gold-glow flex flex-col justify-between tilt-card group">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="bg-amber-500/20 text-amber-300 text-[10px] font-extrabold px-3 py-1 rounded-md border border-amber-500/30 uppercase tracking-wide">CLASS 9 CHEMISTRY</span>
                            <i class="fa-solid fa-flask text-amber-400 text-2xl group-hover:scale-110 transition-transform"></i>
                        </div>
                        <h3 class="font-cinzel text-xl font-bold text-amber-100 mb-2">VIDYANIRMAN CHEMISTRY</h3>
                        <p class="text-slate-300 text-xs leading-relaxed mb-6">
                            Unlock Matter in Our Surroundings, Is Matter Around Us Pure, Atoms &amp; Molecules, Mole Concept Calculations, and Bohr Atomic Models.
                        </p>

                        <ul class="space-y-2.5 mb-8 text-xs text-slate-300">
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-amber-400 text-[10px]"></i> Interactive Periodic Table Directory</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-amber-400 text-[10px]"></i> Mole Concept Step-by-Step Solvers</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-amber-400 text-[10px]"></i> Atomic Structure Orbit Models</li>
                        </ul>
                    </div>

                    <div class="space-y-2 border-t border-amber-500/20 pt-4">
                        <a href="https://vn9th.github.io/VidyaNirman9th/vidyanirman-chemistry.html" class="w-full py-3 px-4 rounded-xl bg-gradient-to-r from-amber-600 to-amber-800 hover:from-amber-500 hover:to-amber-700 text-white font-bold text-xs uppercase tracking-wider transition-all flex items-center justify-center gap-2 shadow-lg">
                            <span>Open Vidyanirman Chem</span>
                            <i class="fa-solid fa-arrow-right"></i>
                        </a>
                        <button onclick="openPortalModal('VIDYANIRMAN CHEMISTRY', 'vidyanirman-chemistry.html', 'Class 9th Chemistry Learning Portal covering Atoms, Molecules, and Mole Concept.')" class="w-full py-2 px-3 rounded-lg bg-amber-950/60 text-amber-300 text-[11px] font-semibold hover:bg-amber-900/60 transition-colors">
                            <i class="fa-solid fa-circle-info mr-1"></i> Preview Portal Details
                        </button>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Quest Arenas Section (BIO-QUEST, PHYSICS-QUEST, CHEMISTRY-QUEST, GRAND-QUEST) -->
    <section id="quests" class="py-16 relative z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center mb-12">
                <span class="text-amber-400 text-xs font-black uppercase tracking-widest bg-amber-500/10 px-3 py-1 rounded-full border border-amber-500/30">Gamified Testing</span>
                <h2 class="font-cinzel text-3xl sm:text-4xl font-black text-gold-gradient mt-2">Class 9th Quest Arenas</h2>
                <p class="text-slate-400 text-xs sm:text-sm mt-2 max-w-lg mx-auto">Challenge yourself with timed quizzes, chapter battles, and national student ranking competitions.</p>
            </div>

            <!-- Quest Grid -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                
                <!-- BIO-QUEST -->
                <div class="bg-maroon-card p-6 rounded-2xl border-gold-glow flex flex-col justify-between group hover:border-emerald-400 transition-all">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-emerald-500/20 text-emerald-400 flex items-center justify-center text-xl mb-4 group-hover:scale-110 transition-transform">
                            <i class="fa-solid fa-vial"></i>
                        </div>
                        <span class="text-[10px] font-bold text-emerald-400 uppercase tracking-widest block mb-1">BIOLOGY ARENA</span>
                        <h3 class="font-cinzel text-lg font-bold text-amber-100 mb-2">BIO-QUEST</h3>
                        <p class="text-slate-300 text-xs leading-relaxed mb-6">
                            Timed multiple-choice challenges testing Cell Biology, Tissues, and Plant Anatomy.
                        </p>
                    </div>
                    <a href="https://vn9th.github.io/VidyaNirman9th/bio-quest.html" class="w-full py-2.5 rounded-xl bg-emerald-950 border border-emerald-500/40 text-emerald-300 font-bold text-xs text-center hover:bg-emerald-800 hover:text-white transition-all block">
                        Start Bio-Quest <i class="fa-solid fa-gamepad ml-1"></i>
                    </a>
                </div>

                <!-- PHYSICS-QUEST -->
                <div class="bg-maroon-card p-6 rounded-2xl border-gold-glow flex flex-col justify-between group hover:border-cyan-400 transition-all">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-cyan-500/20 text-cyan-400 flex items-center justify-center text-xl mb-4 group-hover:scale-110 transition-transform">
                            <i class="fa-solid fa-bolt"></i>
                        </div>
                        <span class="text-[10px] font-bold text-cyan-400 uppercase tracking-widest block mb-1">PHYSICS ARENA</span>
                        <h3 class="font-cinzel text-lg font-bold text-amber-100 mb-2">PHYSICS-QUEST</h3>
                        <p class="text-slate-300 text-xs leading-relaxed mb-6">
                            Rapid-fire numerical puzzles on Kinematics, Gravitation, and Work &amp; Energy.
                        </p>
                    </div>
                    <a href="https://vn9th.github.io/VidyaNirman9th/physics-quest.html" class="w-full py-2.5 rounded-xl bg-cyan-950 border border-cyan-500/40 text-cyan-300 font-bold text-xs text-center hover:bg-cyan-800 hover:text-white transition-all block">
                        Start Physics-Quest <i class="fa-solid fa-gamepad ml-1"></i>
                    </a>
                </div>

                <!-- CHEMISTRY-QUEST -->
                <div class="bg-maroon-card p-6 rounded-2xl border-gold-glow flex flex-col justify-between group hover:border-amber-400 transition-all">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-amber-500/20 text-amber-400 flex items-center justify-center text-xl mb-4 group-hover:scale-110 transition-transform">
                            <i class="fa-solid fa-fire-burner"></i>
                        </div>
                        <span class="text-[10px] font-bold text-amber-400 uppercase tracking-widest block mb-1">CHEMISTRY ARENA</span>
                        <h3 class="font-cinzel text-lg font-bold text-amber-100 mb-2">CHEMISTRY-QUEST</h3>
                        <p class="text-slate-300 text-xs leading-relaxed mb-6">
                            Mole calculations, atomic formula balance tests, and element identification games.
                        </p>
                    </div>
                    <a href="https://vn9th.github.io/VidyaNirman9th/chemistry-quest.html" class="w-full py-2.5 rounded-xl bg-amber-950 border border-amber-500/40 text-amber-300 font-bold text-xs text-center hover:bg-amber-800 hover:text-white transition-all block">
                        Start Chemistry-Quest <i class="fa-solid fa-gamepad ml-1"></i>
                    </a>
                </div>

                <!-- GRAND-QUEST -->
                <div class="bg-gradient-to-b from-[#3B0810] to-[#1F0207] p-6 rounded-2xl border-2 border-amber-400 flex flex-col justify-between group hover:scale-[1.03] transition-all shadow-xl shadow-amber-500/20">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-amber-500/30 text-amber-300 flex items-center justify-center text-xl mb-4 group-hover:scale-110 transition-transform">
                            <i class="fa-solid fa-trophy animate-bounce"></i>
                        </div>
                        <span class="text-[10px] font-black text-amber-300 uppercase tracking-widest block mb-1">MEGA CHAMPIONSHIP</span>
                        <h3 class="font-cinzel text-lg font-black text-gold-gradient mb-2">GRAND-QUEST</h3>
                        <p class="text-slate-200 text-xs leading-relaxed mb-6">
                            The ultimate test combining Bio, Physics &amp; Chem into one adaptive exam battle.
                        </p>
                    </div>
                    <a href="https://vn9th.github.io/VidyaNirman9th/grand-quest.html" class="w-full py-2.5 rounded-xl bg-gold-gradient text-slate-950 font-black text-xs text-center hover:scale-105 transition-all block shadow-md">
                        Enter Championship <i class="fa-solid fa-crown ml-1"></i>
                    </a>
                </div>

            </div>
        </div>
    </section>

    <!-- Connected Pages Direct Directory Section -->
    <section id="directory" class="py-16 relative z-10 bg-gradient-to-b from-[#0F0103] via-[#220308] to-[#0F0103] border-y border-amber-500/20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center mb-12">
                <span class="text-amber-400 text-xs font-black uppercase tracking-widest bg-amber-500/10 px-3 py-1 rounded-full border border-amber-500/30">Direct Gateway Map</span>
                <h2 class="font-cinzel text-3xl sm:text-4xl font-black text-gold-gradient mt-2">Vidya Nirman Connected Links Hub</h2>
                <p class="text-slate-400 text-xs sm:text-sm mt-2 max-w-xl mx-auto">Access direct `<a href="https://vn9th.github.io/VidyaNirman9th/...">` gateway destinations across all official Class 9 learning portals and quest arenas.</a></p><a href="https://vn9th.github.io/VidyaNirman9th/...">
            </a></div><a href="https://vn9th.github.io/VidyaNirman9th/...">

            <div class="bg-maroon-card rounded-2xl border-gold-glow overflow-hidden">
                <div class="p-6 border-b border-amber-500/20 flex flex-col sm:flex-row items-center justify-between gap-4">
                    <div class="text-xs text-amber-200 font-semibold">
                        <i class="fa-solid fa-link text-amber-400 mr-2"></i> Showing all 7 active connected sub-portals
                    </div>
                    <div class="relative w-full sm:w-64">
                        <input type="text" id="directorySearch" onkeyup="filterDirectory()" placeholder="Filter portal links..." class="w-full bg-[#0F0103] text-amber-100 text-xs px-3 py-2 rounded-lg border border-amber-500/30 focus:outline-none focus:border-amber-400 placeholder:text-amber-100/40">
                    </div>
                </div>

                <div class="overflow-x-auto">
                    <table class="w-full text-left text-xs text-slate-300">
                        <thead class="bg-[#180206] text-amber-300 font-cinzel font-bold text-[11px] uppercase tracking-wider border-b border-amber-500/20">
                            <tr>
                                <th class="py-3.5 px-6">Portal Name</th>
                                <th class="py-3.5 px-6">Category</th>
                                <th class="py-3.5 px-6">File Path (a href)</th>
                                <th class="py-3.5 px-6 text-right">Action Gateway</th>
                            </tr>
                        </thead>
                        <tbody id="directoryTable" class="divide-y divide-amber-500/10">
                            
                            <tr class="hover:bg-amber-950/30 transition-colors">
                                <td class="py-4 px-6 font-bold text-amber-100 flex items-center gap-2.5">
                                    <i class="fa-solid fa-dna text-emerald-400"></i> VIDYANIRMAN BIO
                                </td>
                                <td class="py-4 px-6"><span class="bg-emerald-500/20 text-emerald-300 px-2 py-0.5 rounded text-[10px] font-bold">LEARNING PORTAL</span></td>
                                <td class="py-4 px-6 font-mono text-amber-300/80">vidyanirman-bio.html</td>
                                <td class="py-4 px-6 text-right">
                                    <a href="https://vn9th.github.io/VidyaNirman9th/vidyanirman-bio.html" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-emerald-900/60 border border-emerald-500/40 text-emerald-200 font-bold hover:bg-emerald-600 hover:text-white transition-all text-[11px]">
                                        Launch <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                                    </a>
                                </td>
                            </tr>

                            <tr class="hover:bg-amber-950/30 transition-colors">
                                <td class="py-4 px-6 font-bold text-amber-100 flex items-center gap-2.5">
                                    <i class="fa-solid fa-atom text-cyan-400"></i> VIDYANIRMAN PHYSICS
                                </td>
                                <td class="py-4 px-6"><span class="bg-cyan-500/20 text-cyan-300 px-2 py-0.5 rounded text-[10px] font-bold">LEARNING PORTAL</span></td>
                                <td class="py-4 px-6 font-mono text-amber-300/80">vidyanirman-physics.html</td>
                                <td class="py-4 px-6 text-right">
                                    <a href="https://vn9th.github.io/VidyaNirman9th/physics.html" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-cyan-900/60 border border-cyan-500/40 text-cyan-200 font-bold hover:bg-cyan-600 hover:text-white transition-all text-[11px]">
                                        Launch <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                                    </a>
                                </td>
                            </tr>

                            <tr class="hover:bg-amber-950/30 transition-colors">
                                <td class="py-4 px-6 font-bold text-amber-100 flex items-center gap-2.5">
                                    <i class="fa-solid fa-flask text-amber-400"></i> VIDYANIRMAN CHEMISTRY
                                </td>
                                <td class="py-4 px-6"><span class="bg-amber-500/20 text-amber-300 px-2 py-0.5 rounded text-[10px] font-bold">LEARNING PORTAL</span></td>
                                <td class="py-4 px-6 font-mono text-amber-300/80">vidyanirman-chemistry.html</td>
                                <td class="py-4 px-6 text-right">
                                    <a href="https://vn9th.github.io/VidyaNirman9th/vidyanirman-chemistry.html" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-amber-900/60 border border-amber-500/40 text-amber-200 font-bold hover:bg-amber-600 hover:text-white transition-all text-[11px]">
                                        Launch <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                                    </a>
                                </td>
                            </tr>

                            <tr class="hover:bg-amber-950/30 transition-colors">
                                <td class="py-4 px-6 font-bold text-amber-100 flex items-center gap-2.5">
                                    <i class="fa-solid fa-vial text-emerald-400"></i> BIO-QUEST
                                </td>
                                <td class="py-4 px-6"><span class="bg-emerald-500/20 text-emerald-300 px-2 py-0.5 rounded text-[10px] font-bold">QUEST ARENA</span></td>
                                <td class="py-4 px-6 font-mono text-amber-300/80">bio-quest.html</td>
                                <td class="py-4 px-6 text-right">
                                    <a href="https://vn9th.github.io/VidyaNirman9th/bio-quest.html" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-emerald-900/60 border border-emerald-500/40 text-emerald-200 font-bold hover:bg-emerald-600 hover:text-white transition-all text-[11px]">
                                        Launch <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                                    </a>
                                </td>
                            </tr>

                            <tr class="hover:bg-amber-950/30 transition-colors">
                                <td class="py-4 px-6 font-bold text-amber-100 flex items-center gap-2.5">
                                    <i class="fa-solid fa-bolt text-cyan-400"></i> PHYSICS-QUEST
                                </td>
                                <td class="py-4 px-6"><span class="bg-cyan-500/20 text-cyan-300 px-2 py-0.5 rounded text-[10px] font-bold">QUEST ARENA</span></td>
                                <td class="py-4 px-6 font-mono text-amber-300/80">physics-quest.html</td>
                                <td class="py-4 px-6 text-right">
                                    <a href="https://vn9th.github.io/VidyaNirman9th/physics-quest.html" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-cyan-900/60 border border-cyan-500/40 text-cyan-200 font-bold hover:bg-cyan-600 hover:text-white transition-all text-[11px]">
                                        Launch <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                                    </a>
                                </td>
                            </tr>

                            <tr class="hover:bg-amber-950/30 transition-colors">
                                <td class="py-4 px-6 font-bold text-amber-100 flex items-center gap-2.5">
                                    <i class="fa-solid fa-fire-burner text-amber-400"></i> CHEMISTRY-QUEST
                                </td>
                                <td class="py-4 px-6"><span class="bg-amber-500/20 text-amber-300 px-2 py-0.5 rounded text-[10px] font-bold">QUEST ARENA</span></td>
                                <td class="py-4 px-6 font-mono text-amber-300/80">chemistry-quest.html</td>
                                <td class="py-4 px-6 text-right">
                                    <a href="https://vn9th.github.io/VidyaNirman9th/chemistry-quest.html" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-amber-900/60 border border-amber-500/40 text-amber-200 font-bold hover:bg-amber-600 hover:text-white transition-all text-[11px]">
                                        Launch <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                                    </a>
                                </td>
                            </tr>

                            <tr class="hover:bg-amber-950/30 transition-colors bg-amber-500/10">
                                <td class="py-4 px-6 font-bold text-amber-200 flex items-center gap-2.5">
                                    <i class="fa-solid fa-trophy text-yellow-300 animate-bounce"></i> GRAND-QUEST
                                </td>
                                <td class="py-4 px-6"><span class="bg-amber-400 text-slate-950 px-2.5 py-0.5 rounded text-[10px] font-black uppercase">MEGA CHAMPIONSHIP</span></td>
                                <td class="py-4 px-6 font-mono text-amber-300 font-bold">grand-quest.html</td>
                                <td class="py-4 px-6 text-right">
                                    <a href="https://vn9th.github.io/VidyaNirman9th/grand-quest.html" class="inline-flex items-center gap-1.5 px-3.5 py-1.5 rounded-lg bg-gold-gradient text-slate-950 font-black hover:scale-105 transition-all text-[11px] shadow-md">
                                        Launch <i class="fa-solid fa-crown text-[10px]"></i>
                                    </a>
                                </td>
                            </tr>

                        </tbody>
                    </table>
                </div>
            </div>

        </a></div><a href="https://vn9th.github.io/VidyaNirman9th/...">
    </a></section><a href="https://vn9th.github.io/VidyaNirman9th/...">

    <!-- Leadership & Founders Section -->
    </a><section id="founders" class="py-20 relative z-10"><a href="https://vn9th.github.io/VidyaNirman9th/...">
        </a><div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8"><a href="https://vn9th.github.io/VidyaNirman9th/...">
            <div class="text-center mb-16">
                <span class="text-amber-400 text-xs font-black uppercase tracking-widest bg-amber-500/10 px-3 py-1 rounded-full border border-amber-500/30">Visionaries &amp; Leaders</span>
                <h2 class="font-cinzel text-3xl sm:text-4xl font-extrabold text-gold-gradient mt-2">Founders of Vidya Nirman</h2>
                <div class="w-28 h-1 bg-gradient-to-r from-transparent via-amber-400 to-transparent mx-auto mt-3"></div>
            </div>

            </a><div class="grid grid-cols-1 md:grid-cols-3 gap-6 lg:gap-2 max-w-5+l mx-auto"><a href="https://vn9th.github.io/VidyaNirman9th/...">
                
    <!-- FOUNDER: AMRIT SINGH -->
<div class="bg-maroon-card p-6 rounded-2xl border-gold-glow relative overflow-hidden group transition-all w-full max-w-none">

    <div class="flex flex-col sm:flex-row items-start gap-4 mb-4">

        <div class="relative shrink-0">
            <div class="w-28 h-28 rounded-full border-2 border-amber-400 p-1 bg-[#0F0103] shadow-xl shadow-amber-500/20 overflow-hidden">
                <img
                    src="./Vidya Nirman _ विद्या निर्माण - Class 9th Interactive Portal_files/amrit-image.jpg"
                    alt="Amrit Singh"
                    class="w-full h-full object-cover rounded-full"
                >
            </div>

            <div class="absolute -bottom-1 -left-1 bg-amber-500 text-slate-950 p-2 rounded-full text-xs font-black shadow">
                <i class="fa-solid fa-star"></i>
            </div>
        </div>

        <div class="text-left min-w-0">
            <span class="bg-amber-500/20 text-amber-300 text-[11px] px-3 py-1 rounded-full font-bold border border-amber-500/30">
                FOUNDER
            </span>

            <h3 class="font-cinzel text-2xl font-extrabold text-amber-100 mt-2">
                AMRIT SINGH
            </h3>

            <p class="text-xs text-amber-300/90 font-medium">
                Academic Strategist &amp; Tech Innovator, Chief Visionary
            </p>

            <div class="flex items-center justify-start gap-3 mt-3">
                <a href="mailto:cofounder@vidyanirman.edu"
                   class="w-8 h-8 rounded-full bg-amber-500/10 border border-amber-500/30 flex items-center justify-center text-amber-400 hover:bg-amber-500 hover:text-slate-950 transition-all text-xs">
                    <i class="fa-solid fa-envelope"></i>
                </a>

                <a href="https://vn9th.github.io/VidyaNirman9th/#founders"
                   class="w-8 h-8 rounded-full bg-amber-500/10 border border-amber-500/30 flex items-center justify-center text-amber-400 hover:bg-amber-500 hover:text-slate-950 transition-all text-xs">
                    <i class="fa-brands fa-linkedin-in"></i>
                </a>
            </div>
        </div>
    </div>

    <p class="text-slate-300 text-xs leading-relaxed italic border-l-2 border-amber-400/60 pl-4 py-1">
        "Gamified Quest Arenas transform learning from passive textbook reading into an engaging journey of curiosity, problem solving, and confidence building."
    </p>
</div>

                <!-- CO-FOUNDER: ANMOL TIWARI -->
                </a><div class="bg-maroon-card p-8 rounded-2xl border-gold-glow relative overflow-hidden group hover:scale-[1.02] transition-all"><a href="https://vn9th.github.io/VidyaNirman9th/...">
                    </a><div class="flex flex-col sm:flex-row items-center gap-6 mb-6"><a href="https://vn9th.github.io/VidyaNirman9th/...">
                        <div class="relative">
                            <div class="w-28 h-28 rounded-full border-2 border-amber-400 p-1 bg-[#0F0103] shadow-xl shadow-amber-500/20 overflow-hidden">
                                <img src="Anmol.jpg" alt="Anmol Tiwari" class="w-full h-full object-cover rounded-full">
                            </div>
                            <div class="absolute -bottom-1 -right-1 bg-amber-500 text-slate-950 p-2 rounded-full text-xs font-black shadow">
                                <i class="fa-solid fa-crown"></i>
                            </div>
                        </div>

                        </a><div class="text-center sm:text-left"><a href="https://vn9th.github.io/VidyaNirman9th/...">
                            <span class="bg-amber-500/20 text-amber-300 text-[11px] px-3 py-1 rounded-full font-bold border border-amber-500/30">CO-FOUNDER</span>
                            <h3 class="font-cinzel text-2xl font-extrabold text-amber-100 mt-2">ANMOL TIWARI</h3>
                            <p class="text-xs text-amber-300/90 font-medium">Chief Visionary &amp; Curriculum Architect</p>
                            
                            </a><div class="flex items-center justify-center sm:justify-start gap-3 mt-3"><a href="https://vn9th.github.io/VidyaNirman9th/...">
                                </a><a href="mailto:founder@vidyanirman.edu" class="w-8 h-8 rounded-full bg-amber-500/10 border border-amber-500/30 flex items-center justify-center text-amber-400 hover:bg-amber-500 hover:text-slate-950 transition-all text-xs">
                                    <i class="fa-solid fa-envelope"></i>
                                </a>
                                <a href="https://vn9th.github.io/VidyaNirman9th/#founders" class="w-8 h-8 rounded-full bg-amber-500/10 border border-amber-500/30 flex items-center justify-center text-amber-400 hover:bg-amber-500 hover:text-slate-950 transition-all text-xs">
                                    <i class="fa-brands fa-linkedin-in"></i>
                                </a>
                            </div>
                        </div>
                    </div>

                    <p class="text-slate-300 text-xs leading-relaxed italic border-l-2 border-amber-400/60 pl-4 py-1">
                        "At Vidya Nirman, our vision is to combine the timeless focus of traditional Indian education with dynamic visual gateways, ensuring Class 9th students build an unshakeable foundation for their future."
                    </p>
                </div>
                    </p>
                </div>

            <!-- DESIGNER: ARYAMAN MISHRA -->
                </a><div class="bg-maroon-card p-8 rounded-2xl border-gold-glow relative overflow-hidden group hover:scale-[1.02] transition-all"><a href="https://vn9th.github.io/VidyaNirman9th/...">
                    </a><div class="flex flex-col sm:flex-row items-center gap-6 mb-6"><a href="https://vn9th.github.io/VidyaNirman9th/...">
                        <div class="relative">
                            <div class="w-28 h-28 rounded-full border-2 border-amber-400 p-1 bg-[#0F0103] shadow-xl shadow-amber-500/20 overflow-hidden">
                                <img src="" alt="Anmol Tiwari" class="w-full h-full object-cover rounded-full">
                            </div>
                            <div class="absolute -bottom-1 -right-1 bg-amber-500 text-slate-950 p-2 rounded-full text-xs font-black shadow">
                                <i class="fa-solid fa-crown"></i>
                            </div>
                        </div>

                        </a><div class="text-center sm:text-left"><a href="https://vn9th.github.io/VidyaNirman9th/...">
                            <span class="bg-amber-500/20 text-amber-300 text-[11px] px-3 py-1 rounded-full font-bold border border-amber-500/30">DESIGNER</span>
                            <h3 class="font-cinzel text-2xl font-extrabold text-amber-100 mt-2">ARYAMAN MISHRA</h3>
                            <p class="text-xs text-amber-300/90 font-medium">Design this platform &amp; Curriculum Designer</p>
                            
                            </a><div class="flex items-center justify-center sm:justify-start gap-3 mt-3"><a href="https://vn9th.github.io/VidyaNirman9th/...">
                                </a><a href="mailto:founder@vidyanirman.edu" class="w-8 h-8 rounded-full bg-amber-500/10 border border-amber-500/30 flex items-center justify-center text-amber-400 hover:bg-amber-500 hover:text-slate-950 transition-all text-xs">
                                    <i class="fa-solid fa-envelope"></i>
                                </a>
                                <a href="https://vn9th.github.io/VidyaNirman9th/#founders" class="w-8 h-8 rounded-full bg-amber-500/10 border border-amber-500/30 flex items-center justify-center text-amber-400 hover:bg-amber-500 hover:text-slate-950 transition-all text-xs">
                                    <i class="fa-brands fa-linkedin-in"></i>
                                </a>
                            </div>
                        </div>
                    </div>

                    <p class="text-slate-300 text-xs leading-relaxed italic border-l-2 border-amber-400/60 pl-4 py-1">
                        "Vidyanirman is a platform built with the vision of making education more accessible,creative,and technology-driver,As it Designer,I aim to create a user-friendly,attractive,and informative website that provides students."
                    </p>
                </div>
            
        
    </section>

    <!-- Footer Section -->
    <footer class="relative z-10 border-t border-amber-500/30 bg-[#0A0002] py-12 text-xs text-slate-400">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-10">
                
                <div class="space-y-3">
                    <div class="font-cinzel text-xl font-black text-gold-gradient tracking-wider">VIDYA NIRMAN</div>
                    <p class="font-devanagari text-amber-300 text-xs font-semibold">सा विद्या या विमुक्तये</p>
                    <p class="text-slate-400 text-xs leading-relaxed">
                        Class 9th Interactive Learning &amp; Quest Portal. Grounded in traditional excellence, powered by modern technology.
                    </p>
                </div>

                <div>
                    <h4 class="font-cinzel text-amber-200 font-bold mb-3 text-sm">Learning Portals</h4>
                    <ul class="space-y-2">
                        <li><a href="https://vn9th.github.io/VidyaNirman9th/vidyanirman-bio.html" class="hover:text-amber-400 transition-colors">VIDYANIRMAN BIO</a></li>
                        <li><a href="https://vn9th.github.io/VidyaNirman9th/physics.html" class="hover:text-amber-400 transition-colors">VIDYANIRMAN PHYSICS</a></li>
                        <li><a href="https://vn9th.github.io/VidyaNirman9th/vidyanirman-chemistry.html" class="hover:text-amber-400 transition-colors">VIDYANIRMAN CHEMISTRY</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="font-cinzel text-amber-200 font-bold mb-3 text-sm">Quest Arenas</h4>
                    <ul class="space-y-2">
                        <li><a href="https://vn9th.github.io/VidyaNirman9th/Bio%20quest.html" class="hover:text-amber-400 transition-colors">BIO-QUEST</a></li>
                        <li><a href="https://vn9th.github.io/VidyaNirman9th/physics-quest.html" class="hover:text-amber-400 transition-colors">PHYSICS-QUEST</a></li>
                        <li><a href="https://vn9th.github.io/VidyaNirman9th/chemistry-quest.html" class="hover:text-amber-400 transition-colors">CHEMISTRY-QUEST</a></li>
                        <li><a href="https://vn9th.github.io/VidyaNirman9th/grand-quest.html" class="text-amber-300 font-bold hover:underline">GRAND-QUEST Championship</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="font-cinzel text-amber-200 font-bold mb-3 text-sm">Leadership</h4>
                    <p class="text-slate-300 text-xs mb-1"><strong>Founder:</strong> ANMOL TIWARI</p>
                    <p class="text-slate-300 text-xs mb-3"><strong>Co-Founder:</strong> AMRIT SINGH</p>
                    <p class="text-[11px] text-amber-200/80"><i class="fa-solid fa-envelope text-amber-400 mr-1"></i> support@vidyanirman.edu</p>
                </div>

            </div>

            <div class="w-full h-px bg-gradient-to-r from-transparent via-amber-500/30 to-transparent my-6"></div>

            <div class="flex flex-col sm:flex-row items-center justify-between text-center sm:text-left gap-4">
                <p>© 2026 Vidya Nirman Interactive Learning Portal. All Rights Reserved.</p>
                <div class="flex gap-4">
                    <a href="https://vn9th.github.io/VidyaNirman9th/#home" class="hover:text-amber-400">Class 9th Curriculum</a>
                    <a href="https://vn9th.github.io/VidyaNirman9th/#founders" class="hover:text-amber-400">Founders Profile</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Portal Preview Modal -->
    <div id="portalModal" class="fixed inset-0 bg-slate-950/80 backdrop-blur-md z-50 flex items-center justify-center p-4 opacity-0 pointer-events-none transition-all duration-300">
        <div class="bg-[#1A0206] border-2 border-amber-400 rounded-2xl max-w-md w-full p-6 text-center relative shadow-2xl">
            <button onclick="closePortalModal()" class="absolute top-4 right-4 text-amber-400 hover:text-amber-200 text-lg">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div class="w-12 h-12 rounded-full bg-amber-500/20 border border-amber-400 flex items-center justify-center mx-auto mb-4 text-amber-400 text-xl">
                <i class="fa-solid fa-globe"></i>
            </div>
            <span class="text-[10px] font-bold uppercase tracking-widest text-amber-400 bg-amber-500/20 px-3 py-1 rounded-full border border-amber-500/30">GATEWAY PREVIEW</span>
            <h3 id="modalPortalTitle" class="font-cinzel text-xl font-bold text-amber-100 my-3">Portal Title</h3>
            <p id="modalPortalDesc" class="text-xs text-slate-300 leading-relaxed mb-4">Portal description...</p>
            <div class="p-3 bg-[#0F0103] rounded-lg border border-amber-500/20 font-mono text-xs text-amber-300 mb-6 flex items-center justify-between">
                <span>Target Link:</span>
                <strong id="modalTargetUrl" class="text-yellow-300">filename.html</strong>
            </div>
            <div class="flex justify-center gap-3">
                <button onclick="closePortalModal()" class="px-5 py-2.5 rounded-xl bg-amber-950/80 text-amber-200 border border-amber-500/40 text-xs font-bold hover:border-amber-400 transition-all">Close</button>
                <a id="modalLaunchBtn" href="https://vn9th.github.io/VidyaNirman9th/#" class="px-5 py-2.5 rounded-xl bg-gold-gradient text-slate-950 text-xs font-extrabold hover:scale-105 transition-all flex items-center gap-2">
                    Open Portal <i class="fa-solid fa-arrow-right"></i>
                </a>
            </div>
        </div>
    </div>

    <script>
        /* Floating Particle Canvas */
        const canvas = document.getElementById('emberCanvas');
        const ctx = canvas.getContext('2d');
        let particles = [];

        function resizeCanvas() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        }
        window.addEventListener('resize', resizeCanvas);
        resizeCanvas();

        class Particle {
            constructor() {
                this.reset();
            }
            reset() {
                this.x = Math.random() * canvas.width;
                this.y = Math.random() * canvas.height + canvas.height;
                this.size = Math.random() * 2.5 + 0.5;
                this.speedY = Math.random() * 0.8 + 0.2;
                this.speedX = (Math.random() - 0.5) * 0.3;
                this.opacity = Math.random() * 0.8 + 0.2;
            }
            update() {
                this.y -= this.speedY;
                this.x += this.speedX;
                if (this.y < -10) this.reset();
            }
            draw() {
                ctx.fillStyle = `rgba(255, 215, 0, ${this.opacity})`;
                ctx.beginPath();
                ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
                ctx.fill();
            }
        }

        for (let i = 0; i < 75; i++) {
            particles.push(new Particle());
        }

        function animateParticles() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            particles.forEach(p => {
                p.update();
                p.draw();
            });
            requestAnimationFrame(animateParticles);
        }
        animateParticles();

        /* Mobile Drawer Toggle */
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mobileMenu = document.getElementById('mobileMenu');
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        document.querySelectorAll('.mobile-link').forEach(link => {
            link.addEventListener('click', () => mobileMenu.classList.add('hidden'));
        });

        /* Directory Search Filter */
        function filterDirectory() {
            const input = document.getElementById('directorySearch').value.toLowerCase();
            const rows = document.querySelectorAll('#directoryTable tr');
            rows.forEach(row => {
                const text = row.innerText.toLowerCase();
                row.style.display = text.includes(input) ? '' : 'none';
            });
        }

        /* Modal Launcher */
        function openPortalModal(title, url, desc) {
            document.getElementById('modalPortalTitle').innerText = title;
            document.getElementById('modalPortalDesc').innerText = desc;
            document.getElementById('modalTargetUrl').innerText = url;
            document.getElementById('modalLaunchBtn').href = url;

            const modal = document.getElementById('portalModal');
            modal.classList.remove('opacity-0', 'pointer-events-none');
            modal.classList.add('opacity-100', 'pointer-events-auto');
        }

        function closePortalModal() {
            const modal = document.getElementById('portalModal');
            modal.classList.add('opacity-0', 'pointer-events-none');
            modal.classList.remove('opacity-100', 'pointer-events-auto');
        }

        /* 3D Tilt Card Effect */
        document.querySelectorAll('.tilt-card').forEach(card => {
            card.addEventListener('mousemove', (e) => {
                const rect = card.getBoundingClientRect();
                const x = e.clientX - rect.left;
                const y = e.clientY - rect.top;
                const centerX = rect.width / 2;
                const centerY = rect.height / 2;
                const rotateX = ((y - centerY) / centerY) * -5;
                const rotateY = ((x - centerX) / centerX) * 5;

                card.style.transform = `perspective(1000px) rotateX(${rotateX}deg) rotateY(${rotateY}deg)`;
            });

            card.addEventListener('mouseleave', () => {
                card.style.transform = 'perspective(1000px) rotateX(0deg) rotateY(0deg)';
            });
        });
    </script>

</body></html>

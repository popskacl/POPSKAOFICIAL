<!DOCTYPE html><html class="light" lang="es" style=""><head>
<meta charset="utf-8">
<meta content="width=device-width, initial-scale=1.0" name="viewport">
<title>Popska | Cabritas Artesanales &amp; Gourmet</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet">
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "on-background": "#1a1c1d",
                        "tertiary-fixed": "#e5e2e3",
                        "on-error": "#ffffff",
                        "on-secondary-fixed-variant": "#584400",
                        "error": "#ba1a1a",
                        "primary": "#b9003f",
                        "tertiary-fixed-dim": "#c8c6c7",
                        "secondary-container": "#fecb00",
                        "on-surface-variant": "#5c3f42",
                        "surface-container-low": "#f3f3f5",
                        "surface-dim": "#d9dadc",
                        "surface": "#f9f9fb",
                        "on-secondary": "#ffffff",
                        "on-tertiary-container": "#fffcfd",
                        "surface-container-lowest": "#ffffff",
                        "inverse-surface": "#2f3132",
                        "on-primary": "#ffffff",
                        "outline": "#906e71",
                        "background": "#f9f9fb",
                        "on-error-container": "#93000a",
                        "tertiary": "#5c5c5d",
                        "surface-container-high": "#e8e8ea",
                        "surface-variant": "#e2e2e4",
                        "primary-fixed-dim": "#ffb2ba",
                        "on-tertiary-fixed-variant": "#474647",
                        "primary-fixed": "#ffd9dc",
                        "primary-container": "#e51152",
                        "inverse-on-surface": "#f0f0f2",
                        "secondary-fixed-dim": "#f1c100",
                        "on-tertiary-fixed": "#1b1b1c",
                        "on-primary-fixed": "#400010",
                        "secondary-fixed": "#ffe08b",
                        "on-secondary-container": "#6e5700",
                        "secondary": "#745b00",
                        "on-primary-fixed-variant": "#910030",
                        "on-surface": "#1a1c1d",
                        "error-container": "#ffdad6",
                        "inverse-primary": "#ffb2ba",
                        "tertiary-container": "#757475",
                        "surface-container": "#edeef0",
                        "surface-container-highest": "#e2e2e4",
                        "surface-bright": "#f9f9fb",
                        "on-secondary-fixed": "#241a00",
                        "on-primary-container": "#fffbff",
                        "outline-variant": "#e5bdc0",
                        "surface-tint": "#bd0041",
                        "on-tertiary": "#ffffff"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "spacing": {
                        "xs": "4px",
                        "margin-desktop": "64px",
                        "xl": "80px",
                        "lg": "48px",
                        "md": "24px",
                        "margin-mobile": "16px",
                        "base": "8px",
                        "gutter": "24px",
                        "sm": "12px"
                    },
                    "fontFamily": {
                        "body-md": ["Montserrat"],
                        "caption": ["Montserrat"],
                        "headline-lg-mobile": ["Plus Jakarta Sans"],
                        "body-lg": ["Montserrat"],
                        "headline-xl": ["Plus Jakarta Sans"],
                        "headline-lg": ["Plus Jakarta Sans"],
                        "label-bold": ["Montserrat"],
                        "headline-md": ["Plus Jakarta Sans"]
                    },
                    "fontSize": {
                        "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
                        "caption": ["12px", {"lineHeight": "16px", "fontWeight": "500"}],
                        "headline-lg-mobile": ["28px", {"lineHeight": "34px", "fontWeight": "800"}],
                        "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                        "headline-xl": ["48px", {"lineHeight": "56px", "letterSpacing": "-0.02em", "fontWeight": "800"}],
                        "headline-lg": ["32px", {"lineHeight": "40px", "letterSpacing": "-0.01em", "fontWeight": "800"}],
                        "label-bold": ["14px", {"lineHeight": "20px", "fontWeight": "700"}],
                        "headline-md": ["24px", {"lineHeight": "32px", "fontWeight": "700"}]
                    }
                }
            }
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .active-nav-link {
            position: relative;
        }
        .active-nav-link::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 100%;
            height: 2px;
            background-color: currentColor;
        }
        .hero-gradient {
            background: linear-gradient(180deg, rgba(26, 28, 29, 0.4) 0%, rgba(26, 28, 29, 0.1) 100%);
        }
        .bento-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 24px;
        }
        @media (max-width: 768px) {
            .bento-grid {
                grid-template-columns: repeat(1, 1fr);
            }
        }
        .scroll-hide::-webkit-scrollbar {
            display: none;
        }
    </style>
</head>
<body class="bg-background text-on-background font-body-md selection:bg-secondary-container selection:text-on-secondary-container">
<!-- 1. HEADER -->
<header class="fixed top-0 left-0 w-full z-50 bg-surface/80 backdrop-blur-md shadow-sm">
<nav class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop py-base flex justify-between items-center h-20">
<a class="font-headline-md text-headline-md font-black text-primary tracking-tight" href="#"><img alt="Popska Logo" class="h-12 md:h-14 w-auto object-contain" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC8aavvL7fBqlzGDuZu48sA3DiFyRyEm6gTr4pn301SaXrEwNiOu8i-YjnmE6VycdKt9oCtxnWj0bPKc2L6VWhMb1V6ky_1S1Ut9myOOToGe0munK4cWxFUdFvyXGDJ58dgVblGzdjDP43mCTlMCdb5fJBSQPI4sP-1lQxbTlAzlCaZOknaTeWrYtMyNlyeWNRNzXyR1tYHjO9OATxt1ecT4Y8nJWyhCLPlTIma-U_5LwoM1v39W4e_-nlSw7-pmhZ3-ZWyt1vKxc4"></a>
<div class="hidden lg:flex items-center gap-gutter">
<a class="font-body-md text-body-md text-primary font-bold border-b-2 border-primary hover:scale-105 transition-transform duration-200" href="#">Inicio</a>
<a class="font-body-md text-body-md text-on-surface font-medium hover:text-primary hover:scale-105 transition-transform duration-200" href="#">Sabores</a>
<a class="font-body-md text-body-md text-on-surface font-medium hover:text-primary hover:scale-105 transition-transform duration-200" href="#">Combos</a>
<a class="font-body-md text-body-md text-on-surface font-medium hover:text-primary hover:scale-105 transition-transform duration-200" href="#">Eventos</a>
<a class="font-body-md text-body-md text-on-surface font-medium hover:text-primary hover:scale-105 transition-transform duration-200" href="#">Delivery</a>
<a class="font-body-md text-body-md text-on-surface font-medium hover:text-primary hover:scale-105 transition-transform duration-200" href="#">Contacto</a>
</div>
<div class="flex items-center gap-sm md:gap-md">
<button class="material-symbols-outlined text-on-surface-variant hover:text-primary transition-colors">shopping_cart</button>
<button class="material-symbols-outlined text-on-surface-variant hover:text-primary transition-colors">person</button>
<a class="hidden md:flex items-center bg-primary text-on-primary px-md py-xs rounded-xl font-label-bold hover:scale-105 active:scale-95 transition-all shadow-md" href="https://wa.me/something">
                    Pedir por WhatsApp
                </a>
<button class="lg:hidden material-symbols-outlined">menu</button>
</div>
</nav>
</header>
<!-- 2. HERO -->
<section class="relative h-[85vh] md:h-screen w-full flex items-center pt-20">
<div class="absolute inset-0 z-0">
<img class="w-full h-full object-cover" data-alt="A spectacular close-up shot of vibrant, multi-colored gourmet popcorn exploding in the air against a warm, festive background. The lighting is dramatic and high-contrast, highlighting the textures of caramel and chocolate glazes. The overall mood is energetic, appetizing, and artisanal, embodying a premium snack brand aesthetic with rich saturated colors like deep reds and golden yellows." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCUgwQ4ByC41zdhpFnfJPkjARQVDIWr8jiybev_MqD3wphv6V9uvHOza1sb00pMrW4hS1PSHZD8ZTPsDiir-T05NFW8T54oeSXj-pdcgtsF9qwHh9mYx810AD8zJYwe6mlrKUkb_0luUIHBEDvu2sUO7e7gyA894Z1t9tgNxOOnmc0k8glsldSEtn-TYXUhTYSbKtlaOmdufCHMgbM0w4zmUxtEMgFdkep3PdYCEa9ZmrXrfno1oinz0beBfCCDlH6qWHWxSYbxgH8">
<div class="absolute inset-0 bg-gradient-to-r from-on-background/80 via-on-background/40 to-transparent"></div>
</div>
<div class="relative z-10 px-margin-mobile md:px-margin-desktop max-w-4xl">
<span class="inline-block px-sm py-xs bg-secondary-container text-on-secondary-container rounded-full text-caption font-bold mb-md uppercase tracking-widest">Premium Snacks Chile</span>
<h1 class="font-headline-xl text-headline-xl md:text-[64px] text-white leading-tight mb-md">
                Cabritas Artesanales &amp; Gourmet: <br>
<span class="text-secondary-container">El Sabor que amas, la mas POPular.</span>
</h1>
<p class="font-body-lg text-body-lg text-surface-variant max-w-2xl mb-lg">
                Hechas a mano con amor en Chile, perfectas para tus momentos especiales. Calidad premium en cada bocado, directo a tu puerta.
            </p>
<div class="flex flex-col sm:flex-row gap-md">
<button class="bg-primary text-on-primary px-xl py-md rounded-xl font-headline-md hover:brightness-110 hover:scale-[1.02] transition-all shadow-xl">
                    Pedir Ahora
                </button>
<button class="border-2 border-white text-white px-xl py-md rounded-xl font-headline-md hover:bg-white/10 transition-all backdrop-blur-sm">
                    Ver Sabores
                </button>
</div>
</div>
</section>
<!-- 3. TRUST BAR -->
<section class="bg-surface-container py-md shadow-inner">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop flex flex-wrap justify-between items-center gap-md">
<div class="flex items-center gap-sm">
<span class="material-symbols-outlined text-primary" style="font-variation-settings: &quot;FILL&quot; 1;">favorite</span>
<span class="font-label-bold text-on-surface-variant">Cada dia somos +</span>
</div>
<div class="flex items-center gap-sm">
<span class="material-symbols-outlined text-primary" style="font-variation-settings: &quot;FILL&quot; 1;">auto_awesome</span>
<span class="font-label-bold text-on-surface-variant">100% Artesanal</span>
</div>
<div class="flex items-center gap-sm">
<span class="material-symbols-outlined text-primary" style="font-variation-settings: &quot;FILL&quot; 1;">verified</span>
<span class="font-label-bold text-on-surface-variant">Frescas</span>
</div>
<div class="flex items-center gap-sm">
<span class="material-symbols-outlined text-primary" style="font-variation-settings: &quot;FILL&quot; 1;">timer</span>
<span class="font-label-bold text-on-surface-variant">Hecho al momento</span>
</div>
</div>
</section>
<!-- 4. FLAVORS CATALOG -->
<section class="py-xl bg-surface">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<div class="flex justify-between items-end mb-xl">
<div>
<h2 class="font-headline-lg text-headline-lg text-on-background mb-xs">Nuestros Sabores Estrella</h2>
<p class="font-body-md text-on-surface-variant">Explora una explosión de sabor artesanal.</p>
</div>
<button class="text-primary font-label-bold flex items-center gap-xs hover:gap-sm transition-all underline underline-offset-4">
                    Ver todo el catálogo <span class="material-symbols-outlined">arrow_forward</span>
</button>
</div>
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-gutter">
<!-- Caramel Card -->
<div class="group bg-surface-container-lowest rounded-[32px] overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 transform hover:-translate-y-2">
<div class="aspect-square relative overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="A professional food photography shot of a ceramic bowl overflowing with golden caramel gourmet popcorn mixed with whole roasted pecans and almonds. The background is a vibrant solid yellow, creating a cheerful and high-contrast look. Small sprinkles of sea salt crystals are visible, and the lighting is bright and even, highlighting the glossy caramel glaze." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDVsSRFd3wXwm5C4USXSWM876IxwqUnOKp-xFf8PSOWWSmoN2F4JXymdHU_e5fKfjj0iNKXHT1RmWbLIZUbAXW9jBH_US2gIYBUAg3QCXB8c4sp48ZViovdSEJgOHWvqZkrCExgk5U3nUb7jUmyZbZwv5qs-pXK2e-cHLkg3NzRY99HldOXxGqgsEGto5itXs3riXp3D2uphdPftnegy1o4VKBybpPnG5Pl1gYHPY-JVwC4jrOA9bjNw8ZBEC-4wF4fcpiXRpBrSLngYQ">
<span class="absolute top-md left-md bg-secondary text-on-secondary px-sm py-xs rounded-full text-caption font-bold">BEST SELLER</span>
</div>
<div class="p-md">
<h3 class="font-headline-md text-headline-md text-on-background mb-xs">POPSKA Dulce Clasico</h3>
<p class="font-body-md text-on-surface-variant mb-md h-12 line-clamp-2">Cabritas clasicas, con un toque de vainilla y pizca de sal. (100 gr)</p>
<div class="flex justify-between items-center">
<span class="font-headline-md text-primary">$2.000</span>
<button class="bg-primary text-on-primary w-12 h-12 rounded-full flex items-center justify-center hover:scale-110 active:scale-95 transition-all">
<span class="material-symbols-outlined">add_shopping_cart</span>
</button>
</div>
</div>
</div>
<!-- Cheese Card -->
<div class="group bg-surface-container-lowest rounded-[32px] overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 transform hover:-translate-y-2">
<div class="aspect-square relative overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="A premium packaging of gourmet cheese popcorn sitting on a soft pink background. The bag is white with yellow cheese illustrations and says 'Crisp &amp; Cheddar'. Freshly popped orange-hued cheddar popcorn is spilling out of the top and scattered around the base alongside a small wooden bowl and a golden scoop. Soft, bright lighting creates a clean, commercial aesthetic." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDczUfLShuKCcqm9M6Pc1-8jCBqwO-z9F4tvJOKcvgpFO-1zGPwlfk9aQ1snlw3f8vnoPXp3GOVK35SZYOxoXANTawIt58SyYsOU5_UNnlyGTy2ZpA5ev9-ukD7QBl4SetNXNcpoCn2-MxJc9Ir-yiq5O_5GsnR4y_iLMI8sERQcK0zJWLEV5YO6JA8IgcfLoveSUy3-Vl7aTawWubgOswmbOL4lGwtDu59fIQIDLrL7RJAXkv3L_aKBSOoCSIPrulIKrPRaxASVCh_-g">
</div>
<div class="p-md">
<h3 class="font-headline-md text-headline-md text-on-background mb-xs">POPSKA Dulce Arcoiris</h3>
<p class="font-body-md text-on-surface-variant mb-md h-12 line-clamp-2">Cabritas dulces, con azucar de colores vegetal (100 gr)</p>
<div class="flex justify-between items-center">
<span class="font-headline-md text-primary">$2.500</span>
<button class="bg-primary text-on-primary w-12 h-12 rounded-full flex items-center justify-center hover:scale-110 active:scale-95 transition-all">
<span class="material-symbols-outlined">add_shopping_cart</span>
</button>
</div>
</div>
</div>
<!-- Chocolate Card -->
<div class="group bg-surface-container-lowest rounded-[32px] overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 transform hover:-translate-y-2">
<div class="aspect-square relative overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Dark chocolate drizzled gourmet popcorn styled elegantly on a stone surface. The popcorn is coated in rich cocoa and white chocolate stripes, looking incredibly decadent. Warm, moody lighting with soft bokeh background. Luxury food photography style focusing on the glossy chocolate textures and crunch." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBuzcrV49kjEfIkJwkA4-kOXfGN8ySse371GAfVBBq-cEn4xYq4SC7dnKcEFgnwLliM2FAY6lPszjZp8BGfZWhW8e0WriXiwaM6Ze5ZS7YgDjvX0HJQbVv3PQxNyG8dyXaz8syELJWYX7CTbC6COn0Cs1cHGfrtQB5wQh2JYHq9XYwAq9RtHh2jzGyvEQzLDzAush_yIHZlG7hydJwa48eIufgSHM8OBdthXBAh0z4n4FZyKGDReJk_RdO5QTidRj3VJ82pLLhQusd0eA">
<span class="absolute top-md left-md bg-on-background text-white px-sm py-xs rounded-full text-caption font-bold">PREMIUM</span>
</div>
<div class="p-md">
<h3 class="font-headline-md text-headline-md text-on-background mb-xs">POPSKA Saladas</h3>
<p class="font-body-md text-on-surface-variant mb-md h-12 line-clamp-2">Cabritas Saladas (100 gr)</p>
<div class="flex justify-between items-center">
<span class="font-headline-md text-primary">$2.000</span>
<button class="bg-primary text-on-primary w-12 h-12 rounded-full flex items-center justify-center hover:scale-110 active:scale-95 transition-all">
<span class="material-symbols-outlined">add_shopping_cart</span>
</button>
</div>
</div>
</div>
<!-- Berries Card -->
<div class="group bg-surface-container-lowest rounded-[32px] overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 transform hover:-translate-y-2">
<div class="aspect-square relative overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" data-alt="Playful and vibrant pink-hued gourmet popcorn flavored with wild berries and strawberry. The popcorn has a dusty pink coating and is styled in a modern glass bowl. Soft daylight and a pastel blue background. Artistic and feminine food presentation with a focus on fresh, fruity ingredients." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAqdUFNXR-VODnRQguo0U7hReVbgt2kQWCnxsygbGFTVjysJaTuT-KgM5n-y8jtKDn2EWtC0fAzTshxai65tXBGS2H8xWjhseFygjQtFrgvdV367x3Wm2LzJG85fPUas7kwbd9wNMM7HV_pkAnPv-Eq9-S15BI61ti8Sl4J2jYJSMZK4zrbvOjNPaw4ASNO06XLi2k-7klkmhSjvCVNsitox_A_7CzIEtnZ_Avpoki-eTp0OgzpFpd4PfrYhyQ1yMcE5mBC6NBGFC5-LQ">
</div>
<div class="p-md">
<h3 class="font-headline-md text-headline-md text-on-background mb-xs">POPSKA Mantequilla Dulce</h3>
<p class="font-body-md text-on-surface-variant mb-md h-12 line-clamp-2">Cabritas dulces, con sabor mantequilla y pizca de sal. (100 gr)</p>
<div class="flex justify-between items-center">
<span class="font-headline-md text-primary">$3.000</span>
<button class="bg-primary text-on-primary w-12 h-12 rounded-full flex items-center justify-center hover:scale-110 active:scale-95 transition-all">
<span class="material-symbols-outlined">add_shopping_cart</span>
</button>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- 5. WHY US -->
<section class="py-xl bg-surface-container-lowest">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<h2 class="font-headline-lg text-headline-lg text-center mb-xl">¿Por qué elegir Popska?</h2>
<div class="grid grid-cols-1 md:grid-cols-4 gap-xl">
<div class="text-center group">
<div class="w-20 h-20 bg-primary-fixed mx-auto rounded-3xl flex items-center justify-center mb-md group-hover:rotate-6 transition-transform">
<span class="material-symbols-outlined text-primary text-[40px]">eco</span>
</div>
<h4 class="font-headline-md mb-xs">Ingredientes Premium</h4>
<p class="font-body-md text-on-surface-variant">Maíz mushroom gigante y coberturas de origen natural.</p>
</div>
<div class="text-center group">
<div class="w-20 h-20 bg-secondary-fixed mx-auto rounded-3xl flex items-center justify-center mb-md group-hover:-rotate-6 transition-transform">
<span class="material-symbols-outlined text-secondary text-[40px]">restaurant</span>
</div>
<h4 class="font-headline-md mb-xs">Receta Artesanal</h4>
<p class="font-body-md text-on-surface-variant">Hechas a mano en pequeños lotes para garantizar frescura.</p>
</div>
<div class="text-center group">
<div class="w-20 h-20 bg-tertiary-fixed mx-auto rounded-3xl flex items-center justify-center mb-md group-hover:rotate-6 transition-transform">
<span class="material-symbols-outlined text-tertiary text-[40px]">health_and_safety</span>
</div>
<h4 class="font-headline-md mb-xs">100% Sin Sellos</h4>
<p class="font-body-md text-on-surface-variant">Disfruta sin culpas de un snack saludable y delicioso.</p>
</div>
<div class="text-center group">
<div class="w-20 h-20 bg-primary-fixed-dim mx-auto rounded-3xl flex items-center justify-center mb-md group-hover:-rotate-6 transition-transform">

</div>
<h4 class="font-headline-md mb-xs">Variedad Única</h4>
<p class="font-body-md text-on-surface-variant">Sabores exclusivos que no encontrarás en ningún otro lugar.</p>
</div>
</div>
</div>
</section>
<!-- 6. DELIVERY ZONE -->
<section class="py-xl bg-on-background text-white overflow-hidden relative">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop relative z-10 flex flex-col md:flex-row items-center gap-xl">
<div class="flex-1">
<h2 class="font-headline-lg text-headline-lg mb-md">Delivery en Santiago &amp; Regiones</h2>
<p class="font-body-lg text-surface-variant mb-xl">Llegamos a cada rincón con la frescura de Popska. Haz tu pedido directo o búscanos en tus apps favoritas.</p>
<div class="space-y-lg mb-xl">
<div class="flex items-start gap-md">
<span class="material-symbols-outlined text-secondary-container">location_on</span>
<div>
<p class="font-label-bold">Despacho Express</p>
<p class="font-body-md text-surface-variant">La Florida, Santiago (RM) en menos de 24 horas.</p>
</div>
</div>
<div class="flex items-start gap-md">
<span class="material-symbols-outlined text-secondary-container">local_shipping</span>
<div>
<p class="font-label-bold">Envíos a Regiones</p>
<p class="font-body-md text-surface-variant">Vía Blue Express y Starken a todo Chile.</p>
</div>
</div>
</div>
<div class="flex flex-wrap gap-md items-center grayscale opacity-70 hover:grayscale-0 hover:opacity-100 transition-all duration-500">
<span class="font-label-bold text-surface-variant mr-md">Búscanos PRONTO en:</span>
<div class="bg-white/10 px-md py-xs rounded-lg font-bold">Uber Eats</div>
<div class="bg-white/10 px-md py-xs rounded-lg font-bold">Rappi</div>
<div class="bg-white/10 px-md py-xs rounded-lg font-bold">PedidosYa</div>
</div>
<button class="mt-xl w-full md:w-auto bg-[#25D366] text-white px-xl py-md rounded-2xl font-headline-md flex items-center justify-center gap-md hover:scale-105 active:scale-95 transition-all">
<span class="material-symbols-outlined">message</span> Pedir por WhatsApp
                </button>
</div>
<div class="flex-1 w-full h-[400px] rounded-[40px] overflow-hidden shadow-2xl">
<div class="w-full h-full bg-surface-container relative" data-location="Santiago, Chile">
<img class="w-full h-full object-cover" data-alt="A stylized minimalist digital map of Santiago, Chile, highlighting delivery zones with vibrant red and yellow overlays. The visual style is clean and modern, using the brand colors. The map looks high-tech yet friendly, emphasizing accessibility and quick service across the urban landscape." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCP5FUqzoeL9DSei_KUk2eMDSAl18eGTEd9TySTql7Sj1Y4SifFm2JaxdNi52wVVI8CVvHY-VqgeM36eslQU1AsrOxGskQlJL3v90ukTwTU7Cf0-znYbUePr9SR73KEP6HPtRoO3mtUATD-D0-OceZlyPFfZBykthbZwasUxbCf-LR4E1MlusZ1u1EnipMiSuwi50m888ocl4J3GebJZIYttBWH96p_nlRbUeNFTSiM1wiugqlqdYqnEtGbTXpslnH0O3uaJyBpxwg">
</div>
</div>
</div>
</section>
<!-- 7. COMBOS -->
<section class="py-xl bg-surface-container-high">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<h2 class="font-headline-lg text-headline-lg mb-xl text-center">Nuestros Packs para Disfrutar</h2>
<div class="grid grid-cols-1 md:grid-cols-3 gap-gutter">
<!-- Pack 1 -->
<div class="bg-white p-lg rounded-[40px] flex flex-col items-center text-center shadow-sm hover:shadow-xl transition-all">
<span class="material-symbols-outlined text-primary text-[64px] mb-md">person</span>
<h3 class="font-headline-md mb-xs">Pack Pareja</h3>
<p class="font-body-md text-on-surface-variant mb-lg">3 sabores a elección para tu maratón de series.</p>
<span class="font-headline-lg text-on-background mb-lg">$12.900</span>
<button class="mt-auto w-full border-2 border-primary text-primary py-md rounded-xl font-label-bold hover:bg-primary hover:text-on-primary transition-all">Comprar</button>
</div>
<!-- Pack 2 -->
<div class="bg-primary text-on-primary p-lg rounded-[40px] flex flex-col items-center text-center shadow-xl scale-105 relative">
<div class="absolute -top-4 bg-secondary-container text-on-secondary-container px-md py-xs rounded-full font-bold text-caption">MÁS POPULAR</div>
<div class="w-full h-48 rounded-2xl overflow-hidden mb-md">
<img alt="Combo Compartir" class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCczfu4HbE6mP912ql-mzJn6VHsxxuQRV1Ph9hZ-uCpUfCE6lc9DwYP0tL2ijt5MoTK61FCdToeOtT_vMJ9gRcbCk0_tv6pIKeRAa9VMC688ncM4pwULIRRThokRHtO2PfRFl-OhTzvtdvziFoWoeH9W3HleBgbJm_v_EniCbaO_HNeKYHldQ_LJ06usHB7u_3-dFSj1yDH-BRMC91-F9XOedtSHP70HCkA3lg62Tih3tagnO1V_dq2sUTlZzFttnBNSblEtrANNLc">
</div>
<h3 class="font-headline-md mb-xs">Combo Compartir</h3>
<p class="font-body-md text-primary-fixed mb-lg">Balde gigante + 4 bebidas. Perfecto para 4 personas.</p>
<span class="font-headline-lg mb-lg">$24.900</span>
<button class="mt-auto w-full bg-white text-primary py-md rounded-xl font-label-bold hover:bg-primary-fixed transition-all">Comprar</button>
</div>
<!-- Pack 3 -->
<div class="bg-white p-lg rounded-[40px] flex flex-col items-center text-center shadow-sm hover:shadow-xl transition-all">
<span class="material-symbols-outlined text-primary text-[64px] mb-md">celebration</span>
<h3 class="font-headline-md mb-xs">Fiesta Pack</h3>
<p class="font-body-md text-on-surface-variant mb-lg">10 minipacks variados para cumpleaños y eventos.</p>
<span class="font-headline-lg text-on-background mb-lg">$35.000</span>
<button class="mt-auto w-full border-2 border-primary text-primary py-md rounded-xl font-label-bold hover:bg-primary hover:text-on-primary transition-all">Comprar</button>
</div>
</div>
</div>
</section>
<!-- 8. EVENTS -->
<section class="py-xl">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<div class="relative rounded-[48px] overflow-hidden bg-secondary-fixed h-[500px] group">
<img alt="Event Popcorn Cart" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-[2s]" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBNXBx3SFNlnnu3poTB_CWQ60YUuTt0jfF29QKTtS9eHlFi7rTgHiFp_D8aDGue_0kfd1-Y9ZFhN_E0nA4Pq1NwdgUA1Ivh9lyS7oTzA1wSd6zoDlUNYOAkbsjNXVt3l9WOwLFBrmKHsik-PxLt5x_qEQoSncxQqjl81zqQCIRsC52oFLqYgzIqx-cI5Da1QGRAFNwY90mgLjsnHirH2W7UnwrMb_-Z_XkZajQhDS4YRHksOgOmUdAbGG817sLvtsljKTjm_e6a2lQ">
<div class="absolute inset-0 bg-gradient-to-t from-on-background/90 via-on-background/20 to-transparent flex items-end p-xl">
<div class="max-w-2xl">
<h2 class="font-headline-xl text-headline-xl text-white mb-md">Lleva la diversión a tu evento</h2>
<p class="font-body-lg text-surface-variant mb-lg">Cumpleaños, eventos corporativos, bodas y más. Nuestro carrito de cabritas es el alma de la fiesta.</p>
<button class="bg-secondary-container text-on-secondary-container px-xl py-md rounded-xl font-headline-md hover:scale-105 transition-all">
                            Cotizar mi evento
                        </button>
</div>
</div>
</div>
</div>
</section>
<!-- 9. TESTIMONIALS -->
<section class="py-xl bg-surface">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<h2 class="font-headline-lg text-headline-lg text-center mb-xl">Lo que dicen nuestros clientes</h2>
<div class="flex gap-gutter overflow-x-auto scroll-hide pb-md">
<div class="min-w-[320px] bg-white p-lg rounded-3xl shadow-sm border border-surface-container">
<div class="flex text-secondary-container mb-md">
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
</div>
<p class="font-body-md italic mb-md">"Las mejores cabritas que he probado en Chile. El sabor a Caramelo es simplemente de otro planeta."</p>
<div class="flex items-center gap-sm">
<div class="w-10 h-10 rounded-full bg-primary-fixed"></div>
<span class="font-label-bold">Carolina M.</span>
</div>
</div>
<!-- Duplicate for carousel effect -->
<div class="min-w-[320px] bg-white p-lg rounded-3xl shadow-sm border border-surface-container">
<div class="flex text-secondary-container mb-md">
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
</div>
<p class="font-body-md italic mb-md">"Me encanta que no tengan sellos. Mis hijos las aman y yo estoy tranquila dándoselas."</p>
<div class="flex items-center gap-sm">
<div class="w-10 h-10 rounded-full bg-secondary-fixed"></div>
<span class="font-label-bold">Andrés P.</span>
</div>
</div>
<div class="min-w-[320px] bg-white p-lg rounded-3xl shadow-sm border border-surface-container">
<div class="flex text-secondary-container mb-md">
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
<span class="material-symbols-outlined" style="font-variation-settings: &quot;FILL&quot; 1;">star</span>
</div>
<p class="font-body-md italic mb-md">"El servicio de delivery es ultra rápido. Llegaron calentitas y crujientes."</p>
<div class="flex items-center gap-sm">
<div class="w-10 h-10 rounded-full bg-tertiary-fixed"></div>
<span class="font-label-bold">Francisca L.</span>
</div>
</div>
</div>
</div>
</section>
<!-- 10. INSTAGRAM FEED -->
<section class="py-xl">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<div class="text-center mb-xl">
<h2 class="font-headline-lg text-headline-lg mb-xs">@Popska.cl</h2>
<p class="font-body-md text-on-surface-variant">Síguenos para promos y nuevos sabores.</p>
</div>
<div class="grid grid-cols-2 md:grid-cols-6 gap-sm mb-xl">
<div class="aspect-square rounded-xl overflow-hidden cursor-pointer hover:opacity-80 transition-opacity">
<img class="w-full h-full object-cover" data-alt="Close up aesthetic shot of colorful popcorn for instagram feed" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBGu5LyBQgMAFFDNDFwikPYEqasw-Z-Qf2QAxQ_eegktjOovnxGkpEQPrB-c4DHdRE59kk-ita-0SAMKQpV5Ra7w16dCLUHg3AHlAARVIG3c07c888KMdVVjD14GDpIWYFwCvGLPExH2eKytn_GwRBIdtUOrQie27yVFcGCCYZ3jWXJU9oncDfEX7QzGHWS0c7TD7QyQUCiD3KAQstEhi2bHY44wN0eqcwoNiQQ-yvqI8RrlukF0muQzldiZAw2nA-4qRU8wos29sQo9w">
</div>
<div class="aspect-square rounded-xl overflow-hidden cursor-pointer hover:opacity-80 transition-opacity">
<img class="w-full h-full object-cover" data-alt="Lifestyle shot of someone holding a bag of gourmet popcorn outdoors" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAzvN9cZ4t3LPGALY4LKdT1oQz4PWcIS7bhAVF9PfYWAJ85mQ8n3U-bDoq6SB4jxA7QCJt4TWdJ7Q95kS4uAmmg7-3cVS_scTX4dVSZk1TdSzquusbzVL8s4xS_YUcGQVbMRWxJXDUyXZ9RVRk0aY0UP7lhoPvK7VOm9Pt5ZZzptEhtLWv6VJc_SLnCo2n0s6Zo4EYDAxQ2QDroPAfSVs26lAk7TPstg5QjDhDJb7BYKQi3tW7EvUC-69DP9IOs_gIa5yNF_acmyTCH0Q">
</div>
<div class="aspect-square rounded-xl overflow-hidden cursor-pointer hover:opacity-80 transition-opacity">
<img class="w-full h-full object-cover" data-alt="Flat lay of popcorn ingredients like corn kernels and melted chocolate" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDZ46lSeW1fdAxAUHoVmUCttked9UDGqixJ227op1QVKsAxQbjbPhFqPI2jlvUCd-0nuJp1mF1JyqDMQ0xck4Pa7VISvxmkIHoWqUawWyYjJ-tTZvffPKNekksK72D8fSHLBJfNjpw7fLXvrrFv5xT1xOQyXpo0A4R7EJZtoQjiYYvpF27ZV000ImCjX7i-U-fWPFnBBwN7TP8sLp96oWN6wQoUnzdEINBIAZeVI8eC77aLbmv288ZRYKQeD9ulsMf3Yu9vDINTfD7aKw">
</div>
<div class="aspect-square rounded-xl overflow-hidden cursor-pointer hover:opacity-80 transition-opacity">
<img class="w-full h-full object-cover" data-alt="Happy child eating colorful popcorn at a party" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBTCCfpMeKkR-KznvmU0Phns4gqrZGUmL2fEN4xPFMcENB7yTXmMUBaA76fFnOnT23DDRmQXQ2OYQjYWBuF6MZuSeMq0Artdq1-gWUiXbyh2SNbB2aD8OVqj6gQXTBzHLGfjldOdJZ8kPDUd7pvou_iEJIMliYQxFlWC3dsgDmuN7xcwHSdEX_8c2aU4zIjoROdZQuy5Q0OVrXJOZtU7dlstLEtomlGkDW7pLqGziQfvNGZD2JGUt5W0PymbIrJW6M6a1KDtrP2-4ZXlg">
</div>
<div class="aspect-square rounded-xl overflow-hidden cursor-pointer hover:opacity-80 transition-opacity">
<img class="w-full h-full object-cover" data-alt="Gourmet popcorn cart detailed shot with balloons" src="https://lh3.googleusercontent.com/aida-public/AB6AXuApv2e4XlNlZ_e2W4GQ1bavc_vnkj4ZoNaQKie6VkGbT3j1TuFLqu2OMVD1lP_nvaFFEyDlqPUsawDZH4F4xoVNtQ-e4e8ddQAUsYz6GIGQnSEf1wif-fNIfy_Y7pyomzSssFYtpcz9E-SwvoTSb6Y63OxYHxCzJ2cAhUZSoCZxjfMNy4OREj9hPNrjgNgy6McOR0Cn0lqyjglumuedSw9kYv_JNJuSAKUIglYTdJuQXBh7yOQ88RnRX3YYIPprZt8IErZcMMXmuX6EAg">
</div>
<div class="aspect-square rounded-xl overflow-hidden cursor-pointer hover:opacity-80 transition-opacity">
<img class="w-full h-full object-cover" data-alt="Artistic macro shot of a single caramel popcorn kernel" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDZGxorSZv38DQqTY4j4XwceMWL38Rne5oZFWURSbfguCCQpm_W_VR6FenOaMofb44etDD-HHBdST5KqXtqqvTaoI-7LZ5LxA_giRlrMCMixKXC_T1f-GcadmUqLOnj1J_r2Ln8UWoDg-4rIDDz2J4b8C2ddOg-W0IMmYg-YkUF2haEuQFaegmtaNVhzRdENEFyLC0pFG-G3N7le2-qk17Wfeota17mqX224JPr_N4Xzq5JyfUky-dmmGR5RllPSOBdsulQw2jerRSGiA">
</div>
</div>
<div class="text-center">
<button class="inline-flex items-center gap-sm bg-on-background text-white px-lg py-md rounded-xl font-label-bold hover:scale-105 transition-all">
                    Síguenos en Instagram
                </button>
</div>
</div>
</section>
<!-- 11. NEWSLETTER -->
<section class="py-xl bg-primary relative overflow-hidden">
<div class="absolute inset-0 opacity-10">
<div class="grid grid-cols-12 gap-2 h-full">
<!-- Decorative background pattern using tailwind -->
<div class="col-span-1 border-r border-white/20"></div>
<div class="col-span-1 border-r border-white/20"></div>
<div class="col-span-1 border-r border-white/20"></div>
<div class="col-span-1 border-r border-white/20"></div>
</div>
</div>
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop relative z-10">
<div class="bg-white rounded-[40px] p-lg md:p-xl flex flex-col md:flex-row items-center justify-between gap-xl shadow-2xl">
<div class="max-w-xl">
<h2 class="font-headline-lg text-headline-lg mb-md text-primary">¡Únete a la Pop-Lista!</h2>
<p class="font-body-lg text-on-surface-variant">Regístrate en nuestra lista de WhatsApp y recibe un <span class="font-bold text-primary">10% OFF</span> en tu primera compra.</p>
</div>
<div class="w-full md:w-auto flex flex-col sm:flex-row gap-md">
<input class="px-md py-md bg-surface-container rounded-xl border-none focus:ring-2 focus:ring-primary w-full md:w-80 font-body-md" placeholder="Tu número de WhatsApp" type="text">
<button class="bg-primary text-on-primary px-lg py-md rounded-xl font-headline-md hover:brightness-110 shadow-lg whitespace-nowrap">
                        Quiero mi Descuento
                    </button>
</div>
</div>
</div>
</section>
<!-- 12. FOOTER -->
<footer class="bg-on-background text-secondary-container py-xl">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<div class="flex flex-col md:flex-row justify-between items-start gap-gutter mb-xl">
<div>
<img alt="Popska Logo" class="h-16 md:h-20 w-auto object-contain mb-md" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC8aavvL7fBqlzGDuZu48sA3DiFyRyEm6gTr4pn301SaXrEwNiOu8i-YjnmE6VycdKt9oCtxnWj0bPKc2L6VWhMb1V6ky_1S1Ut9myOOToGe0munK4cWxFUdFvyXGDJ58dgVblGzdjDP43mCTlMCdb5fJBSQPI4sP-1lQxbTlAzlCaZOknaTeWrYtMyNlyeWNRNzXyR1tYHjO9OATxt1ecT4Y8nJWyhCLPlTIma-U_5LwoM1v39W4e_-nlSw7-pmhZ3-ZWyt1vKxc4">
<p class="font-body-md text-tertiary-fixed-dim max-w-sm mt-md">Las mejores cabritas gourmet de Chile, hechas con amor y sin sellos para tus mejores momentos.</p>
</div>
<div class="grid grid-cols-2 gap-xl">
<div>
<h4 class="font-label-bold text-white mb-md">Menú</h4>
<ul class="space-y-sm">
<li class=""><a class="font-body-md text-tertiary-fixed-dim hover:text-primary transition-colors" href="#">Inicio</a></li>
<li class=""><a class="font-body-md text-tertiary-fixed-dim hover:text-primary transition-colors" href="#">Sabores</a></li>
<li class=""><a class="font-body-md text-tertiary-fixed-dim hover:text-primary transition-colors" href="#">Combos</a></li>
</ul>
</div>
<div>
<h4 class="font-label-bold text-white mb-md">Ayuda</h4>
<ul class="space-y-sm">
<li class=""><a class="font-body-md text-tertiary-fixed-dim hover:text-primary transition-colors" href="#">Preguntas Frecuentes</a></li>
<li class=""><a class="font-body-md text-tertiary-fixed-dim hover:text-primary transition-colors" href="#">Envíos</a></li>
<li class=""><a class="font-body-md text-tertiary-fixed-dim hover:text-primary transition-colors" href="#">Contacto</a></li>
</ul>
</div>
</div>
<div>
<h4 class="font-label-bold text-white mb-md">Legal</h4>
<ul class="space-y-sm">
<li class=""><a class="font-body-md text-tertiary-fixed-dim hover:text-primary transition-colors" href="#">Privacidad</a></li>
<li class=""><a class="font-body-md text-tertiary-fixed-dim hover:text-primary transition-colors" href="#">Términos y Condiciones</a></li>
</ul>
</div>
</div>
<div class="pt-xl border-t border-white/10 flex flex-col md:flex-row justify-between items-center gap-md">
<p class="font-body-md text-tertiary-fixed-dim">© 2024 Popska Gourmet Popcorn. Hecho con sabor.</p>
<div class="flex gap-md">
<button class="material-symbols-outlined text-tertiary-fixed-dim hover:text-primary">facebook</button>
<button class="material-symbols-outlined text-tertiary-fixed-dim hover:text-primary">share</button>
<button class="material-symbols-outlined text-tertiary-fixed-dim hover:text-primary">mail</button>
</div>
</div>
</div>
</footer>
<!-- Interactive Scripts -->
<script>
        // Smooth scroll implementation
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Header scroll effect
        window.addEventListener('scroll', () => {
            const header = document.querySelector('header');
            if (window.scrollY > 50) {
                header.classList.add('shadow-md');
            } else {
                header.classList.remove('shadow-md');
            }
        });
    </script>




</body></html>

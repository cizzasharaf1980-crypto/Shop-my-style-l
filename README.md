# Shop-my-style-l
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Premium Outfit Gallery Hub</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,100..900;1,100..900&amp;family=Noto+Sans:ital,wght@0,100..900;1,100..900&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "primary": "#ee2b5b",
              "background-light": "#fcf8f9",
              "background-dark": "#221015",
              "accent-pink": "#f3e7ea",
              "muted-pink": "#9a4c5f",
              "deep-text": "#1b0d11"
            },
            fontFamily: {
              "display": ["Noto Serif", "serif"],
              "sans": ["Noto Sans", "sans-serif"]
            },
            borderRadius: {"DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "full": "9999px"},
          },
        },
      }
    </script>
<style>
      body {
        font-family: 'Noto Sans', sans-serif;
      }
      h1, h2, h3, .font-display {
        font-family: 'Noto Serif', serif;
      }
    </style>
</head>
<body class="bg-background-light dark:bg-background-dark text-deep-text transition-colors duration-300">
<div class="relative flex h-auto min-h-screen w-full flex-col group/design-root overflow-x-hidden">
<div class="layout-container flex h-full grow flex-col">
<!-- TopNavBar Component -->
<header class="flex items-center justify-between whitespace-nowrap border-b border-solid border-accent-pink dark:border-white/10 px-6 lg:px-40 py-3 bg-white/50 dark:bg-background-dark/50 backdrop-blur-md sticky top-0 z-50">
<div class="flex items-center gap-8">
<div class="flex items-center gap-4 text-deep-text dark:text-white">
<div class="size-6 text-primary">
<span class="material-symbols-outlined text-3xl">auto_awesome</span>
</div>
<h2 class="text-deep-text dark:text-white text-lg font-bold leading-tight tracking-[-0.015em] font-display">Premium Outfit Hub</h2>
</div>
<div class="hidden md:flex items-center gap-9">
<a class="text-deep-text dark:text-white/80 text-sm font-medium leading-normal hover:text-primary transition-colors" href="#">New Looks</a>
<a class="text-deep-text dark:text-white/80 text-sm font-medium leading-normal hover:text-primary transition-colors" href="#">Collections</a>
<a class="text-deep-text dark:text-white/80 text-sm font-medium leading-normal hover:text-primary transition-colors" href="#">Shop All</a>
</div>
</div>
<div class="flex flex-1 justify-end gap-4 lg:gap-8 items-center">
<label class="hidden sm:flex flex-col min-w-40 !h-10 max-w-64">
<div class="flex w-full flex-1 items-stretch rounded-lg h-full">
<div class="text-muted-pink flex border-none bg-accent-pink dark:bg-white/5 items-center justify-center pl-4 rounded-l-lg">
<span class="material-symbols-outlined text-xl">search</span>
</div>
<input class="form-input flex w-full min-w-0 flex-1 border-none bg-accent-pink dark:bg-white/5 focus:outline-0 focus:ring-0 text-deep-text dark:text-white h-full placeholder:text-muted-pink px-4 rounded-r-lg pl-2 text-base font-normal leading-normal" placeholder="Search outfits..." value=""/>
</div>
</label>
<button class="flex min-w-[84px] cursor-pointer items-center justify-center overflow-hidden rounded-lg h-10 px-4 bg-primary text-white text-sm font-bold leading-normal tracking-[0.015em] hover:brightness-110 transition-all">
<span class="truncate font-sans">Sign Up</span>
</button>
<div class="bg-center bg-no-repeat aspect-square bg-cover rounded-full size-10 ring-2 ring-primary/20" data-alt="User profile avatar placeholder" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCVAqCfvVrq-WOZmYkJgHVO2ZMlu7zjsPiCCIWlUULiiKnAIGgTB0tTjMRTfzSPOlFGze_yMwny4sig36uMKbBBdNpw8zKQq7rH_arxK7_tvehVfWyXbMYfQyVkhLtW4Szb_y2jpA_ZkN865FpwUNy7biV3U4cHTrHRQMY9y1E6F3mri4u1962VpMOSFwY7nAKcKTVEzD6CSX4AZqvFTeQPJY-8qGB5rKzctR5uYE9CmTjxtgrgIlrh2S6xiz-26aM_TVJEAxrD-qML");'></div>
</div>
</header>
<main class="flex flex-1 justify-center py-10">
<div class="layout-content-container flex flex-col max-w-[1200px] flex-1 px-4 sm:px-10 lg:px-20">
<!-- HeadlineText Component -->
<div class="max-w-[800px] mx-auto mb-12">
<h1 class="text-deep-text dark:text-white tracking-light text-[28px] md:text-[42px] font-bold leading-tight text-center pb-3 pt-6 font-display">
                            ✨ Browse my modest outfits and shop all items from each look ✨
                        </h1>
<p class="text-muted-pink dark:text-muted-pink/80 text-center text-lg font-sans">Curated high-end fashion for the modern minimalist.</p>
</div>
<!-- Gallery Grid -->
<div class="grid grid-cols-1 md:grid-cols-2 gap-12 lg:gap-16">
<!-- Outfit Card 1 -->
<div class="flex flex-col gap-6 group">
<div class="w-full bg-center bg-no-repeat aspect-[3/4] bg-cover rounded-xl shadow-lg ring-1 ring-black/5 overflow-hidden transition-transform duration-500 group-hover:scale-[1.02]" data-alt="Elegant modest outfit featuring a silk long dress" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuBNyWy6KS-siTXDrAOnknayPG-bz_JQ_HB89cKO9xTAw-N-lJKNCH2uvhzj340mQULcr7FyilqP7ftWVUijqPnN06fBPBcp8uLODK4GyOWrokOfRqFuXOGiJeQJHEF4Y0RsOiAEhQakNQcfSWq9grGFGHZExx-ReVIafTZQYUtfqXwEh6U3IAdvatnlJdXXRxkRT-woEG528QwoyShIp4NhHj6SZm9wHGp0d48hmXMAAQulToMiXRPd5AQnBGUKP7B3ruCQSbg6maRV");'>
</div>
<div class="px-2">
<h3 class="text-deep-text dark:text-white text-2xl font-bold leading-normal font-display">The Silk Minimalist Look</h3>
<p class="text-muted-pink dark:text-muted-pink/80 text-base font-normal leading-normal">Luxe silk and neutral tones with a focus on drape and flow.</p>
<p class="text-muted-pink/60 dark:text-muted-pink/40 text-xs mt-1 uppercase tracking-widest font-bold">Uploaded 2 days ago</p>
<!-- ButtonGroup Component -->
<div class="flex flex-1 gap-3 flex-wrap py-6 justify-start">
<button class="flex min-w-[120px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-11 px-6 bg-accent-pink dark:bg-white/10 text-deep-text dark:text-white text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary hover:text-white transition-all">
<span class="truncate">Shop Dress</span>
</button>
<button class="flex min-w-[120px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-11 px-6 bg-accent-pink dark:bg-white/10 text-deep-text dark:text-white text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary hover:text-white transition-all">
<span class="truncate">Shop Hijab</span>
</button>
<button class="flex min-w-[120px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-11 px-6 bg-accent-pink dark:bg-white/10 text-deep-text dark:text-white text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary hover:text-white transition-all">
<span class="truncate">Shop Accessories</span>
</button>
</div>
</div>
</div>
<!-- Outfit Card 2 -->
<div class="flex flex-col gap-6 group">
<div class="w-full bg-center bg-no-repeat aspect-[3/4] bg-cover rounded-xl shadow-lg ring-1 ring-black/5 overflow-hidden transition-transform duration-500 group-hover:scale-[1.02]" data-alt="Emerald velvet evening ensemble for modest fashion" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuBuVQBSPp2G1D0BwdjWNigqQz_uohPzp5CqjLcHmpGuFADk1fZ5dDAB29yLjEbETM94jxTLWYVyEGT6fDYan2vKlVg8BOYH37y72G2uOXwfgpsxapaZM6T7BcRs2gf9R1xFkpvgn1rJtGNRyVA5z_ZbPqsdZvbGwg2gqUkZQxTTl1XkWVSBn_q62Yv2OzXJ_9hKPq-PyCIfjm_d_DOVsGU--hGXwqVXeKBQrA-iSUlRYxHb_FgZBBv2HeCKHqdKKfDRSALKFP4f0Wad");'>
</div>
<div class="px-2">
<h3 class="text-deep-text dark:text-white text-2xl font-bold leading-normal font-display">Evening Grace Ensemble</h3>
<p class="text-muted-pink dark:text-muted-pink/80 text-base font-normal leading-normal">Deep emerald velvet paired with delicate chiffon layers.</p>
<p class="text-muted-pink/60 dark:text-muted-pink/40 text-xs mt-1 uppercase tracking-widest font-bold">Uploaded 5 days ago</p>
<!-- ButtonGroup Component -->
<div class="flex flex-1 gap-3 flex-wrap py-6 justify-start">
<button class="flex min-w-[120px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-11 px-6 bg-accent-pink dark:bg-white/10 text-deep-text dark:text-white text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary hover:text-white transition-all">
<span class="truncate">Shop Dress</span>
</button>
<button class="flex min-w-[120px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-11 px-6 bg-accent-pink dark:bg-white/10 text-deep-text dark:text-white text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary hover:text-white transition-all">
<span class="truncate">Shop Shoes</span>
</button>
<button class="flex min-w-[120px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-11 px-6 bg-accent-pink dark:bg-white/10 text-deep-text dark:text-white text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary hover:text-white transition-all">
<span class="truncate">Shop Hijab</span>
</button>
</div>
</div>
</div>
<!-- Outfit Card 3 -->
<div class="flex flex-col gap-6 group">
<div class="w-full bg-center bg-no-repeat aspect-[3/4] bg-cover rounded-xl shadow-lg ring-1 ring-black/5 overflow-hidden transition-transform duration-500 group-hover:scale-[1.02]" data-alt="Modern street style with modest layering" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuB6Uq2yN0iJyTl0hbYjeNV_-SoqHiyTanQM3qMNxfZeQLzt6y6bbv6gA0KR5QZtHjK41n65XCrg-JjlOkaUFG90TMZISEmNGMzo6LlA6biFiV9vY9s3wvFLpQ2qQKJ7_vgZi1jtReIaYPCArQuWiQcPtV2Q7_J9dw4TanD7MQAQDvD6wwDX5kAT6253s_FgSjJlBPC4ZmO9yVjuyoIWRA7TZDZd1isW9ivC4fGxDmSD2MzV4sLj4hWBvy14AzzEkUEgcU08C-C3Q1Gt");'>
</div>
<div class="px-2">
<h3 class="text-deep-text dark:text-white text-2xl font-bold leading-normal font-display">Modern Earth Tones</h3>
<p class="text-muted-pink dark:text-muted-pink/80 text-base font-normal leading-normal">Contemporary layering using terracota and sand palettes.</p>
<p class="text-muted-pink/60 dark:text-muted-pink/40 text-xs mt-1 uppercase tracking-widest font-bold">Uploaded 1 week ago</p>
<div class="flex flex-1 gap-3 flex-wrap py-6 justify-start">
<button class="flex min-w-[120px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-11 px-6 bg-accent-pink dark:bg-white/10 text-deep-text dark:text-white text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary hover:text-white transition-all">
<span class="truncate">Shop Coat</span>
</button>
<button class="flex min-w-[120px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-11 px-6 bg-accent-pink dark:bg-white/10 text-deep-text dark:text-white text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary hover:text-white transition-all">
<span class="truncate">Shop Pants</span>
</button>
<button class="flex min-w-[120px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-11 px-6 bg-accent-pink dark:bg-white/10 text-deep-text dark:text-white text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary hover:text-white transition-all">
<span class="truncate">Shop Boots</span>
</button>
</div>
</div>
</div>
<!-- Outfit Card 4 -->
<div class="flex flex-col gap-6 group">
<div class="w-full bg-center bg-no-repeat aspect-[3/4] bg-cover rounded-xl shadow-lg ring-1 ring-black/5 overflow-hidden transition-transform duration-500 group-hover:scale-[1.02]" data-alt="Linen summer modest outfit with wide sleeves" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuDYZhZk13zNLZkX_4neI47UsrcEhG-CdWNJKRAnMMTZwN83EttS8G_rRmu-4qdpj2jhfe2QgkE0ZZRn8XJU0nvBA8mB-vz3CV4n7E26ZnVhUlOVAGZ_4rpK8_I-abpgwfyZk8qzxI5WU7qBgSrPKeJIj9OIaqbLVdvHugOhPR5iI6qgivp203yPkpYlcEDU2zZY7wER3VT15KqUOF8HVDxuzJRlq3vDzRzhIs5vauleP72513U9CjAutJaHgDubdsUOjs0tXzMJ2ke6");'>
</div>
<div class="px-2">
<h3 class="text-deep-text dark:text-white text-2xl font-bold leading-normal font-display">Summer Breeze Linen</h3>
<p class="text-muted-pink dark:text-muted-pink/80 text-base font-normal leading-normal">Breathable linen fabric in a sophisticated oyster shade.</p>
<p class="text-muted-pink/60 dark:text-muted-pink/40 text-xs mt-1 uppercase tracking-widest font-bold">Uploaded 2 weeks ago</p>
<div class="flex flex-1 gap-3 flex-wrap py-6 justify-start">
<button class="flex min-w-[120px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-11 px-6 bg-accent-pink dark:bg-white/10 text-deep-text dark:text-white text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary hover:text-white transition-all">
<span class="truncate">Shop Abaya</span>
</button>
<button class="flex min-w-[120px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-11 px-6 bg-accent-pink dark:bg-white/10 text-deep-text dark:text-white text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary hover:text-white transition-all">
<span class="truncate">Shop Sandal</span>
</button>
<button class="flex min-w-[120px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-11 px-6 bg-accent-pink dark:bg-white/10 text-deep-text dark:text-white text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary hover:text-white transition-all">
<span class="truncate">Shop Bag</span>
</button>
</div>
</div>
</div>
</div>
<div class="mt-20 text-center pb-20 border-t border-accent-pink dark:border-white/10 pt-10">
<div class="flex justify-center gap-6 mb-4 text-muted-pink">
<span class="material-symbols-outlined cursor-pointer hover:text-primary transition-colors">brand_family</span>
<span class="material-symbols-outlined cursor-pointer hover:text-primary transition-colors">loyalty</span>
<span class="material-symbols-outlined cursor-pointer hover:text-primary transition-colors">favorite</span>
</div>
<p class="text-muted-pink text-sm">© 2024 Premium Outfit Hub • Editorial Modest Fashion</p>
</div>
</div>
</main>
</div>
</div>
</body></html>

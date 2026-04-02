<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TRED | Affordable Fashion</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: { sans: ['Inter', 'sans-serif'] },
                    colors: { brand: '#FF3366' } // A vibrant, youthful pink/red
                }
            }
        }
    </script>
    <style>
        /* Hide scrollbar for category pills but keep functionality */
        .no-scrollbar::-webkit-scrollbar { display: none; }
        .no-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
</head>
<body class="bg-gray-50 text-gray-900 pb-20 md:pb-0">

    <div class="bg-black text-white text-xs text-center py-2 font-semibold uppercase tracking-wider">
        Free shipping on orders over ₹499
    </div>

    <header class="bg-white sticky top-0 z-50 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
            <button class="md:hidden text-gray-600">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
            </button>
            <h1 class="text-2xl font-extrabold tracking-tighter">TRED.</h1>
            <div class="flex items-center gap-4">
                <svg class="w-6 h-6 text-gray-600 cursor-pointer hidden md:block" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                <div class="relative cursor-pointer">
                    <svg class="w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"></path></svg>
                    <span class="absolute -top-1 -right-1 bg-brand text-white text-[10px] font-bold w-4 h-4 rounded-full flex items-center justify-center">2</span>
                </div>
            </div>
        </div>
    </header>

    <section class="relative w-full h-[60vh] bg-gray-200">
        <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?ixlib=rb-4.0.3&auto=format&fit=crop&w=1000&q=80" alt="Fashion Model" class="w-full h-full object-cover object-center">
        <div class="absolute inset-0 bg-black bg-opacity-30 flex flex-col justify-end p-6 md:p-12 pb-12">
            <span class="text-white text-sm font-bold uppercase tracking-widest mb-2 drop-shadow-md">New Drops</span>
            <h2 class="text-white text-4xl md:text-6xl font-extrabold leading-tight mb-4 drop-shadow-lg">Look expensive.<br>Pay less.</h2>
            <button class="bg-brand hover:bg-pink-600 text-white font-bold py-3 px-8 rounded-none w-max transition-colors">SHOP WOMEN</button>
        </div>
    </section>

    <section class="max-w-7xl mx-auto px-4 py-6">
        <div class="flex space-x-3 overflow-x-auto no-scrollbar pb-2">
            <button class="bg-black text-white px-5 py-2 text-sm font-semibold whitespace-nowrap rounded-full shadow-md">All</button>
            <button class="bg-white border border-gray-300 text-gray-700 px-5 py-2 text-sm font-semibold whitespace-nowrap rounded-full hover:border-black">Men</button>
            <button class="bg-white border border-gray-300 text-gray-700 px-5 py-2 text-sm font-semibold whitespace-nowrap rounded-full hover:border-black">Women</button>
            <button class="bg-white border border-gray-300 text-gray-700 px-5 py-2 text-sm font-semibold whitespace-nowrap rounded-full hover:border-black">Teens</button>
            <button class="bg-white border border-gray-300 text-gray-700 px-5 py-2 text-sm font-semibold whitespace-nowrap rounded-full hover:border-black">Accessories</button>
        </div>
    </section>

    <section class="max-w-7xl mx-auto px-4 pb-12">
        <div class="flex justify-between items-end mb-6">
            <h3 class="text-2xl font-bold">Trending ₹499 & Under</h3>
            <a href="#" class="text-sm font-semibold underline text-gray-500">View All</a>
        </div>
        
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
            
            <div class="group relative flex flex-col gap-2 cursor-pointer">
                <div class="relative aspect-[3/4] w-full overflow-hidden bg-gray-100">
                    <span class="absolute top-2 left-2 z-10 bg-white text-black text-[10px] font-bold px-2 py-1 uppercase tracking-wider">New</span>
                    <img src="https://images.unsplash.com/photo-1576566588028-4147f3842f27?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80" alt="Graphic Tee" class="object-cover w-full h-full transition-transform duration-500 group-hover:scale-105">
                </div>
                <div class="flex justify-between items-start pt-1">
                    <div class="flex flex-col">
                        <h3 class="text-sm font-medium text-gray-900">Oversized Graphic Tee</h3>
                        <div class="flex items-center gap-2 mt-1">
                            <span class="text-sm font-bold text-gray-900">₹299</span>
                            <span class="text-xs text-gray-500 line-through">₹599</span>
                        </div>
                    </div>
                </div>
                <button class="w-full border border-black text-black py-2 text-sm font-bold mt-2 hover:bg-black hover:text-white transition-colors md:hidden">Add to Bag</button>
            </div>

            <div class="group relative flex flex-col gap-2 cursor-pointer">
                <div class="relative aspect-[3/4] w-full overflow-hidden bg-gray-100">
                    <span class="absolute top-2 left-2 z-10 bg-brand text-white text-[10px] font-bold px-2 py-1 uppercase tracking-wider">40% OFF</span>
                    <img src="https://images.unsplash.com/photo-1624378439575-d8705ad7ae80?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80" alt="Cargo Pants" class="object-cover w-full h-full transition-transform duration-500 group-hover:scale-105">
                </div>
                <div class="flex justify-between items-start pt-1">
                    <div class="flex flex-col">
                        <h3 class="text-sm font-medium text-gray-900">Streetwear Parachute Pants</h3>
                        <div class="flex items-center gap-2 mt-1">
                            <span class="text-sm font-bold text-gray-900">₹499</span>
                            <span class="text-xs text-gray-500 line-through">₹899</span>
                        </div>
                    </div>
                </div>
                <button class="w-full border border-black text-black py-2 text-sm font-bold mt-2 hover:bg-black hover:text-white transition-colors md:hidden">Add to Bag</button>
            </div>

            <div class="group relative flex flex-col gap-2 cursor-pointer">
                <div class="relative aspect-[3/4] w-full overflow-hidden bg-gray-100">
                    <img src="https://images.unsplash.com/photo-1550614000-4b95d4edfa21?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80" alt="Jacket" class="object-cover w-full h-full transition-transform duration-500 group-hover:scale-105">
                </div>
                <div class="flex justify-between items-start pt-1">
                    <div class="flex flex-col">
                        <h3 class="text-sm font-medium text-gray-900">Crop Denim Jacket</h3>
                        <div class="flex items-center gap-2 mt-1">
                            <span class="text-sm font-bold text-gray-900">₹450</span>
                        </div>
                    </div>
                </div>
                <button class="w-full border border-black text-black py-2 text-sm font-bold mt-2 hover:bg-black hover:text-white transition-colors md:hidden">Add to Bag</button>
            </div>

            <div class="group relative flex flex-col gap-2 cursor-pointer hidden md:flex">
                <div class="relative aspect-[3/4] w-full overflow-hidden bg-gray-100">
                     <span class="absolute top-2 left-2 z-10 bg-black text-white text-[10px] font-bold px-2 py-1 uppercase tracking-wider">Selling Fast</span>
                    <img src="https://images.unsplash.com/photo-1608231387042-66d1773070a5?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80" alt="Sneakers" class="object-cover w-full h-full transition-transform duration-500 group-hover:scale-105">
                </div>
                <div class="flex justify-between items-start pt-1">
                    <div class="flex flex-col">
                        <h3 class="text-sm font-medium text-gray-900">Chunky White Sneakers</h3>
                        <div class="flex items-center gap-2 mt-1">
                            <span class="text-sm font-bold text-gray-900">₹399</span>
                            <span class="text-xs text-gray-500 line-through">₹799</span>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <div class="md:hidden fixed bottom-0 w-full bg-white border-t border-gray-200 py-3 px-6 flex justify-between items-center z-50">
        <div class="flex flex-col items-center text-brand">
            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M10.707 2.293a1 1 0 00-1.414 0l-7 7a1 1 0 001.414 1.414L4 10.414V17a1 1 0 001 1h2a1 1 0 001-1v-2a1 1 0 011-1h2a1 1 0 011 1v2a1 1 0 001 1h2a1 1 0 001-1v-6.586l.293.293a1 1 0 001.414-1.414l-7-7z"></path></svg>
            <span class="text-[10px] font-bold mt-1">Home</span>
        </div>
        <div class="flex flex-col items-center text-gray-400 hover:text-gray-900">
             <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2V6zM14 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V6zM4 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2v-2zM14 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z"></path></svg>
            <span class="text-[10px] font-semibold mt-1">Categories</span>
        </div>
         <div class="flex flex-col items-center text-gray-400 hover:text-gray-900">
             <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path></svg>
            <span class="text-[10px] font-semibold mt-1">Profile</span>
        </div>
    </div>

</body>
</html>

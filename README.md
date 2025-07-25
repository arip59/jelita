<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hijab Collection - Premium Muslim Fashion</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #faf6f2;
        }
        
        .product-card:hover .product-image {
            transform: scale(1.03);
            transition: transform 0.3s ease;
        }
        
        .badge {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .search-bar:focus {
            outline: none;
            box-shadow: 0 0 0 2px #d1a570;
        }
        
        .buy-button {
            transition: all 0.3s ease;
        }
        
        .buy-button:hover {
            background-color: #92400e;
            transform: translateY(-2px);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="sticky top-0 z-50 bg-white shadow-sm">
        <div class="container mx-auto px-4 py-3 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <i class="fas fa-hijab text-2xl text-amber-700"></i>
                <h1 class="text-xl font-bold text-amber-800">Beauty Hijab Collection</h1>
            </div>
            <div class="flex items-center space-x-4">
                <button class="text-gray-600">
                    <i class="fas fa-search text-lg"></i>
        </div>
    </header>

    <!-- Hero Banner -->
    <div class="relative bg-gradient-to-r from-amber-100 to-amber-50 py-8 px-4">
        <div class="container mx-auto flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-6 md:mb-0 text-center">
                <h2 class="text-3xl font-bold text-amber-900 mb-2">New Collection 2025</h2>
                <p class="text-amber-800 mb-4">Premium Quality Hijabs With Modern Designs</p>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <img src="https://st2.depositphotos.com/29490188/48092/i/450/depositphotos_480921618-stock-photo-happy-young-arabian-woman-in.jpg alt="Hijab Model" class="w-70 h-100">
            </div>
        </div>
    </div>

    <!-- Products Grid -->
   <div class="grid grid-cols-2 gap-4">
            <!-- Product 1 -->
            <div class="product-card bg-white rounded-lg shadow-sm overflow-hidden">
                <div class="relative">
                    <img src="https://cdn.orderonline.id/uploads/images_6125721734427019254.png" alt="Hijab 1" class="w-full h-48 object-cover product-image">
                    <div class="absolute top-2 right-2 bg-amber-600 text-white text-xs px-2 py-1 rounded-full badge">New</div>
                </div>
                <div class="p-3">
                    <h4 class="text-sm font-medium text-gray-800 mb-1 truncate">JELITA INSTAN PASHMINA </h4>
                    <div class="flex items-center mb-1">
                        <div class="flex text-amber-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                        </div>
                        <span class="text-xs text-gray-500 ml-1">(128)</span>
                    </div>
                    <div class="flex items-center justify-between mb-2">
                        <span class="text-amber-700 font-bold">Rp 155,000</span>
                        <button class="text-amber-700">
                            <i class="fas fa-heart"></i>
                        </button>
                    </div>
                    <a href="https://luna.orderonline.id/je-JelitaInstanPashmina" class="block w-full bg-amber-700 hover:bg-amber-800 text-white text-center py-2 rounded-md text-sm font-medium buy-button">
                        Belanja Sekarang
                    </a>
                </div>
            </div>
            
            <!-- Product 2 -->
             <div class="product-card bg-white rounded-lg shadow-sm overflow-hidden">
                <div class="relative">
                    <img src="https://cdn.orderonline.id/uploads/images_5723351725468713664.png" alt="Hijab 2" class="w-full h-48 object-cover product-image">
                </div>
                <div class="p-3">
                    <h4 class="text-sm font-medium text-gray-800 mb-1 truncate">JELITA INSTAN OVAL</h4>
                    <div class="flex items-center mb-1">
                        <div class="flex text-amber-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                        </div>
                        <span class="text-xs text-gray-500 ml-1">(95)</span>
                    </div>
                    <div class="flex items-center justify-between mb-2">
                        <span class="text-amber-700 font-bold">Rp 155,000</span>
                        <button class="text-gray-400">
                            <i class="far fa-heart"></i>
                        </button>
                    </div>
                    <a href="https://luna.orderonline.id/je-JelitaInstanOval" class="block w-full bg-amber-700 hover:bg-amber-800 text-white text-center py-2 rounded-md text-sm font-medium buy-button">
                        Belanja Sekarang
                    </a>
                </div>
            </div>
            
            <!-- Product 3 -->
             <div class="product-card bg-white rounded-lg shadow-sm overflow-hidden">
                <div class="relative">
                    <img src="https://cdn.orderonline.id/uploads/images_4778081724832007411.png" alt="Hijab 2" class="w-full h-48 object-cover product-image">
                </div>
                <div class="p-3">
                    <h4 class="text-sm font-medium text-gray-800 mb-1 truncate">NEW HIJAB INSTAN JELITA </h4>
                    <div class="flex items-center mb-1">
                        <div class="flex text-amber-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                        </div>
                        <span class="text-xs text-gray-500 ml-1">(95)</span>
                    </div>
                    <div class="flex items-center justify-between mb-2">
                        <span class="text-amber-700 font-bold">Rp 155,000</span>
                        <button class="text-gray-400">
                            <i class="far fa-heart"></i>
                        </button>
                    </div>
                    <a href="https://luna.orderonline.id/je-NewHijabInstanJelita" class="block w-full bg-amber-700 hover:bg-amber-800 text-white text-center py-2 rounded-md text-sm font-medium buy-button">
                        Belanja Sekarang
                    </a>
                </div>
            </div>
            
            <!-- Product 4 -->
             <div class="product-card bg-white rounded-lg shadow-sm overflow-hidden">
                <div class="relative">
                    <img src="https://cdn.orderonline.id/uploads/images_8731451714030904172.png" alt="Hijab 2" class="w-full h-48 object-cover product-image">
                </div>
                <div class="p-3">
                    <h4 class="text-sm font-medium text-gray-800 mb-1 truncate">PASHMINA SILK INSTAN </h4>
                    <div class="flex items-center mb-1">
                        <div class="flex text-amber-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                        </div>
                        <span class="text-xs text-gray-500 ml-1">(95)</span>
                    </div>
                    <div class="flex items-center justify-between mb-2">
                        <span class="text-amber-700 font-bold">Rp 145,000</span>
                        <button class="text-gray-400">
                            <i class="far fa-heart"></i>
                        </button>
                    </div>
                    <a href="https://luna.orderonline.id/je-Pashminasilkinstan" class="block w-full bg-amber-700 hover:bg-amber-800 text-white text-center py-2 rounded-md text-sm font-medium buy-button">
                        Belanja Sekarang
                    </a>
                </div>
            </div>
            
            <!-- Product 5 -->
             <div class="product-card bg-white rounded-lg shadow-sm overflow-hidden">
                <div class="relative">
                    <img src="https://cdn.orderonline.id/uploads/images_7263681721003961648.png" alt="Hijab 2" class="w-full h-48 object-cover product-image">
                </div>
                <div class="p-3">
                    <h4 class="text-sm font-medium text-gray-800 mb-1 truncate">PASHMINA KAOS NAGITA</h4>
                    <div class="flex items-center mb-1">
                        <div class="flex text-amber-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                        </div>
                        <span class="text-xs text-gray-500 ml-1">(95)</span>
                    </div>
                    <div class="flex items-center justify-between mb-2">
                        <span class="text-amber-700 font-bold">Rp 155,000</span>
                        <button class="text-gray-400">
                            <i class="far fa-heart"></i>
                        </button>
                    </div>
                    <a href="https://luna.orderonline.id/je-PashminaKaosNagita" class="block w-full bg-amber-700 hover:bg-amber-800 text-white text-center py-2 rounded-md text-sm font-medium buy-button">
                        Belanja Sekarang
                    </a>
                </div>
            </div>
            
            <!-- Product 6 -->
             <div class="product-card bg-white rounded-lg shadow-sm overflow-hidden">
                <div class="relative">
                    <img src="https://cdn.orderonline.id/uploads/images_3608341737018775689.png" alt="Hijab 2" class="w-full h-48 object-cover product-image">
                </div>
                <div class="p-3">
                    <h4 class="text-sm font-medium text-gray-800 mb-1 truncate">PASHMINA INSTAN INNER 2IN1</h4>
                    <div class="flex items-center mb-1">
                        <div class="flex text-amber-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                        </div>
                        <span class="text-xs text-gray-500 ml-1">(95)</span>
                    </div>
                    <div class="flex items-center justify-between mb-2">
                        <span class="text-amber-700 font-bold">Rp 155,000</span>
                        <button class="text-gray-400">
                            <i class="far fa-heart"></i>
                        </button>
                    </div>
                    <a href="https://luna.orderonline.id/pashmina-instant-inner-2in-1" class="block w-full bg-amber-700 hover:bg-amber-800 text-white text-center py-2 rounded-md text-sm font-medium buy-button">
                        Belanja Sekarang
                    </a>
                </div>
            </div>
            
            <!-- Product 7 -->
             <div class="product-card bg-white rounded-lg shadow-sm overflow-hidden">
                <div class="relative">
                    <img src="https://cdn.orderonline.id/uploads/images_4787571737713621973.png" alt="Hijab 2" class="w-full h-48 object-cover product-image">
                </div>
                <div class="p-3">
                    <h4 class="text-sm font-medium text-gray-800 mb-1 truncate">NEW HIJAB INSTAN TERVIRAL</h4>
                    <div class="flex items-center mb-1">
                        <div class="flex text-amber-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                        </div>
                        <span class="text-xs text-gray-500 ml-1">(95)</span>
                    </div>
                    <div class="flex items-center justify-between mb-2">
                        <span class="text-amber-700 font-bold">Rp 135,000</span>
                        <button class="text-gray-400">
                            <i class="far fa-heart"></i>
                        </button>
                    </div>
                    <a href="https://luna.orderonline.id/new-hijab-instan-terviral" class="block w-full bg-amber-700 hover:bg-amber-800 text-white text-center py-2 rounded-md text-sm font-medium buy-button">
                        Belanja Sekarang
                    </a>
                </div>
            </div>
            
            <!-- Product 8 -->
             <div class="product-card bg-white rounded-lg shadow-sm overflow-hidden">
                <div class="relative">
                    <img src="https://cdn.orderonline.id/uploads/images_4537171751622784677.png" alt="Hijab 2" class="w-full h-48 object-cover product-image">
                </div>
                <div class="p-3">
                    <h4 class="text-sm font-medium text-gray-800 mb-1 truncate">KERUDUNG BERGO INSTAN</h4>
                    <div class="flex items-center mb-1">
                        <div class="flex text-amber-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                        </div>
                        <span class="text-xs text-gray-500 ml-1">(95)</span>
                    </div>
                    <div class="flex items-center justify-between mb-2">
                        <span class="text-amber-700 font-bold">Rp 155,000</span>
                        <button class="text-gray-400">
                            <i class="far fa-heart"></i>
                        </button>
                    </div>
                    <a href="https://luna.orderonline.id/kerudung-bergo-instan" class="block w-full bg-amber-700 hover:bg-amber-800 text-white text-center py-2 rounded-md text-sm font-medium buy-button">
                        Belanja Sekarang
                    </a>
                </div>
            </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Load More Button -->
    <div class="container mx-auto px-4 py-6 text-center">
        <button class="bg-white border border-amber-600 text-amber-600 px-6 py-2 rounded-full font-medium hover:bg-amber-50 transition duration-300">
            Load More Products
        </button>
    </div>

    <!-- Footer -->
    <footer class="bg-amber-900 text-white py-8">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
                <div>
                    <h4 class="font-bold text-lg mb-4">HijabQueen</h4>
                    <p class="text-amber-100 text-sm">Premium quality hijabs for modern Muslim women.</p>
                    <div class="flex space-x-4 mt-4">
                        <a href="#" class="text-amber-100 hover:text-white"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="text-amber-100 hover:text-white"><i class="fab fa-facebook"></i></a>
                        <a href="#" class="text-amber-100 hover:text-white"><i class="fab fa-tiktok"></i></a>
                    </div>
                </div>
                <div>
                    <h4 class="font-bold text-lg mb-4">Shop</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-amber-100 hover:text-white text-sm">All Products</a></li>
                        <li><a href="#" class="text-amber-100 hover:text-white text-sm">New Arrivals</a></li>
                        <li><a href="#" class="text-amber-100 hover:text-white text-sm">Best Sellers</a></li>
                        <li><a href="#" class="text-amber-100 hover:text-white text-sm">Sale Items</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold text-lg mb-4">Customer Service</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-amber-100 hover:text-white text-sm">Contact Us</a></li>
                        <li><a href="#" class="text-amber-100 hover:text-white text-sm">FAQs</a></li>
                        <li><a href="#" class="text-amber-100 hover:text-white text-sm">Shipping Policy</a></li>
                        <li><a href="#" class="text-amber-100 hover:text-white text-sm">Returns & Exchanges</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold text-lg mb-4">Newsletter</h4>
                    <p class="text-amber-100 text-sm mb-2">Subscribe for updates and promotions</p>
                    <div class="flex">
                        <input type="email" placeholder="Your email" class="bg-amber-800 text-white px-3 py-2 text-sm w-full rounded-l focus:outline-none">
                        <button class="bg-amber-600 px-3 rounded-r">
                            <i class="fas fa-paper-plane"></i>
                        </button>
                    </div>
                </div>
            </div>
            <div class="border-t border-amber-800 mt-8 pt-6 text-sm text-amber-200 text-center">
                <p>© 2023 HijabQueen. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Bottom Navigation -->
    <div class="fixed bottom-0 left-0 right-0 bg-white shadow-lg md:hidden">
        <div class="flex justify-around items-center py-3">
            <a href="#" class="flex flex-col items-center text-amber-700">
                <i class="fas fa-home text-lg"></i>
                <span class="text-xs mt-1">Home</span>
            </a>
            <a href="#" class="flex flex-col items-center text-gray-500">
                <i class="fas fa-search text-lg"></i>
                <span class="text-xs mt-1">Search</span>
            </a>
            <a href="#" class="flex flex-col items-center text-gray-500 relative">
                <i class="fas fa-shopping-cart text-lg"></i>
                <span class="absolute -top-1 -right-2 bg-amber-600 text-white text-xs rounded-full h-4 w-4 flex items-center justify-center">3</span>
                <span class="text-xs mt-1">Cart</span>
            </a>
            <a href="#" class="flex flex-col items-center text-gray-500">
                <i class="fas fa-user text-lg"></i>
                <span class="text-xs mt-1">Account</span>
            </a>
        </div>
    </div>

    <script>
        // Simple script to toggle favorite button
        document.querySelectorAll('.product-card button').forEach(button => {
            button.addEventListener('click', function() {
                if (this.innerHTML.includes('far fa-heart')) {
                    this.innerHTML = '<i class="fas fa-heart text-amber-700"></i>';
                } else {
                    this.innerHTML = '<i class="far fa-heart"></i>';
                }
            });
        });
    </script>
</body>
</html>

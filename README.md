# Sanjar_nfc
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FewSMM - Social Media Marketing Services</title>
    <script src="https://cdn.tailwindcss.com/3.4.16"></script>
    <script>tailwind.config={theme:{extend:{colors:{primary:'#333',secondary:'#555'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
    <style>
        :where([class^="ri-"])::before { content: "\f3c2"; }
        body {
            font-family: 'Inter', sans-serif;
        }
        .hero-section {
            background-image: url('https://readdy.ai/api/search-image?query=modern%20tech%20workspace%20with%20digital%20marketing%20tools%20and%20social%20media%20icons%2C%20dark%20gray%20and%20blue%20color%20scheme%2C%20minimalist%20design%2C%20professional%20atmosphere%2C%20abstract%20digital%20elements%2C%20suitable%20for%20web%20background%20with%20space%20for%20text%20on%20left%20side&width=1600&height=800&seq=1&orientation=landscape');
            background-size: cover;
            background-position: center right;
        }
        .hero-overlay {
            background: linear-gradient(90deg, rgba(0,0,0,0.85) 0%, rgba(0,0,0,0.7) 50%, rgba(0,0,0,0.4) 100%);
        }
        input:focus, select:focus, textarea:focus {
            outline: none;
            border-color: #555;
        }
        input[type="number"]::-webkit-inner-spin-button,
        input[type="number"]::-webkit-outer-spin-button {
            -webkit-appearance: none;
            margin: 0;
        }
        .custom-switch {
            position: relative;
            display: inline-block;
            width: 50px;
            height: 24px;
        }
        .custom-switch input {
            opacity: 0;
            width: 0;
            height: 0;
        }
        .switch-slider {
            position: absolute;
            cursor: pointer;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: #ccc;
            transition: .4s;
            border-radius: 24px;
        }
        .switch-slider:before {
            position: absolute;
            content: "";
            height: 18px;
            width: 18px;
            left: 3px;
            bottom: 3px;
            background-color: white;
            transition: .4s;
            border-radius: 50%;
        }
        input:checked + .switch-slider {
            background-color: #333;
        }
        input:checked + .switch-slider:before {
            transform: translateX(26px);
        }
    </style>
</head>
<body class="bg-gray-50 min-h-screen">
    <!-- Header -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex items-center justify-between">
            <div class="flex items-center">
                <a href="#" class="text-3xl font-['Pacifico'] text-primary">FewSMM</a>
                <nav class="hidden md:flex ml-10">
                    <a href="#" class="mx-3 text-primary font-medium hover:text-gray-600 transition">Home</a>
                    <a href="#" class="mx-3 text-gray-600 font-medium hover:text-primary transition">Services</a>
                    <a href="#" class="mx-3 text-gray-600 font-medium hover:text-primary transition">Pricing</a>
                    <a href="#" class="mx-3 text-gray-600 font-medium hover:text-primary transition">API Docs</a>
                    <a href="#" class="mx-3 text-gray-600 font-medium hover:text-primary transition">Contact</a>
                </nav>
            </div>
            <div class="flex items-center">
                <div class="mr-4 relative">
                    <button class="flex items-center text-gray-600 hover:text-primary transition">
                        <span>EN</span>
                        <div class="w-5 h-5 ml-1 flex items-center justify-center">
                            <i class="ri-arrow-down-s-line"></i>
                        </div>
                    </button>
                </div>
                <a href="#" class="px-4 py-2 mr-2 border border-primary text-primary hover:bg-primary hover:text-white transition duration-300 !rounded-button whitespace-nowrap">Log In</a>
                <a href="#" class="px-4 py-2 bg-primary text-white hover:bg-opacity-90 transition duration-300 !rounded-button whitespace-nowrap">Register</a>
                <button class="ml-4 p-2 rounded-full md:hidden">
                    <div class="w-6 h-6 flex items-center justify-center text-primary">
                        <i class="ri-menu-line ri-lg"></i>
                    </div>
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero-section relative">
        <div class="hero-overlay w-full">
            <div class="container mx-auto px-4 py-20 md:py-32 flex flex-col items-start">
                <div class="max-w-2xl text-white">
                    <h1 class="text-4xl md:text-5xl font-bold mb-6">Boost Your Social Media Presence</h1>
                    <p class="text-lg md:text-xl mb-8">FewSMM provides powerful tools to enhance your social media marketing strategy. Connect with your audience, grow your following, and maximize your online impact.</p>
                    <div class="flex flex-wrap gap-4">
                        <a href="#" class="px-6 py-3 bg-primary text-white hover:bg-opacity-90 transition duration-300 !rounded-button whitespace-nowrap">Get Started</a>
                        <a href="#" class="px-6 py-3 bg-white text-primary hover:bg-gray-100 transition duration-300 !rounded-button whitespace-nowrap">View Services</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div class="text-center p-6 rounded shadow-sm bg-gray-50">
                    <div class="text-4xl font-bold text-primary mb-2">1.2M+</div>
                    <p class="text-gray-600">Orders Completed</p>
                </div>
                <div class="text-center p-6 rounded shadow-sm bg-gray-50">
                    <div class="text-4xl font-bold text-primary mb-2">50K+</div>
                    <p class="text-gray-600">Active Users</p>
                </div>
                <div class="text-center p-6 rounded shadow-sm bg-gray-50">
                    <div class="text-4xl font-bold text-primary mb-2">99.9%</div>
                    <p class="text-gray-600">Service Uptime</p>
                </div>
                <div class="text-center p-6 rounded shadow-sm bg-gray-50">
                    <div class="text-4xl font-bold text-primary mb-2">24/7</div>
                    <p class="text-gray-600">Customer Support</p>
                </div>
            </div>
        </div>
    </section>
    <!-- Social Networks Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">Supported Social Networks</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Enhance your presence across all major social media platforms with our comprehensive suite of marketing tools.</p>
            </div>
            
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-6">
                <div class="bg-white p-6 rounded shadow-sm text-center hover:shadow-md transition">
                    <div class="w-16 h-16 mx-auto mb-4 flex items-center justify-center text-blue-500">
                        <i class="ri-telegram-fill ri-3x"></i>
                    </div>
                    <h3 class="font-semibold mb-2">Telegram</h3>
                    <p class="text-sm text-gray-600">Grow your channel subscribers and post views</p>
                </div>
                
                <div class="bg-white p-6 rounded shadow-sm text-center hover:shadow-md transition">
                    <div class="w-16 h-16 mx-auto mb-4 flex items-center justify-center text-pink-500">
                        <i class="ri-instagram-fill ri-3x"></i>
                    </div>
                    <h3 class="font-semibold mb-2">Instagram</h3>
                    <p class="text-sm text-gray-600">Increase followers, likes, and engagement</p>
                </div>
                
                <div class="bg-white p-6 rounded shadow-sm text-center hover:shadow-md transition">
                    <div class="w-16 h-16 mx-auto mb-4 flex items-center justify-center text-red-500">
                        <i class="ri-youtube-fill ri-3x"></i>
                    </div>
                    <h3 class="font-semibold mb-2">YouTube</h3>
                    <p class="text-sm text-gray-600">Boost subscribers, views, and watch time</p>
                </div>
                
                <div class="bg-white p-6 rounded shadow-sm text-center hover:shadow-md transition">
                    <div class="w-16 h-16 mx-auto mb-4 flex items-center justify-center text-black">
                        <i class="ri-tiktok-fill ri-3x"></i>
                    </div>
                    <h3 class="font-semibold mb-2">TikTok</h3>
                    <p class="text-sm text-gray-600">Increase followers, likes, and video views</p>
                </div>
                
                <div class="bg-white p-6 rounded shadow-sm text-center hover:shadow-md transition">
                    <div class="w-16 h-16 mx-auto mb-4 flex items-center justify-center text-blue-600">
                        <i class="ri-facebook-fill ri-3x"></i>
                    </div>
                    <h3 class="font-semibold mb-2">Facebook</h3>
                    <p class="text-sm text-gray-600">Grow page likes, followers, and post reach</p>
                </div>
            </div>
            
            <div class="mt-10 text-center">
                <a href="#" class="px-6 py-3 bg-primary text-white hover:bg-opacity-90 transition duration-300 !rounded-button whitespace-nowrap">View All Services</a>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">Why Choose FewSMM</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">We provide reliable, efficient, and affordable social media marketing services to help you grow your online presence.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="p-6 bg-gray-50 rounded shadow-sm">
                    <div class="w-12 h-12 mb-4 flex items-center justify-center text-primary bg-gray-200 rounded-full">
                        <i class="ri-speed-line ri-lg"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Instant Delivery</h3>
                    <p class="text-gray-600">Our automated system starts processing your orders immediately after payment confirmation.</p>
                </div>
                
                <div class="p-6 bg-gray-50 rounded shadow-sm">
                    <div class="w-12 h-12 mb-4 flex items-center justify-center text-primary bg-gray-200 rounded-full">
                        <i class="ri-secure-payment-line ri-lg"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Secure Payments</h3>
                    <p class="text-gray-600">Multiple payment options with enhanced security to protect your transactions.</p>
                </div>
                
                <div class="p-6 bg-gray-50 rounded shadow-sm">
                    <div class="w-12 h-12 mb-4 flex items-center justify-center text-primary bg-gray-200 rounded-full">
                        <i class="ri-customer-service-2-line ri-lg"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">24/7 Support</h3>
                    <p class="text-gray-600">Our dedicated support team is available around the clock to assist you with any issues.</p>
                </div>
                
                <div class="p-6 bg-gray-50 rounded shadow-sm">
                    <div class="w-12 h-12 mb-4 flex items-center justify-center text-primary bg-gray-200 rounded-full">
                        <i class="ri-api-line ri-lg"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">API Integration</h3>
                    <p class="text-gray-600">Seamlessly integrate our services into your applications with our robust API.</p>
                </div>
                
                <div class="p-6 bg-gray-50 rounded shadow-sm">
                    <div class="w-12 h-12 mb-4 flex items-center justify-center text-primary bg-gray-200 rounded-full">
                        <i class="ri-price-tag-3-line ri-lg"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Competitive Pricing</h3>
                    <p class="text-gray-600">Get the best value for your money with our affordable service packages.</p>
                </div>
                
                <div class="p-6 bg-gray-50 rounded shadow-sm">
                    <div class="w-12 h-12 mb-4 flex items-center justify-center text-primary bg-gray-200 rounded-full">
                        <i class="ri-shield-check-line ri-lg"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Quality Guarantee</h3>
                    <p class="text-gray-600">We ensure high-quality service delivery that meets your expectations.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- API Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-3xl font-bold mb-6">Powerful API Integration</h2>
                    <p class="text-gray-600 mb-6">Integrate our services directly into your applications with our robust API. Automate your social media marketing efforts and scale your business efficiently.</p>
                    
                    <div class="mb-8">
                        <div class="flex items-center mb-3">
                            <div class="w-6 h-6 mr-3 flex items-center justify-center text-green-500">
                                <i class="ri-check-line ri-lg"></i>
                            </div>
                            <span>Real-time order processing</span>
                        </div>
                        <div class="flex items-center mb-3">
                            <div class="w-6 h-6 mr-3 flex items-center justify-center text-green-500">
                                <i class="ri-check-line ri-lg"></i>
                            </div>
                            <span>Comprehensive documentation</span>
                        </div>
                        <div class="flex items-center mb-3">
                            <div class="w-6 h-6 mr-3 flex items-center justify-center text-green-500">
                                <i class="ri-check-line ri-lg"></i>
                            </div>
                            <span>Multiple programming language support</span>
                        </div>
                        <div class="flex items-center">
                            <div class="w-6 h-6 mr-3 flex items-center justify-center text-green-500">
                                <i class="ri-check-line ri-lg"></i>
                            </div>
                            <span>Secure authentication</span>
                        </div>
                    </div>
                    
                    <a href="#" class="px-6 py-3 bg-primary text-white hover:bg-opacity-90 transition duration-300 !rounded-button whitespace-nowrap">View API Documentation</a>
                </div>
                
                <div class="bg-white p-6 rounded shadow-sm">
                    <div class="mb-4 flex items-center">
                        <div class="w-3 h-3 rounded-full bg-red-500 mr-2"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-500 mr-2"></div>
                        <div class="w-3 h-3 rounded-full bg-green-500"></div>
                        <div class="ml-4 text-gray-500 text-sm">API Request Example</div>
                    </div>
                    <pre class="bg-gray-900 text-green-400 p-4 rounded overflow-x-auto text-sm">
<span class="text-blue-400">POST</span> <span class="text-yellow-400">https://api.fewsmm.uz/v1/order</span>
<span class="text-purple-400">Content-Type:</span> application/json
<span class="text-purple-400">Authorization:</span> Bearer YOUR_API_KEY
{
  <span class="text-yellow-400">"service"</span>: <span class="text-green-400">"telegram_subscribers"</span>,
  <span class="text-yellow-400">"link"</span>: <span class="text-green-400">"https://t.me/yourchannel"</span>,
  <span class="text-yellow-400">"quantity"</span>: <span class="text-blue-400">1000</span>,
  <span class="text-yellow-400">"speed"</span>: <span class="text-green-400">"medium"</span>
}</pre>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">Simple, Transparent Pricing</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Choose the plan that works best for your needs. No hidden fees, no surprises.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="border rounded shadow-sm p-8 bg-gray-50 relative">
                    <h3 class="text-xl font-bold mb-4">Starter</h3>
                    <div class="text-4xl font-bold mb-4">$19<span class="text-lg text-gray-500 font-normal">/month</span></div>
                    <p class="text-gray-600 mb-6">Perfect for individuals and small businesses just getting started.</p>
                    
                    <ul class="mb-8">
                        <li class="flex items-start mb-3">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>500 orders per month</span>
                        </li>
                        <li class="flex items-start mb-3">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>Basic API access</span>
                        </li>
                        <li class="flex items-start mb-3">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>Email support</span>
                        </li>
                        <li class="flex items-start">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>3 social platforms</span>
                        </li>
                    </ul>
                    
                    <a href="#" class="block w-full py-3 text-center bg-primary text-white hover:bg-opacity-90 transition duration-300 !rounded-button whitespace-nowrap">Get Started</a>
                </div>
                
                <div class="border rounded shadow-md p-8 bg-white relative">
                    <div class="absolute top-0 right-0 bg-primary text-white px-4 py-1 text-sm font-medium">Popular</div>
                    <h3 class="text-xl font-bold mb-4">Professional</h3>
                    <div class="text-4xl font-bold mb-4">$49<span class="text-lg text-gray-500 font-normal">/month</span></div>
                    <p class="text-gray-600 mb-6">Ideal for growing businesses with moderate social media needs.</p>
                    
                    <ul class="mb-8">
                        <li class="flex items-start mb-3">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>2,000 orders per month</span>
                        </li>
                        <li class="flex items-start mb-3">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>Full API access</span>
                        </li>
                        <li class="flex items-start mb-3">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>Priority email & chat support</span>
                        </li>
                        <li class="flex items-start mb-3">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>All social platforms</span>
                        </li>
                        <li class="flex items-start">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>Analytics dashboard</span>
                        </li>
                    </ul>
                    
                    <a href="#" class="block w-full py-3 text-center bg-primary text-white hover:bg-opacity-90 transition duration-300 !rounded-button whitespace-nowrap">Get Started</a>
                </div>
                
                <div class="border rounded shadow-sm p-8 bg-gray-50 relative">
                    <h3 class="text-xl font-bold mb-4">Enterprise</h3>
                    <div class="text-4xl font-bold mb-4">$99<span class="text-lg text-gray-500 font-normal">/month</span></div>
                    <p class="text-gray-600 mb-6">For large businesses with extensive social media marketing needs.</p>
                    
                    <ul class="mb-8">
                        <li class="flex items-start mb-3">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>Unlimited orders</span>
                        </li>
                        <li class="flex items-start mb-3">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>Premium API access</span>
                        </li>
                        <li class="flex items-start mb-3">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>24/7 dedicated support</span>
                        </li>
                        <li class="flex items-start mb-3">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>All social platforms</span>
                        </li>
                        <li class="flex items-start mb-3">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>Advanced analytics</span>
                        </li>
                        <li class="flex items-start">
                            <div class="w-6 h-6 mr-2 flex items-center justify-center text-green-500 mt-0.5">
                                <i class="ri-check-line"></i>
                            </div>
                            <span>Custom integration support</span>
                        </li>
                    </ul>
                    
                    <a href="#" class="block w-full py-3 text-center bg-primary text-white hover:bg-opacity-90 transition duration-300 !rounded-button whitespace-nowrap">Get Started</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">What Our Clients Say</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Don't just take our word for it. Here's what our customers have to say about our services.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded shadow-sm">
                    <div class="flex mb-4">
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-6">"FewSMM has been instrumental in growing my Telegram channel. Their service is fast, reliable, and the results are impressive. Highly recommended!"</p>
                    <div class="flex items-center">
                        <div class="w-10 h-10 rounded-full bg-gray-300 mr-3 flex items-center justify-center">
                            <i class="ri-user-line text-gray-600"></i>
                        </div>
                        <div>
                            <div class="font-medium">James Wilson</div>
                            <div class="text-sm text-gray-500">Digital Marketer</div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-white p-6 rounded shadow-sm">
                    <div class="flex mb-4">
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-6">"The API integration was seamless, and it has saved us countless hours of manual work. Our social media management is now fully automated thanks to FewSMM."</p>
                    <div class="flex items-center">
                        <div class="w-10 h-10 rounded-full bg-gray-300 mr-3 flex items-center justify-center">
                            <i class="ri-user-line text-gray-600"></i>
                        </div>
                        <div>
                            <div class="font-medium">Sarah Johnson</div>
                            <div class="text-sm text-gray-500">Tech Entrepreneur</div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-white p-6 rounded shadow-sm">
                    <div class="flex mb-4">
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-fill"></i>
                        </div>
                        <div class="w-5 h-5 text-yellow-400 flex items-center justify-center">
                            <i class="ri-star-half-fill"></i>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-6">"Customer support is exceptional. Whenever I've had questions or issues, they've been quick to respond and resolve them. The service quality is consistently good."</p>
                    <div class="flex items-center">
                        <div class="w-10 h-10 rounded-full bg-gray-300 mr-3 flex items-center justify-center">
                            <i class="ri-user-line text-gray-600"></i>
                        </div>
                        <div>
                            <div class="font-medium">Michael Thompson</div>
                            <div class="text-sm text-gray-500">Content Creator</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- CTA Section -->
    <section class="py-16 bg-primary">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold text-white mb-6">Ready to Boost Your Social Media Presence?</h2>
            <p class="text-white opacity-90 max-w-2xl mx-auto mb-8">Join thousands of satisfied customers who have transformed their social media marketing with FewSMM.</p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#" class="px-6 py-3 bg-white text-primary hover:bg-gray-100 transition duration-300 !rounded-button whitespace-nowrap">Create an Account</a>
                <a href="#" class="px-6 py-3 border border-white text-white hover:bg-white hover:text-primary transition duration-300 !rounded-button whitespace-nowrap">Contact Sales</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white pt-16 pb-8">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-12">
                <div>
                    <a href="#" class="text-3xl font-['Pacifico'] text-white mb-4 inline-block">FewSMM</a>
                    <p class="text-gray-400 mb-6">Your complete social media marketing solution for growing your online presence.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-primary transition">
                            <i class="ri-facebook-fill"></i>
                        </a>
                        <a href="#" class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-primary transition">
                            <i class="ri-twitter-fill"></i>
                        </a>
                        <a href="#" class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-primary transition">
                            <i class="ri-instagram-fill"></i>
                        </a>
                        <a href="#" class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-primary transition">
                            <i class="ri-telegram-fill"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Quick Links</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Home</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Services</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Pricing</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">API Documentation</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Blog</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Services</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Telegram Services</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Instagram Services</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">YouTube Services</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">TikTok Services</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Facebook Services</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Contact Us</h3>
                    <ul class="space-y-3">
                        <li class="flex">
                            <div class="w-5 h-5 mr-3 flex items-center justify-center text-gray-400">
                                <i class="ri-mail-line"></i>
                            </div>
                            <span class="text-gray-400">support@fewsmm.uz</span>
                        </li>
                        <li class="flex">
                            <div class="w-5 h-5 mr-3 flex items-center justify-center text-gray-400">
                                <i class="ri-phone-line"></i>
                            </div>
                            <span class="text-gray-400">+998 90 123 4567</span>
                        </li>
                        <li class="flex">
                            <div class="w-5 h-5 mr-3 flex items-center justify-center text-gray-400">
                                <i class="ri-map-pin-line"></i>
                            </div>
                            <span class="text-gray-400">Tashkent, Uzbekistan</span>
                        </li>
                    </ul>
                    
                    <div class="mt-6">
                        <h3 class="text-lg font-semibold mb-4">Payment Methods</h3>
                        <div class="flex space-x-3">
                            <div class="w-10 h-6 flex items-center justify-center text-gray-400">
                                <i class="ri-visa-fill ri-lg"></i>
                            </div>
                            <div class="w-10 h-6 flex items-center justify-center text-gray-400">
                                <i class="ri-mastercard-fill ri-lg"></i>
                            </div>
                            <div class="w-10 h-6 flex items-center justify-center text-gray-400">
                                <i class="ri-paypal-fill ri-lg"></i>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-800 pt-8">
                <div class="flex flex-col md:flex-row justify-between items-center">
                    <div class="text-gray-400 text-sm mb-4 md:mb-0">
                        &copy; 2025 FewSMM. All rights reserved.
                    </div>
                    <div class="flex space-x-4 text-sm text-gray-400">
                        <a href="#" class="hover:text-white transition">Terms of Service</a>
                        <a href="#" class="hover:text-white transition">Privacy Policy</a>
                        <a href="#" class="hover:text-white transition">Cookie Policy</a>
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <script id="mobileMenuScript">
        document.addEventListener('DOMContentLoaded', function() {
            const menuButton = document.querySelector('button.md\\:hidden');
            const mobileMenu = document.createElement('div');
            mobileMenu.className = 'fixed inset-0 bg-black bg-opacity-50 z-50 hidden';
            mobileMenu.innerHTML = `
                <div class="bg-white h-full w-64 p-4 transform transition-transform -translate-x-full">
                    <div class="flex justify-between items-center mb-6">
                        <a href="#" class="text-2xl font-['Pacifico'] text-primary">FewSMM</a>
                        <button class="p-2">
                            <div class="w-6 h-6 flex items-center justify-center text-primary">
                                <i class="ri-close-line ri-lg"></i>
                            </div>
                        </button>
                    </div>
                    <nav class="flex flex-col space-y-4">
                        <a href="#" class="py-2 text-primary font-medium">Home</a>
                        <a href="#" class="py-2 text-gray-600 font-medium">Services</a>
                        <a href="#" class="py-2 text-gray-600 font-medium">Pricing</a>
                        <a href="#" class="py-2 text-gray-600 font-medium">API Docs</a>
                        <a href="#" class="py-2 text-gray-600 font-medium">Contact</a>
                    </nav>
                    <div class="mt-6 pt-6 border-t">
                        <a href="#" class="block w-full py-2 text-center border border-primary text-primary mb-2 !rounded-button">Log In</a>
                        <a href="#" class="block w-full py-2 text-center bg-primary text-white !rounded-button">Register</a>
                    </div>
                </div>
            `;
            document.body.appendChild(mobileMenu);
            
            menuButton.addEventListener('click', function() {
                mobileMenu.classList.remove('hidden');
                const menuPanel = mobileMenu.querySelector('div.bg-white');
                setTimeout(() => {
                    menuPanel.classList.remove('-translate-x-full');
                }, 10);
            });
            
            const closeButton = mobileMenu.querySelector('button');
            closeButton.addEventListener('click', function() {
                const menuPanel = mobileMenu.querySelector('div.bg-white');
                menuPanel.classList.add('-translate-x-full');
                setTimeout(() => {
                    mobileMenu.classList.add('hidden');
                }, 300);
            });
            
            mobileMenu.addEventListener('click', function(e) {
                if (e.target === mobileMenu) {
                    const menuPanel = mobileMenu.querySelector('div.bg-white');
                    menuPanel.classList.add('-translate-x-full');
                    setTimeout(() => {
                        mobileMenu.classList.add('hidden');
                    }, 300);
                }
            });
        });
    </script>
</body>
</html>

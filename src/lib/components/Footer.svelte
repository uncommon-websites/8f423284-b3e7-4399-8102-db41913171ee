<script>
    const currentYear = new Date().getFullYear();
</script>

<footer class="bg-white pt-24 pb-12">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <!-- Top Section -->
        <div class="flex flex-col md:flex-row justify-between items-start mb-24 gap-12">
            <div class="max-w-xl">
                <div class="mb-8">
                    <!-- Logo mark -->
                     <svg width="32" height="32" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path
                            fill-rule="evenodd"
                            clip-rule="evenodd"
                            d="M5.0473 17.8386L5.69453 18.9586V18.9601H18.3003L18.9314 17.84H6.34063L6.82626 16.9993H19.4308L20.078 15.8807H7.47237L7.95715 15.0414H16.0358L16.0366 15.0429L16.0375 15.0414H20.5603L20.5612 15.0429L21.2084 13.9228L21.208 13.922L21.2084 13.9213H21.2075L14.9084 3.00677L14.9106 3.00296L14.9062 3.00296L13.6177 3.00296L5.0473 17.8386ZM14.261 4.12767L13.7751 4.96887L18.9438 13.9213H19.9139L14.261 4.12767ZM13.1286 6.08808L12.6467 6.9225L16.6749 13.9006L16.6634 13.9213H17.6511L13.1286 6.08808ZM11.9999 8.04225L8.60411 13.9213H15.3899L11.9999 8.04225ZM6.99833 3.30006C7.33866 3.10343 7.7248 2.99993 8.11786 3L2.30033 13.0776C2.10357 12.7371 2 12.3508 2 11.9575C2 11.5643 2.10357 11.178 2.30033 10.8375L6.17916 4.12006C6.37543 3.77951 6.65798 3.49669 6.99833 3.30006ZM9.08869 3H10.3816L3.43223 15.0384L2.785 13.9184L9.08869 3ZM11.3509 3H12.6424L4.56262 16.9963L3.91691 15.8777L11.3509 3ZM21.7064 13.0598C21.8988 12.7254 22 12.3463 22 11.9605C22 11.5746 21.8988 11.1956 21.7064 10.8611L17.8039 4.10233C17.6108 3.7681 17.3331 3.49057 16.9987 3.2976C16.6644 3.10463 16.2852 3.00302 15.8992 3.00296H15.8741L21.6931 13.082L21.7064 13.0598ZM17.7995 19.7994H6.17916C6.37472 20.1412 6.65692 20.4253 6.99728 20.6232C7.33763 20.8212 7.72414 20.9258 8.11786 20.9269H15.8829C16.2737 20.9261 16.6572 20.8212 16.994 20.6231C17.3309 20.4249 17.6089 20.1406 17.7995 19.7994Z"
                            fill="currentColor"
                        />
                    </svg>
                </div>
                <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                    Predict Clinical Trial Success<br />Before You Invest
                </h2>
            </div>
            <div>
                <a href="#demo" class="rounded-full bg-black px-6 py-3 text-sm font-medium text-white hover:bg-gray-800 transition-colors inline-block">
                    Schedule Demo
                </a>
            </div>
        </div>

        <!-- Links Grid -->
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8 mb-24 border-t border-gray-100 pt-16">
            <div>
                <h4 class="text-[10px] font-mono uppercase tracking-widest text-gray-500 mb-6">Platform</h4>
                <ul class="space-y-4">
                    <li><a href="#platform" class="text-xs text-gray-600 hover:text-gray-900">Natural RCTs</a></li>
                    <li><a href="#features" class="text-xs text-gray-600 hover:text-gray-900">Features</a></li>
                    <li><a href="#security" class="text-xs text-gray-600 hover:text-gray-900">Security</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-[10px] font-mono uppercase tracking-widest text-gray-500 mb-6">Company</h4>
                <ul class="space-y-4">
                    <li><a href="#about" class="text-xs text-gray-600 hover:text-gray-900">About</a></li>
                    <li><a href="#science" class="text-xs text-gray-600 hover:text-gray-900">Science</a></li>
                    <li><a href="#team" class="text-xs text-gray-600 hover:text-gray-900">Team</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-[10px] font-mono uppercase tracking-widest text-gray-500 mb-6">Legal</h4>
                <ul class="space-y-4">
                    <li><a href="#terms" class="text-xs text-gray-600 hover:text-gray-900">Terms of Use</a></li>
                    <li><a href="#privacy" class="text-xs text-gray-600 hover:text-gray-900">Privacy Policy</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-[10px] font-mono uppercase tracking-widest text-gray-500 mb-6">Contact</h4>
                <ul class="space-y-4">
                    <li><a href="#demo" class="text-xs text-gray-600 hover:text-gray-900">Schedule Demo</a></li>
                    <li><a href="#contact" class="text-xs text-gray-600 hover:text-gray-900">Contact Us</a></li>
                    <li><a href="#linkedin" class="text-xs text-gray-600 hover:text-gray-900">LinkedIn</a></li>
                    <li><a href="#publications" class="text-xs text-gray-600 hover:text-gray-900">Publications</a></li>
                </ul>
            </div>
        </div>

        <!-- Copyright -->
        <div class="text-center border-t border-gray-100 pt-8">
            <p class="text-[10px] font-mono uppercase tracking-widest text-gray-400">
                © {currentYear} Pheiron
            </p>
        </div>
    </div>
</footer>

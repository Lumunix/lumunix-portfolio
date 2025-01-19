<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->
<script>
    import { AppBar } from '@skeletonlabs/skeleton';
    import { LightSwitch } from '@skeletonlabs/skeleton';
</script>


<div class="container h-full mx-auto flex justify-center items-center p-4">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-5">
        <!-- Card 1 -->
        <div class="card space-y-2">
            <header class="card-header bg-primary text-white p-4 rounded-t-lg">
                <h2 class="text-lg font-bold">Card 1 Header</h2>
            </header>
            <section class="p-4">
                <p class="text-sm">
                    This is the content of Card 1. It can include text, images, or anything else you'd like.
                </p>
            </section>
            <footer class="card-footer bg-gray-100 p-4 rounded-b-lg text-right">
                <button class="btn btn-primary">Action</button>
            </footer>
        </div>
        <a class="card card-hover overflow-hidden" href="/elements/cards">
						<header>

						</header>
						<div class="p-4 space-y-4">
							<h6 class="h6" data-toc-ignore>Announcements</h6>
							<h3 class="h3" data-toc-ignore>Skeleton is Awesome!</h3>
							<article>
								<p>
									<!-- cspell:disable -->
									Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam aspernatur provident eveniet eligendi cumque consequatur tempore
									sint nisi sapiente. Iste beatae laboriosam iure molestias cum expedita architecto itaque quae rem.
									<!-- cspell:enable -->
								</p>
							</article>
						</div>
						<hr class="opacity-50" />
						<footer class="p-4 flex justify-start items-center space-x-4">

							<div class="flex-auto flex justify-between items-center">
								<h6 class="font-bold" data-toc-ignore>By Alex</h6>
								<small>On {new Date().toLocaleDateString()}</small>
							</div>
						</footer>
					</a>

        <!-- Card 2 -->
        <div class="card space-y-2">
            <header class="card-header bg-primary text-white p-4 rounded-t-lg">
                <h2 class="text-lg font-bold">Card 2 Header</h2>
            </header>
            <section class="p-4">
                <p class="text-sm">
                    This is the content of Card 2. Customize it as needed for your use case.
                </p>
            </section>
            <footer class="card-footer bg-gray-100 p-4 rounded-b-lg text-right">
                <button class="btn btn-primary">Action</button>
            </footer>
        </div>
    </div>
</div>



<label class="label">
	<span>Select</span>
	<select class="select">
		<option value="1">Option 1</option>
		<option value="2">Option 2</option>
		<option value="3">Option 3</option>
		<option value="4">Option 4</option>
		<option value="5">Option 5</option>
	</select>
</label>

<a href="/about">Go to About</a>

<div class="container mx-auto mt-10">
    <!-- Page Separator -->
    <hr class="border-t border-gray-300 my-6" />

    <!-- Footer -->
    <footer class="flex flex-col md:flex-row items-center justify-between space-y-4 md:space-y-0 p-4 rounded-lg">
        <!-- Footer Content -->
        <div class="text-sm">
            © 2025 Your Company. All Rights Reserved.
        </div>

        <!-- Social Media Icons -->
        <div class="flex space-x-4">
            <!-- Facebook Icon -->
            <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="text-blue-500 hover:text-blue-700">
                <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M22.675 0h-21.35C.59 0 0 .59 0 1.325v21.351C0 23.41.59 24 1.325 24H12.82V14.708h-3.333v-3.53h3.333V8.409c0-3.3 2.015-5.1 4.96-5.1 1.408 0 2.617.104 2.968.151v3.444h-2.038c-1.602 0-1.912.762-1.912 1.88v2.465h3.834l-.5 3.53h-3.334V24h6.545c.734 0 1.324-.59 1.324-1.324V1.325C24 .59 23.41 0 22.675 0z" />
                </svg>
            </a>

            <!-- GitHub Icon -->
            <a href="https://github.com" target="_blank" rel="noopener noreferrer" class="text-gray-800 hover:text-gray-900">
                <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M12 .5a11.5 11.5 0 00-3.63 22.407c.575.106.784-.247.784-.551v-2.163c-3.19.696-3.862-1.506-3.862-1.506a3.044 3.044 0 00-1.28-1.684c-1.047-.717.08-.703.08-.703a2.405 2.405 0 011.751 1.178 2.45 2.45 0 003.336.962 2.453 2.453 0 01.729-1.54c-2.547-.293-5.225-1.273-5.225-5.667a4.423 4.423 0 011.174-3.063 4.102 4.102 0 01.112-3.021s.961-.308 3.151 1.17a10.7 10.7 0 015.736 0c2.189-1.478 3.15-1.17 3.15-1.17a4.1 4.1 0 01.113 3.021 4.425 4.425 0 011.173 3.063c0 4.402-2.682 5.372-5.236 5.66.474.41.895 1.217.895 2.452v3.63c0 .305.208.66.787.55A11.502 11.502 0 0012 .5z" />
                </svg>
            </a>

            <!-- LinkedIn Icon -->
            <a href="https://linkedin.com" target="_blank" rel="noopener noreferrer" class="text-blue-700 hover:text-blue-900">
                <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M22.225 0H1.775C.794 0 0 .774 0 1.729v20.543C0 23.227.794 24 1.775 24h20.451C23.205 24 24 23.227 24 22.271V1.729C24 .774 23.205 0 22.225 0zM7.125 20.452H3.633V9h3.492v11.452zM5.375 7.518a2.026 2.026 0 110-4.053 2.026 2.026 0 010 4.053zm15.077 12.934h-3.492v-5.572c0-1.33-.026-3.044-1.855-3.044-1.857 0-2.142 1.45-2.142 2.951v5.665H9.471V9h3.357v1.561h.047c.467-.88 1.608-1.805 3.312-1.805 3.543 0 4.195 2.33 4.195 5.358v6.338z" />
                </svg>
            </a>
        </div>
    </footer>
</div>

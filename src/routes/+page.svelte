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

</div>

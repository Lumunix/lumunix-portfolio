<script>
 const pdfPath = 'DylanPoljakResume.pdf'; // Path to your PDF



</script>
<div class="container h-full mx-auto flex justify-center items-center">
  <div class="w-full md:w-2/3 lg:w-1/2 shadow-lg rounded-lg p-4">
    <h2 class="text-xl font-semibold text-center mb-4">My Resume</h2>
    <iframe
      src={pdfPath}
      class="w-full h-[1000px] border rounded-lg"
      frameborder="0"
    ></iframe>
  </div>
</div>



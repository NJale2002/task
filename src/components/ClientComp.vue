<script setup>

import imageprofil1 from '../assets/images/clients/c1.png'
import imageprofil2 from '../assets/images/clients/c2.png'
import imageprofil3 from '../assets/images/clients/c3.png'
import imageprofil4 from '../assets/images/clients/c4.png'
import imageprofil5 from '../assets/images/clients/c5.png'
import imageprofil6 from '../assets/images/clients/c6.png'
import imageprofil7 from '../assets/images/clients/c7.png'

</script>




<template>
<section id="clients" class="clients">
			<div class="section-heading text-center">
				<h2>clients</h2>
			</div>
			<div class="clients-area">
				<div class="container">
					<div class="owl-carousel owl-theme" id="client">
						<div class="item">
							<a href="#">
								<img :src="imageprofil1" alt="brand-image" />
							</a>
						</div><!--/.item-->
						<div class="item">
							<a href="#">
								<img :src="imageprofil2" alt="brand-image" />
							</a>
						</div><!--/.item-->
						<div class="item">
							<a href="#">
								<img :src="imageprofil3" alt="brand-image" />
							</a>
						</div><!--/.item-->
						<div class="item">
							<a href="#">
								<img :src="imageprofil4" alt="brand-image" />
							</a>
						</div><!--/.item-->
						<div class="item">
							<a href="#">
								<img :src="imageprofil5" alt="brand-image" />
							</a>
						</div><!--/.item-->
						<div class="item">
							<a href="#">
								<img :src="imageprofil6" alt="brand-image" />
							</a>
						</div><!--/.item-->
						<div class="item">
							<a href="#">
								<img :src="imageprofil7" alt="brand-image" />
							</a>
						</div><!--/.item-->
					</div><!--/.owl-carousel-->
				</div><!--/.container-->
			</div><!--/.clients-area-->

		</section>


</template>
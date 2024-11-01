<script setup>

import imageprofil1 from '../assets/images/portfolio/p1.jpg'
import imageprofil2 from '../assets/images/portfolio/p2.jpg'
import imageprofil3 from '../assets/images/portfolio/p3.jpg'
import imageprofil4 from '../assets/images/portfolio/p4.jpg'
import imageprofil5 from '../assets/images/portfolio/p5.jpg'

</script>



<template>

<section id="portfolio" class="portfolio">
			<div class="portfolio-details">
				<div class="section-heading text-center">
					<h2>portfolio</h2>
				</div>
				<div class="container">
					<div class="portfolio-content">
						<div class="isotope">
							<div class="row">

								<div class="col-sm-4">
									<div class="item">
										<img :src="imageprofil1" alt="portfolio image"/>
										<div class="isotope-overlay">
											<a href="#">
												ui/ux design
											</a>
										</div><!-- /.isotope-overlay -->
									</div><!-- /.item -->
									<div class="item">
										<img :src="imageprofil2" alt="portfolio image"/>
										<div class="isotope-overlay">
											<a href="#">
												ui/ux design
											</a>
										</div><!-- /.isotope-overlay -->
									</div><!-- /.item -->
								</div><!-- /.col -->

								<div class="col-sm-4">
									<div class="item">
										<img :src="imageprofil3" alt="portfolio image"/>
										<div class="isotope-overlay">
											<a href="#">
												web design
											</a>
										</div><!-- /.isotope-overlay -->
									</div><!-- /.item -->
								</div><!-- /.col -->

								<div class="col-sm-4">
									<div class="item">
										<img :src="imageprofil4" alt="portfolio image"/>
										<div class="isotope-overlay">
											<a href="#">
												web development
											</a>
										</div><!-- /.isotope-overlay -->
									</div><!-- /.item -->
									<div class="item">
										<img :src="imageprofil5" alt="portfolio image"/>
										<div class="isotope-overlay">
											<a href="#">
												web development
											</a>
										</div><!-- /.isotope-overlay -->
									</div><!-- /.item -->
								</div><!-- /.col -->
							</div><!-- /.row -->
						</div><!--/.isotope-->
					</div><!--/.gallery-content-->
				</div><!--/.container-->
			</div><!--/.portfolio-details-->

		</section>


</template>
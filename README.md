# Quem sou eu?

Sou coordenador de desenvolvimento de software experiente, com histórico comprovado na liderança de transformações ágeis e no fornecimento de soluções de software de alta qualidade. Minha experiência reside na liderança de equipes, gerenciamento de projetos e na promoção de uma cultura de colaboração e inovação. Com paixão por tecnologia e dedicação à melhoria contínua, prospero em ambientes dinâmicos onde posso causar um impacto significativo.

## Cases

<ul>
    {% for post in site.posts %}
    {% if post.categories contains "Cases" %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
    {% endif %}
    {% endfor %}
</ul>

<!-- lazily load the Swiper CSS file -->
<link rel="preload" href="https://unpkg.com/swiper@8/swiper-bundle.min.css" as="style" onload="this.onload=null;this.rel='stylesheet'" />

<!-- lazily load the Swiper JS file -->
<script defer="defer" src="https://unpkg.com/swiper@8/swiper-bundle.min.js" onload="initializeSwiperRANDOMID();"></script>

<!-- lc-needs-hard-refresh -->

<script>
    	function initializeSwiperRANDOMID(){
        const swiper = new Swiper(".mySwiper-RANDOMID", {
            slidesPerView: 1,
            grabCursor: true,
            spaceBetween: 30,
            
            pagination: {
                el: ".swiper-pagination",
                dynamicBullets: true,
            },
            breakpoints: {
                768: {
                    slidesPerView: 2,
                },
                992: {
                    slidesPerView: 3,
                },
            },
        });
    }
</script>

<style>
	.mySwiper-RANDOMID .card {max-width:21rem}
</style>

<div class="container py-6"><!-- Slider main container -->
	<div class="swiper mySwiper-RANDOMID">
		<!-- Additional required wrapper -->
		<div class="swiper-wrapper"><!-- Slides -->
			<div class="swiper-slide h-100">
				<div class="card shadow mx-auto">
					<div class="card-body">
						<div class="lc-block">
							<img class="img-fluid" src="https://images.unsplash.com/photo-1660861378355-d194175e4905?crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8Mnx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0MzUxOTV8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1080&amp;h=1080" srcset="" sizes="" width="" height="" alt="Photo by Marla Gottschalk" loading="lazy">
						</div>
						<div class="card-body">
							<div class="lc-block mb-3">
								<div editable="rich">

									<h2 class="h5">Card Title</h2>

									<p>Some quick example text to build on the card title and make up the bulk of the card's content..</p>
								</div>
							</div>
							<div class="lc-block">
								<a class="btn btn-primary" href="#" role="button">Button</a>
							</div>


						</div>
					</div>
				</div>
			</div>
			<div class="swiper-slide h-100">
				<div class="card shadow mx-auto">
					<div class="card-body">
						<div class="lc-block">
							<img class="img-fluid" src="https://images.unsplash.com/photo-1617886903355-9354bb57b5d4?crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8NHx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1080&amp;h=1080" srcset="https://images.unsplash.com/photo-1617886903355-9354bb57b5d4?crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8NHx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1080&amp;h=1080 1080w, https://images.unsplash.com/photo-1617886903355-9354bb57b5d4??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8NHx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=150 150w, https://images.unsplash.com/photo-1617886903355-9354bb57b5d4??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8NHx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=300 300w, https://images.unsplash.com/photo-1617886903355-9354bb57b5d4??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8NHx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=768 768w, https://images.unsplash.com/photo-1617886903355-9354bb57b5d4??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8NHx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1024 1024w" sizes="(max-width: 1080px) 100vw, 1080px" width="1080" height="1080" alt="Photo by Jon Tyson" loading="lazy">
						</div>
						<div class="card-body">
							<div class="lc-block mb-3">
								<div editable="rich">

									<h2 class="h5">Card Title</h2>

									<p>Some quick example text to build on the card title and make up the bulk of the card's content..</p>
								</div>
							</div>
							<div class="lc-block">
								<a class="btn btn-primary" href="#" role="button">Button</a>
							</div>


						</div>
					</div>
				</div>
			</div>
			<div class="swiper-slide h-100">
				<div class="card shadow mx-auto">
					<div class="card-body">
						<div class="lc-block">
							<img class="img-fluid" src="https://images.unsplash.com/photo-1606685544086-ce4ab1b91c21?crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8OHx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1080&amp;h=1080" srcset="https://images.unsplash.com/photo-1606685544086-ce4ab1b91c21?crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8OHx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1080&amp;h=1080 1080w, https://images.unsplash.com/photo-1606685544086-ce4ab1b91c21??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8OHx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=150 150w, https://images.unsplash.com/photo-1606685544086-ce4ab1b91c21??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8OHx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=300 300w, https://images.unsplash.com/photo-1606685544086-ce4ab1b91c21??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8OHx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=768 768w, https://images.unsplash.com/photo-1606685544086-ce4ab1b91c21??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8OHx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1024 1024w" sizes="(max-width: 1080px) 100vw, 1080px" width="1080" height="1080" alt="Photo by Vianney CAHEN" loading="lazy">
						</div>
						<div class="card-body">
							<div class="lc-block mb-3">
								<div editable="rich">

									<h2 class="h5">Card Title</h2>

									<p>Some quick example text to build on the card title and make up the bulk of the card's content..</p>
								</div>
							</div>
							<div class="lc-block">
								<a class="btn btn-primary" href="#" role="button">Button</a>
							</div>


						</div>
					</div>
				</div>
			</div>
			<div class="swiper-slide h-100">
				<div class="card shadow mx-auto">
					<div class="card-body">
						<div class="lc-block">
							<img class="img-fluid" src="https://images.unsplash.com/photo-1597489276008-79951d6be8bb?crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8N3x8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1080&amp;h=1080" srcset="https://images.unsplash.com/photo-1597489276008-79951d6be8bb?crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8N3x8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1080&amp;h=1080 1080w, https://images.unsplash.com/photo-1597489276008-79951d6be8bb??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8N3x8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=150 150w, https://images.unsplash.com/photo-1597489276008-79951d6be8bb??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8N3x8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=300 300w, https://images.unsplash.com/photo-1597489276008-79951d6be8bb??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8N3x8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=768 768w, https://images.unsplash.com/photo-1597489276008-79951d6be8bb??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8N3x8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1024 1024w" sizes="(max-width: 1080px) 100vw, 1080px" width="1080" height="1080" alt="Photo by Cherry Lin" loading="lazy">
						</div>
						<div class="card-body">
							<div class="lc-block mb-3">
								<div editable="rich">

									<h2 class="h5">Card Title</h2>

									<p>Some quick example text to build on the card title and make up the bulk of the card's content..</p>
								</div>
							</div>
							<div class="lc-block">
								<a class="btn btn-primary" href="#" role="button">Button</a>
							</div>


						</div>
					</div>
				</div>
			</div>
			<div class="swiper-slide h-100">
				<div class="card shadow mx-auto">
					<div class="card-body">
						<div class="lc-block">
							<img class="img-fluid" src="https://images.unsplash.com/photo-1594398901592-4f07a2e0b5f1?crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8OXx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1080&amp;h=1080" srcset="https://images.unsplash.com/photo-1594398901592-4f07a2e0b5f1?crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8OXx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1080&amp;h=1080 1080w, https://images.unsplash.com/photo-1594398901592-4f07a2e0b5f1??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8OXx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=150 150w, https://images.unsplash.com/photo-1594398901592-4f07a2e0b5f1??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8OXx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=300 300w, https://images.unsplash.com/photo-1594398901592-4f07a2e0b5f1??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8OXx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=768 768w, https://images.unsplash.com/photo-1594398901592-4f07a2e0b5f1??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8OXx8ZnVybml0dXJlJTIwcmVkfGVufDB8Mnx8fDE2OTE0ODcxMjF8MA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1024 1024w" sizes="(max-width: 1080px) 100vw, 1080px" width="1080" height="1080" alt="Photo by Grant Durr" loading="lazy">
						</div>
						<div class="card-body">
							<div class="lc-block mb-3">
								<div editable="rich">

									<h2 class="h5">Card Title</h2>

									<p>Some quick example text to build on the card title and make up the bulk of the card's content..</p>
								</div>
							</div>
							<div class="lc-block">
								<a class="btn btn-primary" href="#" role="button">Button</a>
							</div>


						</div>
					</div>
				</div>
			</div>
			<div class="swiper-slide h-100">
				<div class="card shadow mx-auto">
					<div class="card-body">
						<div class="lc-block">
							<img class="img-fluid" src="https://images.unsplash.com/photo-1604309225246-86ad9ff7d79f?crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8MTB8fGZ1cm5pdHVyZSUyMHJlZHxlbnwwfDJ8fHwxNjkxNDg3MTIxfDA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1080&amp;h=1080" srcset="https://images.unsplash.com/photo-1604309225246-86ad9ff7d79f?crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8MTB8fGZ1cm5pdHVyZSUyMHJlZHxlbnwwfDJ8fHwxNjkxNDg3MTIxfDA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1080&amp;h=1080 1080w, https://images.unsplash.com/photo-1604309225246-86ad9ff7d79f??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8MTB8fGZ1cm5pdHVyZSUyMHJlZHxlbnwwfDJ8fHwxNjkxNDg3MTIxfDA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=150 150w, https://images.unsplash.com/photo-1604309225246-86ad9ff7d79f??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8MTB8fGZ1cm5pdHVyZSUyMHJlZHxlbnwwfDJ8fHwxNjkxNDg3MTIxfDA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=300 300w, https://images.unsplash.com/photo-1604309225246-86ad9ff7d79f??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8MTB8fGZ1cm5pdHVyZSUyMHJlZHxlbnwwfDJ8fHwxNjkxNDg3MTIxfDA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=768 768w, https://images.unsplash.com/photo-1604309225246-86ad9ff7d79f??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8MTB8fGZ1cm5pdHVyZSUyMHJlZHxlbnwwfDJ8fHwxNjkxNDg3MTIxfDA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1024 1024w" sizes="(max-width: 1080px) 100vw, 1080px" width="1080" height="1080" alt="Photo by willy wo" loading="lazy">
						</div>
						<div class="card-body">
							<div class="lc-block mb-3">
								<div editable="rich">

									<h2 class="h5">Card Title</h2>

									<p>Some quick example text to build on the card title and make up the bulk of the card's content..</p>
								</div>
							</div>
							<div class="lc-block">
								<a class="btn btn-primary" href="#" role="button">Button</a>
							</div>


						</div>
					</div>
				</div>
			</div>
			<div class="swiper-slide h-100">
				<div class="card shadow mx-auto">
					<div class="card-body">
						<div class="lc-block">
							<img class="img-fluid" src="https://images.unsplash.com/photo-1587117238257-8cacadca6ae4?crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8MTd8fGZ1cm5pdHVyZSUyMHJlZHxlbnwwfDJ8fHwxNjkxNDM1MjA3fDA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1080&amp;h=1080" srcset="https://images.unsplash.com/photo-1587117238257-8cacadca6ae4?crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8MTd8fGZ1cm5pdHVyZSUyMHJlZHxlbnwwfDJ8fHwxNjkxNDM1MjA3fDA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1080&amp;h=1080 1080w, https://images.unsplash.com/photo-1587117238257-8cacadca6ae4??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8MTd8fGZ1cm5pdHVyZSUyMHJlZHxlbnwwfDJ8fHwxNjkxNDM1MjA3fDA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=150 150w, https://images.unsplash.com/photo-1587117238257-8cacadca6ae4??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8MTd8fGZ1cm5pdHVyZSUyMHJlZHxlbnwwfDJ8fHwxNjkxNDM1MjA3fDA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=300 300w, https://images.unsplash.com/photo-1587117238257-8cacadca6ae4??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8MTd8fGZ1cm5pdHVyZSUyMHJlZHxlbnwwfDJ8fHwxNjkxNDM1MjA3fDA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=768 768w, https://images.unsplash.com/photo-1587117238257-8cacadca6ae4??crop=entropy&amp;cs=tinysrgb&amp;fit=crop&amp;fm=jpg&amp;ixid=M3wzNzg0fDB8MXxzZWFyY2h8MTd8fGZ1cm5pdHVyZSUyMHJlZHxlbnwwfDJ8fHwxNjkxNDM1MjA3fDA&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=1024 1024w" sizes="(max-width: 1080px) 100vw, 1080px" width="1080" height="1080" alt="Photo by Dayana Brooke" loading="lazy">
						</div>
						<div class="card-body">
							<div class="lc-block mb-3">
								<div editable="rich">

									<h2 class="h5">Card Title</h2>

									<p>Some quick example text to build on the card title and make up the bulk of the card's content..</p>
								</div>
							</div>
							<div class="lc-block">
								<a class="btn btn-primary" href="#" role="button">Button</a>
							</div>


						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- If we need pagination -->
		<div class="swiper-pagination position-relative pt-5 bottom-0"></div>
	</div>
</div>

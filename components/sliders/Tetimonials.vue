<template>
    <div class="reviews-1-wrapper">
        <Swiper
            :modules="[SwiperAutoplay, SwiperEffectCreative]"
            :slides-per-view="1"
            :loop="true"
            :autoplay="{
                delay: 8000,
                disableOnInteraction: true
            }"
            :breakpoints="{
                600:{ slidesPerView:2 },
                920:{ slidesPerView:3 },
            }"
        >
            <SwiperSlide>
                <div class="review-1 bg--white-100 block-shadow r-08">
                    <!-- Quote Icon -->
                    <div class="review-ico ico-65"><span class="flaticon-quote"></span></div>
                    <!-- Text -->
                    <div class="review-txt">
                        <!-- Text -->
                        <p>Desde que comencé a trabajar con Nova Ignis, mi presencia en redes sociales se disparó. Sus estrategias hicieron que mi marca generara conversaciones a nivel mundial, conectándome con audiencias que nunca imaginé alcanzar.</p>
                        <!-- Author -->
                        <div class="author-data clearfix">
                            <!-- Avatar -->
                            <div class="review-avatar">
                                <img src="/assets/images/review-author-1.jpg" alt="review-avatar" />
                            </div>
                            <!-- Data -->
                            <div class="review-author">
                                <h6 class="s-18 w-700">Takashi Sato</h6>
                                <p class="p-sm">Aumento Global de Conexiones</p>
                            </div>
                        </div>
                        <!-- End Author -->
                    </div>
                    <!-- End Text -->
                </div>
            </SwiperSlide>
            <SwiperSlide>
                <div class="review-1 bg--white-100 block-shadow r-08">
                    <!-- Quote Icon -->
                    <div class="review-ico ico-65"><span class="flaticon-quote"></span></div>
                    <!-- Text -->
                    <div class="review-txt">
                        <!-- Text -->
                        <p>Mi sitio web era obsoleto y no reflejaba la esencia de mi marca. Gracias a Nova Ignis, ahora tengo una plataforma digital moderna y eficaz que encanta a mis visitantes y convierte prospectos en clientes leales.</p>
                        <!-- Author -->
                        <div class="author-data clearfix">
                            <!-- Avatar -->
                            <div class="review-avatar">
                                <img src="/assets/images/review-author-2.jpg" alt="review-avatar" />
                            </div>
                            <!-- Data -->
                            <div class="review-author">
                                <h6 class="s-18 w-700">Clara Martínez</h6>
                                <p class="p-sm">Transformación Web Inigualable</p>
                            </div>
                        </div>
                        <!-- End Author -->
                    </div>
                    <!-- End Text -->
                </div>
            </SwiperSlide>
            <SwiperSlide>
                <div class="review-1 bg--white-100 block-shadow r-08">
                    <!-- Quote Icon -->
                    <div class="review-ico ico-65"><span class="flaticon-quote"></span></div>
                    <!-- Text -->
                    <div class="review-txt">
                        <!-- Text -->
                        <p>Al asociarme con Nova Ignis, redescubrí lo que significa tener un sitio web poderoso. Su enfoque y dedicación resultaron en una experiencia digital que ha superado todas mis expectativas.</p>
                        <!-- Author -->
                        <div class="author-data clearfix">
                            <!-- Avatar -->
                            <div class="review-avatar">
                                <img src="/assets/images/review-author-3.jpg" alt="review-avatar" />
                            </div>
                            <!-- Data -->
                            <div class="review-author">
                                <h6 class="s-18 w-700">Carlos Mendoza</h6>
                                <p class="p-sm">Más Allá de los Límites</p>
                            </div>
                        </div>
                        <!-- End Author -->
                    </div>
                    <!-- End Text -->
                </div>
            </SwiperSlide>
            <SwiperSlide>
                <div class="review-1 bg--white-100 block-shadow r-08">
                    <!-- Quote Icon -->
                    <div class="review-ico ico-65"><span class="flaticon-quote"></span></div>
                    <!-- Text -->
                    <div class="review-txt">
                        <!-- Text -->
                        <p>Como propietaria de un restaurante, la presentación es crucial. Nova Ignis diseñó un menú para mi negocio que no solo es visualmente atractivo, sino que seduce a los clientes desde el primer vistazo.</p>
                        <!-- Author -->
                        <div class="author-data clearfix">
                            <!-- Avatar -->
                            <div class="review-avatar">
                                <img src="/assets/images/review-author-4.jpg" alt="review-avatar" />
                            </div>
                            <!-- Data -->
                            <div class="review-author">
                                <h6 class="s-18 w-700">Valentina Bianchi</h6>
                                <p class="p-sm">Una Presentación Culminante</p>
                            </div>
                        </div>
                        <!-- End Author -->
                    </div>
                    <!-- End Text -->
                </div>
            </SwiperSlide>
            <SwiperSlide>
                <div class="review-1 bg--white-100 block-shadow r-08">
                    <!-- Quote Icon -->
                    <div class="review-ico ico-65"><span class="flaticon-quote"></span></div>
                    <!-- Text -->
                    <div class="review-txt">
                        <!-- Text -->
                        <p>Con Nova Ignis, mi sitio web se convirtió en algo más que una simple tarjeta de presentación en línea. Ahora es una herramienta dinámica que atrae y retiene a mi audiencia como nunca antes.</p>
                        <!-- Author -->
                        <div class="author-data clearfix">
                            <!-- Avatar -->
                            <div class="review-avatar">
                                <img src="/assets/images/review-author-5.jpg" alt="review-avatar" />
                            </div>
                            <!-- Data -->
                            <div class="review-author">
                                <h6 class="s-18 w-700">Lucy Cheung</h6>
                                <p class="p-sm">Web Innovadora y Dinámica</p>
                            </div>
                        </div>
                        <!-- End Author -->
                    </div>
                    <!-- End Text -->
                </div>
            </SwiperSlide>
            <SwiperSlide>
                <div class="review-1 bg--white-100 block-shadow r-08">
                    <!-- Quote Icon -->
                    <div class="review-ico ico-65"><span class="flaticon-quote"></span></div>
                    <!-- Text -->
                    <div class="review-txt">
                        <!-- Text -->
                        <p>Nuestro alcance en redes sociales era limitado hasta que encontramos a Nova Ignis. Ahora, nuestra audiencia ha crecido exponencialmente y nuestra marca es el centro de muchas discusiones en línea.</p>
                        <!-- Author -->
                        <div class="author-data clearfix">
                            <!-- Avatar -->
                            <div class="review-avatar">
                                <img src="/assets/images/review-author-6.jpg" alt="review-avatar" />
                            </div>
                            <!-- Data -->
                            <div class="review-author">
                                <h6 class="s-18 w-700">Gabriela Silva</h6>
                                <p class="p-sm">Impacto Social Aumentado</p>
                            </div>
                        </div>
                        <!-- End Author -->
                    </div>
                    <!-- End Text -->
                </div>
            </SwiperSlide>
            <SwiperSlide>
                <div class="review-1 bg--white-100 block-shadow r-08">
                    <!-- Quote Icon -->
                    <div class="review-ico ico-65"><span class="flaticon-quote"></span></div>
                    <!-- Text -->
                    <div class="review-txt">
                        <!-- Text -->
                        <p>Lo que más me impresionó de Nova Ignis fue su proceso colaborativo. Desde la idea inicial hasta el producto final, me sentí incluido y valorado, y el resultado superó todas mis expectativas.</p>
                        <!-- Author -->
                        <div class="author-data clearfix">
                            <!-- Avatar -->
                            <div class="review-avatar">
                                <img src="/assets/images/review-author-7.jpg" alt="review-avatar" />
                            </div>
                            <!-- Data -->
                            <div class="review-author">
                                <h6 class="s-18 w-700">Stefano Romano</h6>
                                <p class="p-sm">Equipo de Confianza</p>
                            </div>
                        </div>
                        <!-- End Author -->
                    </div>
                    <!-- End Text -->
                </div>
            </SwiperSlide>
            <SwiperSlide>
                <div class="review-1 bg--white-100 block-shadow r-08">
                    <!-- Quote Icon -->
                    <div class="review-ico ico-65"><span class="flaticon-quote"></span></div>
                    <!-- Text -->
                    <div class="review-txt">
                        <!-- Text -->
                        <p>El servicio de Naming y Logotipos de Nova Ignis es insuperable. Gracias a ellos, mi marca tiene ahora un sello distintivo que se recuerda y destaca en cualquier lugar.</p>
                        <!-- Author -->
                        <div class="author-data clearfix">
                            <!-- Avatar -->
                            <div class="review-avatar">
                                <img src="/assets/images/review-author-8.jpg" alt="review-avatar" />
                            </div>
                            <!-- Data -->
                            <div class="review-author">
                                <h6 class="s-18 w-700">Deepak Patel</h6>
                                <p class="p-sm">Sello Distintivo</p>
                            </div>
                        </div>
                        <!-- End Author -->
                    </div>
                    <!-- End Text -->
                </div>
            </SwiperSlide>
        </Swiper>
    </div>
</template>

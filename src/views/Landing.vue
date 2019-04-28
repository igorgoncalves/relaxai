<template>
    <div>

        <div class="position-relative">
            <!-- shape Hero -->
            <section class="section-shaped my-0">
                <div class="shape shape-style-1 shape-default shape-skew">
                    <span></span>                    
                    <span></span>
                    <span></span>
                </div>
                <div class="container shape-container d-flex">
                    <div class="col px-0">
                        <div class="row">
                            <div class="col-lg-6">
                                <h1 class="display-3  text-white">Quer um desconto para você se cuidar hoje?
                                    <span>Produtos, serviços e informações para sua saúde mental</span>
                                </h1>
                                <p class="lead  text-white">
                                    Acesse o Relaxaí agora e comece a resgatar descontos em serviços psicologia, Yoga, Reiki e muitos outros.
                                </p>
                                <div class="btn-wrapper">
                                    <span></span>
                                    <span></span>
                                    <!-- <base-button tag="a"
                                                 href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
                                                 class="mb-3 mb-sm-0"
                                                 type="info"
                                                 icon="fa fa-code">
                                        Cadastro
                                    </base-button>
                                    <base-button tag="a"
                                                 href="https://www.creative-tim.com/product/argon-design-system"
                                                 class="mb-3 mb-sm-0"
                                                 type="white"
                                                 icon="ni ni-cloud-download-95">
                                        Ver catálogo
                                    </base-button> -->
                                    </div>
                            </div>
                            <div class="col-lg-6" color="#ffffff">
                                <card shadow class="shadow-lg--hover">
                                    <form  method="POST" :action="cadastrar">                                    
                                    <h6 class="text-primary text-uppercase">Quer saber mais? Preencha os campos abaixo</h6>
                                    <label  for="email">Email</label>
                                    <base-input v-model="email" name="email" placeholder="Adicione seu email" />
                                    <span></span>
                                        
                                    <label for="servicos">Serviços do seu interesse</label>
                                    <textarea v-model="texto" class="form-control " name="servicos" rows="4"
                                              cols="80" placeholder="Que tipo de serviços você procura?" />
                                    <base-button tag="button"
                                                 class="mb-12 mb-sm-0 btn-cadastrar"
                                                 type="info"
                                                 v-on:click="cadastrar"
                                                 >
                                        Cadastrar
                                    </base-button>
                                    </form >
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- 1st Hero Variation -->
        </div>
        <section class="section section-lg pt-lg-0 mt--200">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-check-bold" type="primary" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-primary text-uppercase">Catálogo de psicólogos</h6>
                                    <p class="description mt-3">Conheça psicólogos na sua região, saiba o que seus pacientes pensam dele e conheça sua abordagem.</p>
                                    <!-- <div>
                                        <badge type="primary" rounded>design</badge>
                                        <badge type="primary" rounded>system</badge>
                                        <badge type="primary" rounded>creative</badge>
                                    </div> -->
                                    <!-- <base-button tag="a" href="#" type="primary" class="mt-4">
                                        Learn more
                                    </base-button> -->
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-money-coins" type="success" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-success text-uppercase">Ganhe vários descontos</h6>
                                    <p class="description mt-3">Ganhe descontos exclusivos dos nossos paceiros em diversas atividades que vão contribuir com o desenvolvimento da sua saúde mental.</p>
                                    <!-- <div>
                                        <badge type="success" rounded>business</badge>
                                        <badge type="success" rounded>vision</badge>
                                        <badge type="success" rounded>success</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="success" class="mt-4">
                                        Learn more
                                    </base-button> -->
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-bullet-list-67" type="warning" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-warning text-uppercase">Conheça novas atividades</h6>
                                    <p class="description mt-3">Descubra uma variedade de novas atividades e ocupações que vão te ajudar a equilibrar corpo e mente.</p>
                                    <!-- <div>
                                        <badge type="warning" rounded>marketing</badge>
                                        <badge type="warning" rounded>product</badge>
                                        <badge type="warning" rounded>launch</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="warning" class="mt-4">
                                        Learn more
                                    </base-button> -->
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-md-2">
                        <img src="img/theme/undraw_environment_iaus.svg" class="img-fluid floating">
                    </div>
                    <div class="col-md-6 order-md-1">
                        <div class="pr-md-5">
                            <!-- <icon name="ni ni-settings-gear-65" class="mb-5" size="lg" type="success" shadow
                                  rounded></icon> -->
                            <h3>Como uma planta, você também precisa passar por cuidados</h3>
                            <p>Cuidar de sí é viver melhor, assim como o corpo, a mente precisa de cuidados, vivemos em tempos difíceis e queremos te ajudar a passar por eles.</p>
                            <ul class="list-unstyled mt-5">
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-settings-gear-65"></badge>
                                        <h6 class="mb-0">Treine o corpo</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-html5"></badge>
                                        <h6 class="mb-0">Cuide de interior e da mente</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-satisfied"></badge>
                                        <h6 class="mb-0">Todos merecemos a felicidade!</h6>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <section class="section section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-1 bg-gradient-warning shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container py-0">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-lg-2 ml-lg-auto">
                        <div class="position-relative pl-md-5">
                            <img src="img/ill/ill-2.svg" class="img-center img-fluid">
                        </div>
                    </div>
                    <div class="col-lg-6 order-lg-1">
                        <div class="d-flex px-3">
                            <div>
                                <!-- <icon name="ni ni-building" size="lg" class="bg-gradient-white" color="primary" shadow
                                      rounded></icon> -->
                            </div>
                            <div class="pl-4">
                                <h4 class="display-3 text-white">Compre online, pratique pessoalmente</h4>
                                <p class="text-white">Contrate serviços humanizados e acolhedores direto do conforto da sua casa, com transparência e confiança.</p>
                            </div>
                        </div>
                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-satisfied" gradient="success" color="white" shadow
                                          rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-success">Aprenda mais sobre sí</h5>
                                    <p>Além dos descontos, você ainda obtem informações sobre saúde mental e psicologia</p>
                                    <!-- <a href="#" class="text-success">Ver mais</a> -->
                                </div>
                            </div>
                        </card>
                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-active-40" gradient="warning" color="white" shadow
                                          rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-warning">Conheça mais sobre psicologia</h5>
                                    <p>Como encontrar um bom psicologo? O que é terapia comportamental? Psicanálise? </p>
                                    <p>Conheça isso tudo e decida como e com qual profissional você quer dar esse grande passo no cuidado da sua mente.</p>
                                    <!-- <a href="#" class="text-warning">Learn more</a> -->
                                </div>
                            </div>
                        </card>
                    </div>
                </div>
            </div>
        </section>
        <section v-if="false" class="section section-lg">
            <div class="container">
                <div class="row justify-content-center text-center mb-lg">
                    <div class="col-lg-8">
                        <h2 class="display-3">The amazing Team</h2>
                        <p class="lead text-muted">According to the National Oceanic and Atmospheric Administration,
                            Ted, Scambos, NSIDClead scentist, puts the potentially record maximum.</p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-1-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Ryan Tompson</span>
                                    <small class="h6 text-muted">Web Developer</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="warning" icon="fa fa-twitter" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="warning" icon="fa fa-facebook" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="warning" icon="fa fa-dribbble" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-2-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Romina Hadid</span>
                                    <small class="h6 text-muted">Marketing Strategist</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="primary" icon="fa fa-twitter" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="primary" icon="fa fa-facebook" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="primary" icon="fa fa-dribbble" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-3-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Alexander Smith</span>
                                    <small class="h6 text-muted">UI/UX Designer</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="info" icon="fa fa-twitter" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="info" icon="fa fa-facebook" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="info" icon="fa fa-dribbble" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-4-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">John Doe</span>
                                    <small class="h6 text-muted">Founder and CEO</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="success" icon="fa fa-twitter" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="success" icon="fa fa-facebook" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="success" icon="fa fa-dribbble" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-0">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-5 margin-8">
                        <img src="img/theme/undraw_celebration_0jvk.svg" class="img-fluid floating">
                    </div>
                    <div class="col-md-6">
                        <card gradient="white"
                            no-body
                            
                            class="border-0">
                            <div class="p-5">
                                <div class="row align-items-center">
                                    <div class="col-lg-10">
                                        <h3 class="text-primary">Não deixe para depois, nós acreditamos que você consegue </h3>
                                        <p class="lead  mt-3">
                                            As vezes pode ser dificil, mas acreditamos que você pode encontrar ajuda, nossos parceiros estão prontos para te acolher, e tudo isso com descontos especiais.
                                        </p>
                                    </div>                             
                                </div>
                            </div>
                        </card>
                    </div>
                </div>
                
            </div>
        </section>
        <section class="section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-3 bg-gradient-default shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container pt-lg pb-300">
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">
                        <h2 class="display-3 text-white">Esperamos poder ajudar você nessa jornada</h2>
                        <p class="lead text-white">Só precisamos que preencha o formulário, e então poderemos te conectar com vários serviços e psicólogos que poderão te ajudar a ter uma vida melhor, para você e todos aqueles que ama.</p>
                    </div>
                </div>
                <!-- <div class="row row-grid mt-5">
                    <div class="col-lg-4">
                        <icon name="ni ni-settings" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">Building tools</h5>
                        <p class="text-white mt-3">Some quick example text to build on the card title and make up the
                            bulk of the card's content.</p>
                    </div>
                    <div class="col-lg-4">
                        <icon name="ni ni-ruler-pencil" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">Grow your market</h5>
                        <p class="text-white mt-3">Some quick example text to build on the card title and make up the
                            bulk of the card's content.</p>
                    </div>
                    <div class="col-lg-4">
                        <icon name="ni ni-atom" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">Launch time</h5>
                        <p class="text-white mt-3">Some quick example text to build on the card title and make up the
                            bulk of the card's content.</p>
                    </div>
                </div> -->
            </div>
        </section>
        <section class="section section-lg pt-lg-0 section-contact-us">
            <div class="container">
                <div class="row justify-content-center mt--300">
                    <div class="col-lg-8">
                        <card gradient="secondary" shadow body-classes="p-lg-5">
                            <h4 class="mb-1">Poderia cadastrar-se? </h4>
                            <p class="mt-0">Ajudar você é muito importante para nós</p>                                                                                                                        
                             <form  method="POST" :action="cadastrar">                                                                    
                                    <label  for="email">Email</label>
                                    <base-input v-model="email" name="email" placeholder="Adicione seu email" />
                                    <span></span>
                                        
                                    <label for="servicos">Serviços do seu interesse</label>
                                    <textarea v-model="texto" class="form-control " name="servicos" rows="4"
                                              cols="80" placeholder="Que tipo de serviços você procura?" />
                                    <base-button tag="button"
                                                 class="mb-12 mb-sm-0 btn-cadastrar"
                                                 type="info"
                                                 round block size="lg"
                                                 v-on:click="cadastrar"
                                                 >
                                        Cadastrar
                                    </base-button>
                                    </form >                            
                        </card>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>

const Parse = require('parse')

Parse.serverURL="https://relaxai.back4app.io/"
Parse.initialize("mn1U2NGsbSLY8Fo7ER9XHsdYjTG2ccIkSYnBSyHZ", "t1etGKEovjHhzNX6ELjnXEJ8GO0jdRypePlKK2sJ")


export default {
  name: "home",
  components: {},
  data () {
      return {
          email: "",
          texto: ""
      };
  },
  methods: {
    cadastrar () {
        const Newsletter = Parse.Object.extend("newsletter")
        const newsletter = new Newsletter();        
        
        newsletter.set("email", this.email);
        newsletter.set("texto", this.texto);

        newsletter.save().then(function (obj) {
            console.log("Success", obj);
            alert("Obrigado! Logo entraremos em contato com novidades.")            
        })
        .catch(function (e) {                    
            console.log("Error saving test object!" + e.message);                    
        });
    }      
  }
};
</script>

<style scoped>

.btn-cadastrar {
    width: 100%;
    margin-top: 20px;
}

.margin-8 {
    margin-right: 6vw;
}

</style>


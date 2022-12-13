<template>
  <div class="container px-5 mt-5 cust pb-5">
    <div class="row" style="background-color: darkslategrey; height: 200px;">
      <div class="col-3 p-0">
        <img src="https://themes.3rdwavemedia.com/demo/bs5/pillar/assets/images/profile.jpg" height="200px">
      </div>
      <div class="col-6 mt-2" style="color: white">
        <div>
          <h1 class="fw-bolder"> STEVE DOE</h1>
          <h2 class="fw-lighter">Full Stack Developer</h2>
        </div>
        <div style="color:darkgray" class="mt-4 d-flex flex-column gap-1">
          <div>
            <i class="fa fa-envelope-o" aria-hidden="true"></i><a href="#" class="ms-2">Steve.Doe@website.com</a>
          </div>
          <div>
            <i class="fa fa-mobile" aria-hidden="true"></i><a href="#" class="ms-3">0123 456 78900</a>
          </div>
        </div>
      </div>
      <div class="col-3 d-flex flex-column gap-3 mt-4" style="color:darkgray">
        <div class="d-flex gap-2 align-items-center">
          <i class="fa fa-linkedin-square" aria-hidden="true"></i><a href="#">linkedin.com/in/stevedoe</a>
        </div>
        <div class="d-flex gap-2 align-items-center">
          <i class="fa fa-github-alt" aria-hidden="true"></i><a href="#">github.com/username</a>
        </div>
        <div class="d-flex gap-2 align-items-center">
          <i class="fa fa-codepen" aria-hidden="true"></i><a href="#">codepen.io/username/</a>
        </div>
        <div class="d-flex gap-2 align-items-center">
          <i class="fa fa-question-circle" aria-hidden="true"></i><a href="#">yourwebsite.com</a>
        </div>
      </div>
    </div>
    <div class="mt-5 px-3">
      <h4>CAREER SUMMARY</h4>
      <hr class="fw-bolder">
      <div>
        Summarise your career here. You can make a PDF version of your resume using our free Sketch template here.
        Aenean commodo ligula eget dolor aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes,
        nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu. Lorem ipsum dolor sit amet,
        consectetuer
        adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis
        parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem.
        Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget. Lorem ipsum dolor
        sit
        amet, consectetuer adipiscing elit.
      </div>
    </div>
    <div class="row mt-5 px-3">
      <div class="col-9">
        <h4>WORK EXPERIENCE</h4>
        <hr class="fw-bolder">
        <div class="px-5">
          <div>
            <div class="d-flex justify-content-between">
              <div class="fs-4 fw-bolder">
                Lead Developer
              </div>
              <div>
                Startup Hub
              </div>
            </div>
            <h6 class="fw-lighter">2020 - Present</h6>
            <div class="mt-3">
              Role description goes here ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget
              dolor.
              Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec
              quam
              felis, ultricies nec, pellentesque eu, pretium quis, sem. Donec pede justo, fringilla vel.
            </div>
            <h6 class="mt-3">Achievements:</h6>
            <div>
              Praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati
              cupiditate non provident.
            </div>
            <ul class="mt-3">
              <li>Lorem ipsum dolor sit amet, 80% consectetuer adipiscing elit.</li>
              <li>At vero eos et accusamus et iusto odio dignissimos.</li>
              <li>Blanditiis praesentium voluptatum deleniti atque corrupti.</li>
              <li>Maecenas tempus tellus eget.</li>
            </ul>
            <h6 class="fw-bolder">Technologies used:</h6>
            <div class="d-flex gap-2 mt-2">
              <div v-for="technology in leadTechnologies" class="bg-secondary text-white rounded-1 px-2">
                {{ technology }}
              </div>
            </div>
          </div>
          <div class="mt-5">
            <div class="d-flex justify-content-between">
              <div class="fs-4 fw-bolder">
                Senior Software Developer
              </div>
              <div>
                Google
              </div>
            </div>
            <h6 class="fw-lighter">2016 - 2020</h6>
            <div class="mt-3">
              Role description goes here ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget
              dolor.
              Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec
              quam
              felis, ultricies nec, pellentesque eu, pretium quis, sem. Donec pede justo, fringilla vel.
            </div>
            <h6 class="mt-3">Achievements:</h6>
            <div>
              Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis,
              ultricies nec, pellentesque eu, pretium quis, sem.
            </div>
            <h6 class="fw-bolder mt-2">Technologies used:</h6>
            <div class="d-flex gap-2 mt-2">
              <div v-for="technology in devTechnologies" class="bg-secondary text-white rounded-1 px-2">
                {{ technology }}
              </div>
            </div>
          </div>
          <div class="mt-5">
            <div class="d-flex justify-content-between">
              <div class="fs-4 fw-bolder">
                Co-Founder & Lead Developer
              </div>
              <div>
                To-do Lists
              </div>
            </div>
            <h6 class="fw-lighter">2012 - 2016</h6>
            <div class="mt-3">
              Role description goes here ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget
              dolor.
              Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec
              quam
              felis, ultricies nec.
            </div>
            <div class="mt-2">
              Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa.
              Cum sociis natoque penatibus et magnis dis parturient montes.
            </div>
            <h6 class="fw-bolder mt-2">Technologies used:</h6>
            <div class="d-flex gap-2 mt-2">
              <div v-for="technology in founderTechnologies" class="bg-secondary text-white rounded-1 px-2">
                {{ technology }}
              </div>
            </div>
          </div>
          <div class="mt-5">
            <div class="d-flex justify-content-between">
              <div class="fs-4 fw-bolder">
                Web Developer (Intern)
              </div>
              <div>
                Amazon
              </div>
            </div>
            <h6 class="fw-lighter">2011 - 2012</h6>
            <div class="mt-3">
              Role description goes here ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget
              dolor.
              Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec
              quam
              felis, ultricies nec. Fusce vulputate eleifend sapien. Vestibulum purus quam, scelerisque ut, mollis sed,
              nonummy
              id, metus. Nullam accumsan lorem in dui. Cras ultricies mi eu turpis hendrerit fringilla. Vestibulum.
            </div>
            <h6 class="fw-bolder mt-2">Technologies used:</h6>
            <div class="d-flex gap-2 mt-2">
              <div v-for="technology in webTechnologies" class="bg-secondary text-white rounded-1 px-2">
                {{ technology }}
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-3">
        <h4>SKILLS & TOOLS</h4>
        <hr class="fw-bolder">
        <div class="fs-6">
          <div>
            <h6>Frontend</h6>
            <div v-for="front in frontend">
              <p>{{ front.name }}</p>
              <div class="progress">
                <div class="progress-bar bg-secondary" role="progressbar" :style="{width: front.percent+'%'}" aria-valuenow="75" aria-valuemin="0"
                     aria-valuemax="100"></div>
              </div>
            </div>
          </div>
          <div class="mt-2">
            <h6>Backend</h6>
            <div v-for="back in backend">
              <p>{{ back.name }}</p>
              <div class="progress">
                <div class="progress-bar bg-secondary" role="progressbar" :style="{width: back.percent+'%'}" aria-valuenow="75" aria-valuemin="0"
                     aria-valuemax="100"></div>
              </div>
            </div>
          </div>
          <div class="mt-2">
            <h6>Others</h6>
          </div>
        </div>
        <h4 class="mt-3">EDUCATION</h4>
        <hr class="fw-bolder">
        <div>
          <div>
            <div class="fw-normal">MSc in Computer Science</div>
            <div class="fw-light">University College London</div>
            <div class="fw-lighter">2010 - 2011</div>
          </div>
          <div class="mt-2">
            <div class="fw-normal">BSc Maths and Physics</div>
            <div class="fw-light">Imperial College London</div>
            <div class="fw-lighter">2007 - 2010</div>
          </div>
        </div>
        <h4 class="mt-3">AWARDS</h4>
        <hr class="fw-bolder">
        <div>
          <i class="fa fa-trophy" aria-hidden="true"></i>
          <div class="fw-bold d-inline">Award Name Lorem</div>
          <div class="px-3 fw-light">Award desc goes here, ultricies nec, pellentesque eu, pretium quis, sem.
            Nulla consequat massa quis enim. Donec pede justo.
          </div>
        </div>
        <div class="mt-3">
          <i class="fa fa-trophy" aria-hidden="true"></i>
          <div class="fw-bold d-inline">Award Name Ipsum</div>
          <div class="px-3 fw-light">Award desc goes here, ultricies nec, pellentesque.</div>
        </div>
        <h4 class="mt-5">LANGUAGE</h4>
        <hr class="fw-bolder">
        <div>
          <div><b>English</b> (Native)</div>
          <div><b>French</b> (Professional)</div>
          <div><b>Spanish</b> (Professional)</div>
        </div>
        <h4 class="mt-3">INTERESTS</h4>
        <hr class="fw-bolder">
        <div>
          <div class="fw-normal">Climbing</div>
          <div class="fw-normal">Snowboarding</div>
          <div class="fw-normal">Cooking</div>
        </div>
      </div>
    </div>
  </div>

</template>

<script>

export default {
  name: 'homepage',
  data() {
    return {
      leadTechnologies: [
        "Angular", "Python", "jQuery", "Webpack", "HTML/SASS", "PostgresSQL"
      ],
      devTechnologies: [
        'React', 'Redux', 'Django', 'Webpack', 'HTML/SASS', 'MySQL'
      ],
      founderTechnologies: [
        'Django', 'JavaScript', 'Node.js', 'Require.js', 'HTML/SASS'
      ],
      webTechnologies: [
        'Ruby on Rails', 'jQuery', 'HTML/LESS', 'MongoDB'
      ],
      frontend: [
        {
          name: 'Angular',
          percent: 75,
        },
        {
          name: 'React',
          percent: 50,
        },
        {
          name: 'JavaScript',
          percent: 90,
        },
        {
          name: 'Node.js',
          percent: 100,
        },
        {
          name: 'HTML/CSS/SASS/LESS',
          percent: 60,
        },
      ],
      backend: [
        {
          name: 'Python/Django',
          percent: 60,
        },
        {
          name: 'Ruby/Rails',
          percent: 70,
        },
        {
          name: 'PHP',
          percent: 80,
        },
        {
          name: 'WordPress/Shopify',
          percent: 100,
        },
      ]
    }
  }
}
</script>
<style scoped>
a {
  color: darkgray;
  text-decoration: none;
}

.cust {
  padding-left: 500px;
  padding-right: 500px;
}
</style>
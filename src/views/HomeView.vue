<template>
   <header>
        <nav>
            <div class="NBA-logo">
                <!-- <div class="img-logo">
                    <img src="NBA_logo1.png" alt="">
                </div>
                <div class="logo-text">
                    <h5>Nigerian BAR Assiocation</h5>
                    <h6>Promoting the rule of law</h6>
                </div> -->

                <img src="../assets/afed1.png" alt="">
            </div>

            <div class="act-btn">
                <router-link to="/" class="signin">Sign In</router-link>
                <!-- <router-link to="/register" class="signup">Sign Up</router-link> -->
                <a href="https://memberly.vercel.app/event/2ef860b9-a76f-4dad-9fdd-307237f4eb05" class="signup">Register</a>
            </div>
        </nav>
    </header>

    <section>
        <div class="hero">
            <div class="overlay"></div>
            <div class="hero-holder">
                <div class="hero-text">
                    <h2>
                        Welcome to AFED
                    </h2>
                    <p>
                        An association of low-fee education service providers working to promote an enabling platform to achieve better educational standards for the populace through effective collaboration with relevant stakeholders. 
                    </p>

                    <router-link to="" class="read-more">Read More</router-link>
                </div>
                <!-- <div class="hero-image">
                    <img src="../assets/AfedMeeting.jpg" alt="">
                </div> -->
            </div>
        </div>
    </section>

    <section>
        <div class="card-box">
            <div class="card-head">
                <h1>Key Features</h1>
                <p>We organise unified mock examinations for students of member schools, prepare pupils in yet-to-be-approved schools for placement examinations and publish educational development tools such as Continuous Assessment Kits, Student Register, Student’s Diary Book etc... AFED currently has over 5000 members all across the nation.</p>
            </div>
            <div class="card-col">
                <div class="card">
                    <div class="card-image">
                        <img src="../assets/person-solid.svg" alt="">
                    </div>
                    <h5>Pre-Primary</h5>
                    <p>An investment in knowledge pays the best interest over time</p>
                </div>
                <div class="card">
                    <div class="card-image">
                        <img src="../assets/file-solid.svg" alt="">
                    </div>
                    <h5>Primary Education</h5>
                    <p>Education is the passport for the furture, for tomorrow belongs to those who prepares for it today</p>
                </div>
                <div class="card">
                    <div class="card-image">
                        <img src="../assets/graduation-cap-solid.svg" alt="">
                    </div>
                    <h5>Junior Secondary</h5>
                    <p>Education is the most powerfull weapon which you can use to change the world</p>
                </div>
                <div class="card">
                    <div class="card-image">
                        <img src="../assets/graduation-cap-solid.svg" alt="">
                    </div>
                    <h5>Senior Secondary</h5>
                    <p>Education is the key to success in life, and teachers make a lasting impact in the lives of their students</p>


                </div>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; All rights reserved. AFED</p>
    </footer>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
    
  }
}
</script>

<style scoped>
.hero {
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #F8F9FA;
    background-image: url('../assets/AfedMeeting.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    height: 85vh;
    padding-top: 1rem;
    color: #fff;
    position: relative;
}

.overlay {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color:#00afef34;
    top: 0;
    
}
</style> 

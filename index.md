---
layout: default
title: Home
---

<!-- Hero Section -->
<section class="hero">
    <div class="hero-content">
        <h1>Java Backend Classroom</h1>
        <p class="lead">Master Enterprise Java Development from Fundamentals to Advanced Frameworks</p>
        
        <div class="instructor-info">
            <div class="instructor-name">Farshad Fallah</div>
            <p class="instructor-title">Java Developer | Software Engineer | Instructor</p>
        </div>

        <a href="#course-sections" class="btn-primary">
            <i class="bi bi-play-circle"></i>
            Start Your Journey
        </a>
    </div>
</section>

<!-- Course Sections -->
<section class="course-section" id="course-sections">
    <div class="container">
        <div class="section-title">
            <h2>Course Curriculum</h2>
            <div class="underline"></div>
            <p>Four comprehensive modules covering the complete Java backend stack</p>
        </div>
        
        <div class="course-grid">
            <!-- Module 1: Development Fundamentals -->
            <div class="course-card fundamentals">
                <div class="card-img-wrapper">
                    <span class="badge">Module 1</span>
                    <i class="bi bi-code-square"></i>
                </div>
                <div class="card-body">
                    <h5 class="card-title">Development Fundamentals</h5>
                    <p class="card-text">Build a solid foundation in programming principles, algorithms, and problem-solving techniques.</p>
                    <a href="{{ '/fundamentals.html' | relative_url }}" class="btn-outline-primary">
                        Explore <i class="bi bi-arrow-right"></i>
                    </a>
                </div>
            </div>

            <!-- Module 2: Java SE -->
            <div class="course-card javase">
                <div class="card-img-wrapper">
                    <span class="badge">Module 2</span>
                    <i class="bi bi-cup-hot"></i>
                </div>
                <div class="card-body">
                    <h5 class="card-title">Java SE</h5>
                    <p class="card-text">Master Java Standard Edition including core concepts, OOP, collections, streams, and concurrency.</p>
                    <a href="{{ '/java-fundamentals.html' | relative_url }}" class="btn-outline-primary">
                        Explore <i class="bi bi-arrow-right"></i>
                    </a>
                </div>
            </div>

            <!-- Module 3: Jakarta EE -->
            <div class="course-card jakarta">
                <div class="card-img-wrapper">
                    <span class="badge">Module 3</span>
                    <i class="bi bi-layers"></i>
                </div>
                <div class="card-body">
                    <h5 class="card-title">Jakarta EE</h5>
                    <p class="card-text">Learn enterprise Java development with Jakarta EE specifications, servlets, JSP, and JPA.</p>
                    <a href="{{ '/jakarta-ee.html' | relative_url }}" class="btn-outline-primary">
                        Explore <i class="bi bi-arrow-right"></i>
                    </a>
                </div>
            </div>

            <!-- Module 4: Spring Framework -->
            <div class="course-card spring">
                <div class="card-img-wrapper">
                    <span class="badge">Module 4</span>
                    <i class="bi bi-diagram-3"></i>
                </div>
                <div class="card-body">
                    <h5 class="card-title">Spring Framework</h5>
                    <p class="card-text">Dive into Spring Boot, Spring MVC, Spring Data, Spring Security, and microservices architecture.</p>
                    <a href="{{ '/spring.html' | relative_url }}" class="btn-outline-primary">
                        Explore <i class="bi bi-arrow-right"></i>
                    </a>
                </div>
            </div>
        </div>
    </div>
</section>
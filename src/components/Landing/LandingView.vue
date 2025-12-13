<template>
  <div class="landing-root d-flex flex-column min-vh-100 overflow-hidden text-dark position-relative">
    <nav class="navbar navbar-expand navbar-dark fixed-top px-4 py-3"
      style="background: rgba(26, 52, 85, 0.44); backdrop-filter: blur(3px); border-bottom: 1px solid rgba(255, 255, 255, 0.12); box-shadow: 0 2px 10px rgba(90, 160, 255, 0.08);">
      <div class="container-fluid">
        <span class="navbar-brand fw-bold fs-3 text-white" style="letter-spacing: 0.5px;">Sync'em</span>
        <div class="ms-auto">
          <router-link :to="{ name: 'Login' }" class="nav-link text-white fs-5 fw-medium">Login</router-link>
        </div>
      </div>
    </nav>

    <section class="d-flex flex-column align-items-center justify-content-start text-center text-white py-5 mt-5"
      style="min-height: 45vh; padding-top: 100px !important;">
      <div class="container d-flex flex-column align-items-center">
        <h1 class="display-3 fw-bold mb-2 text-shadow">WELCOME!</h1>
        <h2 class="h1 fw-medium mb-3" style="color: #e2e8ff;">Sync'em — smarter HR, happier teams</h2>
        <p class="lead mb-4" style="max-width: 600px; color: #f2f4ff; font-size: 18px;">
          Seamlessly synchronize your data, tasks, and teams with AI-driven HR workflows and instant assistance.
        </p>

        <div class="d-flex align-items-center gap-2">
          <router-link :to="{ name: 'Login' }" class="btn btn-primary custom-btn fw-semibold px-3 py-2">Get
            Started</router-link>
          <a href="#features" class="btn btn-outline-light fw-semibold px-3 py-2"
            style="border-color: rgba(255,255,255,0.12);">Learn More</a>
        </div>
      </div>
    </section>

    <section id="features" class="py-5 px-4 text-white">
      <div class="container-fluid">
        <div class="row justify-content-center g-4">
          <div class="col-12 col-lg-4 d-flex flex-column align-items-center">
            <h2 class="fw-bold mb-4 text-center" style="color: #e2e8ff;">For HR</h2>
            <div class="d-flex flex-column gap-3 w-100 align-items-center">
              <div class="feature-card p-4 rounded-4"
                style="width: 100%; max-width: 360px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.15); backdrop-filter: blur(6px);">
                <h3 class="h5 text-white mb-2 text-center">HR Policy Management</h3>
                <p class="small mb-0" style="color: #f0f0ff; line-height: 1.6; text-align: justify;">
                  Create, update, and publish HR policies that are instantly accessible to employees via the platform
                  and chatbot.
                </p>
              </div>
              <div class="feature-card p-4 rounded-4"
                style="width: 100%; max-width: 360px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.15); backdrop-filter: blur(6px);">
                <h3 class="h5 text-white mb-2 text-center">Performance Reviews & Feedback</h3>
                <p class="small mb-0" style="color: #f0f0ff; line-height: 1.6; text-align: justify;">
                  Manage employee performance reviews and generate structured summaries to support appraisal and
                  evaluation workflows.
                </p>
              </div>
            </div>
          </div>

          <div class="col-12 col-lg-4 d-flex flex-column align-items-center">
            <h2 class="fw-bold mb-4 text-center" style="color: #e2e8ff;">For Product Manager</h2>
            <div class="d-flex flex-column gap-3 w-100 align-items-center">
              <div class="feature-card p-4 rounded-4"
                style="width: 100%; max-width: 360px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.15); backdrop-filter: blur(6px);">
                <h3 class="h5 text-white mb-2 text-center">Intelligent Team Allocation</h3>
                <p class="small mb-0" style="color: #f0f0ff; line-height: 1.6; text-align: justify;">
                  Leverage GenAI to analyze skills, workload, and availability to build balanced, high-performing teams
                  for every project.
                </p>
              </div>
              <div class="feature-card p-4 rounded-4"
                style="width: 100%; max-width: 360px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.15); backdrop-filter: blur(6px);">
                <h3 class="h5 text-white mb-2 text-center">Automated Reports & Insights</h3>
                <p class="small mb-0" style="color: #f0f0ff; line-height: 1.6; text-align: justify;">
                  Generate daily progress reports, performance insights, and client updates automatically—so you focus
                  on delivery, not documentation.
                </p>
              </div>
            </div>
          </div>

          <div class="col-12 col-lg-4 d-flex flex-column align-items-center">
            <h2 class="fw-bold mb-4 text-center" style="color: #e2e8ff;">For Employee</h2>
            <div class="d-flex flex-column gap-3 w-100 align-items-center">
              <div class="feature-card p-4 rounded-4"
                style="width: 100%; max-width: 360px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.15); backdrop-filter: blur(6px);">
                <h3 class="h5 text-white mb-2 text-center">Employee Dashboard</h3>
                <p class="small mb-0" style="color: #f0f0ff; line-height: 1.6; text-align: justify;">
                  Access a personalized dashboard showing assigned projects, requests, learning resources, and HR
                  updates in one place.
                </p>
              </div>
              <div class="feature-card p-4 rounded-4"
                style="width: 100%; max-width: 360px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.15); backdrop-filter: blur(6px);">
                <h3 class="h5 text-white mb-2 text-center">HR FAQ & Policy Access</h3>
                <p class="small mb-0" style="color: #f0f0ff; line-height: 1.6; text-align: justify;">
                 Get instant answers to HR questions using the integrated HR chatbot, without waiting for manual HR
                  responses.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.min.css';

export default {
  name: 'LandingView'
}
</script>

<style scoped>
.landing-root {
  background: url('../../assets/images/landing/landingPageBackgroundImage.png') no-repeat center center/cover;
  background-color: rgba(20, 40, 108, 0.85);
  background-blend-mode: overlay;
  font-family: 'Inter', system-ui, -apple-system, sans-serif;
}

.text-shadow {
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
}

.custom-btn {
  background: linear-gradient(90deg, #6366f1, #3b82f6);
  border: none;
  transition: transform 0.3s ease, background 0.3s ease;
}

.custom-btn:hover {
  background: linear-gradient(90deg, #818cf8, #60a5fa);
  transform: translateY(-2px);
}

.feature-card {
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.feature-card:hover {
  background: rgba(255, 255, 255, 0.25) !important;
  box-shadow: 0 0 20px rgba(99, 102, 241, 0.7) !important;
  transform: translateY(-5px) scale(1.02);
}

.nav-link:hover {
  color: #dce3ff !important;
}
</style>

<template>
    <footer class="bg-dark text-light pt-4">
      <div class="container">
        <div class="row">
          <!-- Footer Logo ve Açıklama -->
          <div class="col-md-4">
            <h5>HRMS</h5>
            <p>
                Human Resource Management System  is a modern platform aimed at providing the best experience for its users
            </p>
          </div>
          <!-- Hızlı Linkler -->
          <div class="col-md-4">
            <h5>Quick Links</h5>
            <ul class="list-unstyled">
              <li><a href="#" class="text-light">Home</a></li>
              <li><a href="#" class="text-light">About</a></li>
              <li><a href="#" class="text-light">Services</a></li>
              <li><a href="#" class="text-light">Contact</a></li>
            </ul>
          </div>
          <!-- Sosyal Medya -->
          <div class="col-md-4">
            <h5>Follow Us</h5>
            <div class="d-flex">
              <a href="#" class="text-light mr-3">
                <i class="fab fa-facebook fa-2x"></i>
              </a>
              <a href="#" class="text-light mr-3">
                <i class="fab fa-twitter fa-2x"></i>
              </a>
              <a href="#" class="text-light mr-3">
                <i class="fab fa-instagram fa-2x"></i>
              </a>
              <a href="#" class="text-light">
                <i class="fab fa-linkedin fa-2x"></i>
              </a>
            </div>
          </div>
        </div>
        <!-- Telif Hakkı Bölümü -->
        <div class="row mt-4">
          <div class="col text-center">
            <p class="mb-0">&copy; 2024 HRMS. All rights reserved.</p>
          </div>
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'FooterComponent',
  }
  </script>
  
  <style scoped>
  /* Footer özel stiller */
  footer {
    padding-top: 20px;
    padding-bottom: 20px;
    background-color: #343a40;
    color: #fff;
  }
  
  footer h5 {
    font-weight: bold;
  }
  
  footer a {
    text-decoration: none;
  }
  
  footer a:hover {
    color: #007bff;
  }
  
  footer .fab {
    transition: color 0.3s ease;
  }
  
  footer .fab:hover {
    color: #007bff;
  }
  </style>
  
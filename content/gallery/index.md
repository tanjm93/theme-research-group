---
title: Gallery
date: 2022-10-24

type: landing

sections:
  - block: markdown
    content:
      title: Gallery
      text: |
        <div class="gallery-grid">
          <div class="gallery-item">
            <img src="../media/welcome.jpg" alt="Gallery image 1">
          </div>
          <div class="gallery-item">
            <img src="../media/coders.jpg" alt="Gallery image 2">
          </div>
          <div class="gallery-item">
            <img src="../media/contact.jpg" alt="Gallery image 3">
          </div>
          <!-- Add more gallery items here -->
        </div>

        <style>
        .gallery-grid {
          display: grid;
          grid-template-columns: repeat(3, 1fr);
          gap: 20px;
          max-width: 1200px;
          margin: 40px auto;
          padding: 0 20px;
        }

        .gallery-item {
          position: relative;
          overflow: hidden;
          aspect-ratio: 1 / 1;
          border-radius: 8px;
          cursor: pointer;
        }

        .gallery-item img {
          width: 100%;
          height: 100%;
          object-fit: cover;
          transition: transform 0.3s ease;
        }

        .gallery-item:hover img {
          transform: scale(1.1);
        }

        /* Tablet view - 2 columns */
        @media (max-width: 768px) {
          .gallery-grid {
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
          }
        }

        /* Mobile view - 1 column */
        @media (max-width: 480px) {
          .gallery-grid {
            grid-template-columns: 1fr;
            gap: 15px;
          }
        }
        </style>
    design:
      columns: '1'
---

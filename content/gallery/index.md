---
title: Gallery
date: 2022-10-08

type: landing

sections:
  - block: markdown
    content:
      title: Gallery
      text: |
        <div style="text-align: center; font-size: 1.2rem; padding: 10px 0 40px 0; color: #666;">
          Watch this space for some behind the scenes of Leong Research Group in action!
        </div>

        <div class="gallery-grid">

          <div class="gallery-item">
            <img src="gallery/album/lab-photo-1.jpg" alt="New lab space">
          </div>

          <div class="gallery-item">
            <video controls muted playsinline poster="gallery/album/pineapple-roll-screenshot.jpg">
              <source src="/gallery/album/lab-pineapple-roll.mp4" type="video/mp4">
              Your browser does not support the video tag.
            </video>
          </div>

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

        .gallery-item img, .gallery-item video {
          width: 100%;
          height: 100%;
          object-fit: cover;
          transition: transform 0.3s ease;
        }

        .gallery-item:hover img {
          transform: scale(1.1);
        }

        .gallery-item video {
          position: relative;
          z-index: 1;
          pointer-events: auto;
          cursor: default;
          transition: transform 0.3s ease;
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
            grid-template-columns: 1fr !important;
            gap: 20px !important;
            display: flex !important;
            flex-direction: column !important;
          }

          .gallery-item {
            aspect-ratio: auto !important;
            height: auto !important;
            width: 100% !important;
            position: relative !important;
          }

          .gallery-item img,
          .gallery-item video {
            position: relative !important;
            width: 100% !important;
            height: auto !important;
            display: block !important;
          }
        }
        </style>
    design:
      columns: '1'
---

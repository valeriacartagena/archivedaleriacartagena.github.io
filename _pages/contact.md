---
layout: page
title: Contact me!
permalink: /contact
comments: true
<script
    src="https://kit.fontawesome.com/25bc89a4e6.js"
    crossorigin="anonymous>
</script>
---

<body>
<div class="social-links">
    <a href="https://www.instagram.com/valeriacartagenav_/" target="_blank">
        i class="fab fa-instagram"></i>
    </a>
    </a>
    <a href="https://www.linkedin.com/in/valeriacartagena/" target="_blank">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://github.com/valeriacartagena" target="_blank">
        <i class="fab fa-github"></i>
    </a>
</div>
    <style>
      * {
        margin: 0;
        padding: 0;
    }
    body {
        background: rgb(255, 210, 253);
      }
      .social-links {
        margin-top: 200px; /*use any margin that u need*/
        display: flex;
        justify-content: center;
    }
    a {
        height: 90px;
        width: 90px;
        margin: 0 20px; /*as bigger margin as farther from each other will be social links*/
        display: flex;
        align-items: center;
        justify-content: center;
        text-decoration: none;
        background-color: rgb(
          255,
          210,
          253
        ); /*use the same color that body background or any other matching color that u like*/
        border-radius: 50%; /*50% make round shape,
        u can use border-radius less than 50% to have oval shape*/
        border: 1px solid rgba(214, 202, 214, 0.72);
        box-shadow: 8px 8px 12px -2px rgb(187, 192, 196),
          -5px -5px 9px -2px rgb(173, 177, 177);
        transition: transform 1s; /*any transition number from 0.3s to 1s*/
    }
    a i {
        font-size: 50px; /*any font-size from 20px to 40px will look good. I've used 50px just
          for demonstration purpose*/
        color: rgb(77, 113, 119);
        transition: transform 1s; /*it's great to match a{transition: transform 1s;} with
        i{transition: transform 1s;} it will be synchronized*/
    }
    a:hover {
        box-shadow: inset 6px 6px 8px -2px rgb(168, 170, 172),
          inset -6px -6px 8px -2px rgb(193, 211, 214),
          0px 12px 10px -10px rgb(124, 146, 143);
        border: 2px solid rgba(194, 171, 194, 0.3);
        transform: translateY(3px);
    }
    a:hover i {
        transform: scale(0.85);
    }
    a:hover .fa-instagram {
        color: #e4405f;
    }
    a:hover .fa-youtube {
        color: #cd201f;
    }
    a:hover .fa-wordpress {
        color: #21759b;
    }
    a:hover .fa-linkedin {
        color: #0077b5;
    }
    a:hover .fa-github {
        color: #333333;
    }
   </style>
</body>
<html lang="{{ site.lang | default: "en-US" }}">
  <head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}">

  </head>

  <body>

    <header>
      <div class="container">

        <section id="downloads">
          {% if site.show_downloads %}
          {% endif %}
          <a href="https://petesoelite.github.io/ps4-jbxploit-host/75x/index.html" style="color:#3366ff" class="btn _5"><span class="icon"></span>PS4 7.5x Xploit</a>
          <a href="https://petesoelite.github.io/ps4-jbxploit-host/702/index.html" style="color:#3366ff" class="btn _5"><span class="icon"></span>PS4 7.02 Xploit</a>
        </section>
      </div>
    </header>

    <div class="container">
      <section id="main_content">
        {{ content }}
      </section>
    </div>
  </body>
</html>

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
          <a href="https://github.com/petesoelite/ps4-jbxploit-host/blob/main/75x/index.html" style="color:#660066" class="btn _5"><span class="icon"></span>PS4 7.5x Xploit</a>
          <br>
          <a href="https://github.com/petesoelite/ps4-jbxploit-host/blob/main/75x/index.html" style="color:#660066" class="btn _5"><span class="icon"></span>PS4 7.02 Xploit</a>
          </br>
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

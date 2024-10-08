.. CrossGL documentation master file, created by
   sphinx-quickstart on Thu Jul 22 14:28:32 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to CrossGL's documentation!
===================================

.. raw:: html

      <div style="text-align: center; margin-top: 10px;">

      <div style="text-align: center; margin-top: 10px;">
         <a href="https://discord.gg/YOUR_INVITE_LINK" id="discord-link">
            <img src="https://img.shields.io/discord/1240998239206113330?style=flat-square&logo=Discord" alt="Join our Discord" id="discord-badge" />
         </a>
      </div>

      <script>
         const GUILD_ID = '1240998239206113330';
         const WIDGET_URL = `https://discord.com/api/guilds/1240998239206113330/widget.json`;

         fetch(WIDGET_URL)s
         .then(response => response.json())
         .then(data => {
            const onlineCount = data.presence_count;
            const badge = document.getElementById('discord-badge');
            badge.src = `https://img.shields.io/badge/online-${onlineCount}-brightgreen`;
         })
         .catch(error => {
            console.error('Error fetching Discord widget data:', error);
            const badge = document.getElementById('discord-badge');
            badge.src = `https://img.shields.io/badge/online-unavailable-lightgrey`;
         });
      </script>

        <a href="https://github.com/CrossGL/crosstl">
          <img src="https://img.shields.io/github/issues/CrossGL/crosstl?style=flat-square" alt="issues" />
        </a>
        <a href="https://github.com/your-repo">
          <img src="https://img.shields.io/github/forks/your-repo/your-project.svg?style=flat-square" alt="forks" />
        </a>
        <a href="https://github.com/your-repo">
          <img src="https://img.shields.io/github/stars/your-repo/your-project.svg?style=flat-square" alt="stars" />
        </a>
        <a href="https://github.com/your-repo">
          <img src="https://img.shields.io/github/contributors/your-repo/your-project.svg?style=flat-square" alt="contributors" />
        </a>
        <a href="https://pypi.org/project/your-project/">
          <img src="https://img.shields.io/pypi/v/your-project.svg?style=flat-square" alt="PyPI version" />
        </a>
        <a href="https://github.com/your-repo">
          <img src="https://img.shields.io/github/license/your-repo/your-project.svg?style=flat-square" alt="license" />
        </a>
    </div>

About CrossGL
=============

CrossGL is a pioneering company in the field of shader development, offering a unified, cross-platform shader language that compiles directly to machine-specific binaries. Our innovative approach eliminates the need for intermediate translation steps, significantly reducing time and development complexity.

.. raw:: html

   <div class="large-text">Our Mission 🎯</div>

Our mission is to streamline the shader development process, making it more efficient and accessible for developers across different platforms. By providing a powerful and intuitive language, we empower developers to create high-performance graphics applications with ease.

.. raw:: html

   <div class="large-text">Our Team 👥</div>

The CrossGL team comprises experienced professionals from the graphics programming and software development industries. We are dedicated to providing top-notch tools and services to our users, constantly pushing the boundaries of what's possible in shader development.

.. raw:: html

    <div>
        <div style="display: flex; flex-wrap: wrap;">
            <div style="margin: 5px; text-align: center;">

                <a href="https://github.com/NripeshN">
                  <img src="https://avatars.githubusercontent.com/u/86844847?v=4" style="width: 40px; height: 40px; border-radius: 50%;" />
                </a>

                <a href="https://github.com/vaatsalya123">
                  <img src="https://avatars.githubusercontent.com/u/96314403?v=4" style="width: 40px; height: 40px; border-radius: 50%;" />
                </a>

                <a href="https://github.com/niixxaaa">
                  <img src="https://avatars.githubusercontent.com/u/91986717?v=4" style="width: 40px; height: 40px; border-radius: 50%;" />
                </a>

                <a href="https://github.com/abhayMore">
                  <img src="https://avatars.githubusercontent.com/u/49201569?v=4" style="width: 40px; height: 40px; border-radius: 50%;" />
                </a>


                <a href="https://github.com/Husienvora">
                  <img src="https://avatars.githubusercontent.com/u/74529491?v=4" style="width: 40px; height: 40px; border-radius: 50%;" />
                </a>


                <a href="https://github.com/samthakur587">
                  <img src="https://avatars.githubusercontent.com/u/83540902?v=4" style="width: 40px; height: 40px; border-radius: 50%;" />
                </a>


                <a href="https://github.com/nomaannm">
                  <img src="https://avatars.githubusercontent.com/u/115913726?v=4" style="width: 40px; height: 40px; border-radius: 50%;" />
                </a>


                <a href="https://github.com/Baxi-codes">
                  <img src="https://avatars.githubusercontent.com/u/46259792?v=4" style="width: 40px; height: 40px; border-radius: 50%;" />
                </a>


                <a href="https://github.com/Solo-Levelings">
                  <img src="https://avatars.githubusercontent.com/u/172627392?v=4" style="width: 40px; height: 40px; border-radius: 50%;" />
                </a>

                <a href="https://github.com/steamid1000">
                  <img src="https://avatars.githubusercontent.com/u/73237099?v=4" style="width: 40px; height: 40px; border-radius: 50%;" />
                </a>

                <a href="https://github.com/ArnavMehta3000">
                  <img src="https://avatars.githubusercontent.com/u/77837038?v=4" style="width: 40px; height: 40px; border-radius: 50%;" />
                </a>

                <a href="https://github.com/ThirulogeswarenVenkatraman">
                  <img src="https://avatars.githubusercontent.com/u/97526449?v=4" style="width: 40px; height: 40px; border-radius: 50%;" />
                </a>

                <a href="https://github.com/JayzCodez">
                  <img src="https://avatars.githubusercontent.com/u/133510488?v=4" style="width: 40px; height: 40px; border-radius: 50%;" />
                </a>
            </div>
        </div>
    </div>


.. toctree::
  :hidden:

  design

.. toctree::
   :hidden:

   translator
   language
   contribution
   api_reference

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

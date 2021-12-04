<main>
  <div class="content">
    <div class="wrapper">
      <div class="nameAndLinks">
        <h1>Pranav Thota</h1>
        <p>Programming Student | 7th Grader</p>
      </div>
      <div class="grid-container">
        <a
          href="https://github.com/awsame303"
          target="_blank"
          rel="noopener"
          title="Github"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentcolor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path
              d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37.0 00-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44.0 0020 4.77 5.07 5.07.0 0019.91 1S18.73.65 16 2.48a13.38 13.38.0 00-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07.0 005 4.77 5.44 5.44.0 003.5 8.55c0 5.42 3.3 6.61 6.44 7A3.37 3.37.0 009 18.13V22"
            />
          </svg>
        </a>

        <a
          href="mailto:tpranav2009@gmail.com"
          target="_blank"
          rel="noopener"
          title="Email"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentcolor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path
              d="M4 4h16c1.1.0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1.0-2-.9-2-2V6c0-1.1.9-2 2-2z"
            />
            <polyline points="22,6 12,13 2,6" />
          </svg>
        </a>
      </div>
    </div>

    <footer class="footer">
      <div class="footer__inner">
        <div class="footer__content">
          <span>© 2021</span>
          <span><a href="https://pranavthota.github.io/">Pranav Thota</a></span>
          <span
            ><a
              href="https://creativecommons.org/licenses/by-nc/4.0/"
              target="_blank"
              rel="noopener">CC BY-NC 4.0</a
            ></span
          >
          <span
            ><a
              href="https://irenekurien.github.io/posts/index.xml"
              target="_blank"
              title="rss"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                width="18"
                height="18"
                viewBox="0 0 20 20"
                fill="none"
                stroke="currentcolor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
                class="feather feather-rss"
                ><path d="M4 11a9 9 0 019 9" /><path
                  d="M4 4a16 16 0 0116 16"
                /><circle cx="5" cy="19" r="1" /></svg
              ></a
            ></span
          >
        </div>
      </div>
      <div class="footer__inner">
        <div class="footer__content" />
      </div>
    </footer>
  </div>
</main>

<style>
  main {
    text-align: center;
    width: 100%;
    margin: 0;
    background-color: rgb(35, 36, 37);
    color: rgb(169, 169, 179);
    font-family: "Inter UI", -apple-system, BlinkMacSystemFont, "Roboto",
      "Segoe UI", Helvetica, Arial, sans-serif;
    line-height: 1.54;
    text-rendering: optimizelegibility;
    font-feature-settings: "liga", "tnum", "case", "calt", "zero", "ss01",
      "locl";
    font-size: 1rem;
    letter-spacing: 0.06em;
  }
  .nameAndLinks {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
  .content {
    display: flex;
    flex-direction: column;
    flex: 1 1 auto;
    align-items: center;
    justify-content: center;
    margin: 0px;
  }
  h1 {
    font-size: 2.625rem;
    margin-top: 150px;
  }
  p {
    box-sizing: inherit;
  }
  a {
    color: inherit;
    background-color: transparent;
    margin: 4px;
  }
  .grid-container {
    margin-bottom: 130px;
  }
  .footer {
    padding: 40px 20px;
    flex-grow: 0;
    color: rgb(153, 153, 153);
    position: absolute;
    bottom: 0;
  }
  .footer__inner {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0px auto;
    width: 760px;
    max-width: 100%;
  }
  .footer__content {
    display: flex;
    flex-direction: row;
    align-items: center;
    font-size: 1rem;
    color: rgb(153, 153, 153);
  }
</style>

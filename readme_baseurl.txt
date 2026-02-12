A Note on baseurl
You currently have baseurl: "/test02".

Important: Whenever you link to images in your Markdown or studio.html include, ensure you use the relative_url filter.

The Test: In your sample Moog post, I suggested img: /img/portfolio/cabin.png. Because of your baseurl, Jekyll will correctly point this to /test02/img/portfolio/cabin.png.

If you find images aren't loading, check that the relative_url filter is applied in your studio-grid-item.html:
src="{{ post.img | relative_url }}"

# Http2 server push example
This example uses [netlify](https://netlify) and [cloudflare](https://cloudflare.com) to demonstrate http2 server push.

## Requirements
* Account in netlify.com and open source plan to use `_headers` file. See more in: [Netlify docs](https://www.netlify.com/docs/headers-and-basic-auth/).
* Account in cloudflare.com

## Know bugs
Netlify doesn't add all `Link` headers correctly so only the `image.jpg` gets pushed.

## License
<a href="http://www.wtfpl.net/">
    <img src="http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-4.png"
       width="80" height="15" alt="WTFPL" />
</a>
[WTFPL](http://www.wtfpl.net/)

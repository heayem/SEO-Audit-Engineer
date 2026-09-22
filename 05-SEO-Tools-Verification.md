SEO VERIFICATION

HTTP
curl -I https://example.com/

REDIRECT
curl -L -I https://example.com/old-url

ROBOTS
curl https://example.com/robots.txt

SITEMAP
curl https://example.com/sitemap.xml

HTML
curl https://example.com/page

CANONICAL
curl https://example.com/page | grep -i canonical

ROBOTS META
curl https://example.com/page | grep -i robots

TITLE
curl https://example.com/page | grep -i "<title"

For JavaScript websites:
Compare initial HTML with rendered DOM.

Check:
- status code
- final URL
- title
- description
- H1
- canonical
- robots
- schema
- important body content
- crawlable links

When possible use:
- Google Search Console
- PageSpeed Insights
- Lighthouse
- browser rendering
- crawler tools
- structured data validation
- HTTP inspection

Never treat:
- sitemap inclusion as proof of indexing
- 200 status as proof of indexability
- canonical as a guarantee of indexing
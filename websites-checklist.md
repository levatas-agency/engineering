# Website Development and Deployment Checklist

Here is the list of activities that apply to the development and deployment of websites and serve as a checklist for our team and a meassure of success for our clients. 

## Development and pre-launch activities

1. Website is responsive and the layouts respond to changes in screen size to accommodate to the respective breakpoints. See [Configure the Viewport](https://developers.google.com/speed/docs/insights/ConfigureViewport) and [Size Content to Viewport](https://developers.google.com/speed/docs/insights/SizeContentToViewport).
1. Files such as JavaScript, HTML, and CSS are minified to reduce file size. See [Minify Resources](https://developers.google.com/speed/docs/insights/MinifyResources).
1. Image files are properly optimized. See [
Optimize Images](https://developers.google.com/speed/docs/insights/OptimizeImages).
1. Compression is enabled for all HTTP requests, including for TTF and EOT formats. See [Enable Compression](https://developers.google.com/speed/docs/insights/EnableCompression).
1. Web Fonts are optimized. woff2 and woff fonts are defined first, as these are compressed. See [Web Font Optimization](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/webfont-optimization).
1. A server caching strategy covering the creation and cache of dynamic pages is in place. See [Improve Server Response Time](https://developers.google.com/speed/docs/insights/Server).
1. A browser caching strategy is in place. See [Leverage Browser Caching](https://developers.google.com/speed/docs/insights/LeverageBrowserCaching).
1. General websites analytics are in place to report on general visitor numbers, in-page engagement, and behavior taken on the site. See [Set up Analytics tracking](https://support.google.com/analytics/answer/1008080?hl=en).
1. Content is proof read for spelling and grammar, punctuation, consistency of writing style, and capitalization.
1. All the descriptive images on the site use the "alt" attribute to improve ADA compliance.
1. Custom 404 and 500 error pages are created and setup to work at every level of the site structure.
1. Forms submissions are stored in the database and there's an option for clients to export them from the site.
1. Website performs appropriately on Internet Explorer 11, and the latest version of Edge, Chrome, Safari, and Firefox.
1. Website performs appropriately on the latest version of Safari for iOS, and Chrome for Android devices.

## Deployment and post-launch activities

1. Updates are first deployed to a staging environment before making them available on production.
1. The site has been load tested taking into account the expected traffic.
1. Regular backups of the website and database are scheduled.
1. A plan is in place to roll back any updates to the previous version.
1. Monitoring alerts are in place to report any downtime with the site.
1. Generation of logs is active and properly coordinated with the server's disk capacity.
1. A Content Delivery Network (CDN) is used to deliver all the static resources of the site.
1. Updates to the site are accessible to clients without having them clearing their cache.

## Security and risk mitigation

1. Every form in the site is resilient to special characters.
1. An SSL certificate is in place covering all the variations of the URL.
1. All HTTP traffic is automatically redirected to HTTPS.
1. There's no direct access through the browser to any of the private directories of the website.
1. There's no direct access through the browser to any configuration file.
1. There's no direct access to the database from outside the web servers.
1. All the necessary passwords meet the maximum complexity requirements.
1. A security and penetration test was carried out.

## Tools

1. [Webmaster World Tools](http://freetools.webmasterworld.com/) - Internet Marketing Tools
1. [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) - Website performance
1. [Web Page Test](https://www.webpagetest.org/) - Website performance
1. [Web Site Optimization](http://www.webpageanalyzer.com/) - Website performance
1. [Test Your Mobile Speed](https://testmysite.withgoogle.com) - Mobile website performance
1. [WordPress Security Scan](https://hackertarget.com/wordpress-security-scan/) - WordPress security
1. [Automated WordPress Scans](https://wpscans.com/scan) - WordPress security
1. [W3C Link Checker](http://validator.w3.org/checklink) - Check for broken links 

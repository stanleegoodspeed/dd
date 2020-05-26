## Datadog Homepage Redesign Test

Live demo: http://demo.colincole.me

### Development
Running Hugo v0.71.0
1. Clone repo
2. Run `npm install`
1. Install hugo
2. Run `hugo server -D`
3. Visit http://localhost:1313

### Deploy
1. export AWS_PROFILE=[profile]
2. hugo -D
3. hugo deploy --invalidateCDN

### Notes
The font used is National with a Roboto fallback for glyphs and other characters not included in the free download from https://klim.co.nz/retail-fonts/national/
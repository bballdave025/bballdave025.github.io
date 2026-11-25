# Homepage setup and validation

## Publish
In repository Settings > Pages, select Deploy from a branch, then main and /(root), and Save.
The intended address is https://bballdave025.github.io/.
No custom domain, DNS changes, forwarding, or hosting cancellation has been configured by this change.

## Repeat the HTML check
1. Open https://validator.w3.org/nu/.
2. Before publication, choose file upload and upload index.html (or use direct text input).
3. After publication, enter https://bballdave025.github.io/ and run the check.
4. Resolve errors and review warnings after editing.
The footer's Check HTML with W3C link runs the URL check after publication.
It is a custom text badge linking to the checker, not a W3C endorsement.

## Verified result
On November 25, 2026, the exact initial index.html was submitted directly to
https://validator.w3.org/nu/?out=json with Content-Type: text/html; charset=utf-8.
Response: {"version":"26.11.20","messages":[]}
No HTML errors or warnings were reported.
HTML conformance does not establish accessibility, security, or the correctness of linked content.

## Source and scope
Adapted from bballdave025/yahoo-verizon-turbify-html, main/index-with_partial_.html.
Added a standalone document, metadata, semantic sections, and responsive inline CSS.
Retained the LinkedIn, GitHub, and Stack Exchange destinations and the main subject areas.
Removed Turbify-specific presentation text, repeated displayed URLs, and the opacity experiment.
No external scripts, dependencies, or build system.
Licensing remains deferred.

## Domains: deferred
GitHub Pages does not process Apache .htaccess files.
If bballdave025.github.io is to remain the address shown in the browser, investigate
URL forwarding for bballdave025.com with the registrar/forwarding provider.
DNS alone does not issue an HTTP redirect.
If .com should instead remain in the address bar, use GitHub Pages custom-domain
settings and the required DNS configuration.
Preserve domain registration and any email records. The reported phishing warning
on the old domain still needs independent investigation.

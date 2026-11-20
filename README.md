# DeepMotiv landing page

Pilot-request landing page, deployed on Netlify. The form uses Netlify Forms (`pilot-request`); requests carry a `source` field filled from `?src=` in the link.

Channel addresses: `/dm`, `/li`, `/dfhq`, `/email` and `/wa` all show the same page (see `_redirects`), so web analytics counts views per channel; the form's `source` field takes the matching label when no `?src=` is given.


To redeploy,

-- Delete gh-pages branch from repo
-- Pull any changes, rebase
-- add, commit and push local changes
-- Run "npm run deploy" - It will create a new branch, gh-pages and push to it
-- Go to Settings->Pages. Update source to gh-pages branch and set domain.
-- Wait till deploy. Clear cache if neccessary.
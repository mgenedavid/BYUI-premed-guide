# BYUI Pre-Med Course Guide — Master Project

This folder is the master source for the student-built BYUI pre-med website. Future changes should update this project rather than creating separate designs.

## Pages
- index.html — Home only; course catalog is no longer embedded at the bottom.
- courses.html — Browse/search/filter courses.
- course.html?id=BIO%20180 — Course detail, approved ratings, and link to rating form.
- rate.html?id=BIO%20180 — Full student rating form. New reviews enter Pending status.
- planner.html — Dedicated four-year drag-and-drop Path Planner with MCAT prep block.
- admin.html — Local moderation prototype: approve/reject submitted reviews.

## Important before public launch
The current master is a functional front-end prototype. Planner data and reviews use browser localStorage. That means reviews are not shared between different students/devices yet, and admin access is not secure. The production phase should connect the same UI to a hosted database/auth system (for example Supabase) so all students can submit reviews and only the site admin can moderate them.

Course catalog details are prototype data and should be verified against current official BYU-Idaho sources before launch.

# Unexpected CSS Behavior Due to Inline Style Overriding

This repository demonstrates an uncommon HTML/CSS bug where inline styles unexpectedly override styles defined in an external stylesheet. This can lead to inconsistent and difficult-to-debug visual inconsistencies.

The `bug.html` file showcases the problem. The `solution.html` demonstrates a solution to avoid such issues.

**Problem:** Using inline styles can unintentionally override external styles. 

**Solution:** Prefer external stylesheets and use classes/IDs effectively. Avoid inline styles unless absolutely necessary.  If inline styles are unavoidable, ensure they are consistently applied to avoid unexpected cascades.
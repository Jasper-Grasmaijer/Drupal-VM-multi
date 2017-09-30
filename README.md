Multiple sites with NGINX in one Drupal VM instance.
====================================================
1. Clone this repo.
2. Add vendor directory to root and clone [Drupal VM](https://github.com/geerlingguy/drupal-vm).
3. Add websites codebase.
4. Run vagrant up.

TODO: Only the first database is generated correctly. Other databases have no
      user and user must be added manually.
TODO: On vagrant up the dashboard is created in root of project. Should this be
      done differently?

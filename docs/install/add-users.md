Most administration & configuration of the JupyterHub can be done from the
web UI directly. Let's add a few users who can log in!

1. Open the **Control Panel** by clicking the control panel button on the top
   right of your JupyterHub.

   ```{image} ../images/control-panel-button.png
   :alt: Control panel button in notebook, top right
   ```

2. In the control panel, open the **Admin** link in the top left.

   ```{image} ../images/admin/admin-access-button.png
   :alt: Admin button in control panel, top left
   ```

   This opens up the JupyterHub admin page, where you can add / delete users,
   start / stop peoples' servers and see who is online.

3. Click the **Add Users** button.

   ```{image} ../images/admin/add-users-button.png
   :alt: Add Users button in the admin page
   ```

   A **Add Users** dialog box opens up.

4. Type the names of users you want to add to this JupyterHub in the dialog box,
   one per line.

   ```{image} ../images/admin/add-users-dialog.png
   :alt: Adding users with add users dialog
   ```

   You can tick the **Admin** checkbox if you want to give admin rights to all
   these users too.

5. Click the **Add Users** button in the dialog box. Your users are now added
   to the JupyterHub! When they log in for the first time, they can set their
   password - and use it to log in again in the future.

Congratulations, you now have a multi user JupyterHub that you can add arbitrary
users to!

Connecting with the Geneious Biocode Plugin
===========================================

BWP Biocode Plugin Connection Details
-------------------------------------

Once the Biocode plugin has been successfully installed, you can now connect by right-clicking on the Biocode icon in the Sources panel and click "Login".

.. figure:: /images/biocode_login.png
  :align: center
  :target: /en/latest/_images/biocode_login.png

This will open the Biocode Connections window that looks like this:

.. figure:: /images/biocode_connection_details_empty.png
  :align: center
  :target: /en/latest/_images/biocode_connection_details_empty.png

Connection Name and Method
~~~~~~~~~~~~~~~~~~~~~~~~~~

Enter a value in the Connection Name so that the plug-in saves this information. Connection Method should be "Direct FIMS/LIMS".

Field Database Connection
~~~~~~~~~~~~~~~~~~~~~~~~~

In the Field Database Connection section, start out by selecting "Biocode FIMS" from the dropdown.

.. figure:: /images/biocode_fims_options.png
  :align: center
  :target: /en/latest/_images/biocode_fims_options.png

This will auto-fill the Host box with "http://biscicol.org". Enter the FIMS Username and Password that Mike Trizna assigned to you during training. Make sure to click the "Save" box, and then the "Authenticate" button to ensure you can connect to FIMS.

After authenticating, the Project drop-down will now be populated with only the FIMS projects that you have access to. Choose the project that corresponds with your country.

Tissue ID field
	For "Tissue ID field", select "tissueBarcode".

Specimen ID field
	For "Specimen ID field", select "voucherID".

Make sure to check the box next to "The FIMS database contains plate information".

Plate name field
	For "Plate name field", select "extractionPlateID".

Well field
	For "Well field", select "extractionWell".

Finally, click the "Autodetect" button to automatically populate the different taxonomy fields.

The completed Field Database Connection should look like this:

.. figure:: /images/biocode_connection_details_fims.png
  :align: center
  :target: /en/latest/_images/biocode_connection_details_fims.png

LIMS Database Connection
~~~~~~~~~~~~~~~~~~~~~~~~

In the LIMS Location section, start out by selecting "Remote MySQL Database" from the dropdown.

Server Address
	For "Server Address", copy and paste in "bwp-lims.c8jj3stgjimh.us-east-1.rds.amazonaws.com".
Port
	For "Port", make sure it is set to "3,306".
Database Name
	For "Database Name", enter "labbench".
Username and Password
	Finally, for the "Username" and "Password" boxes, enter the LIMS database Username and Password that Mike Trizna assigned to you during training.

Make sure that the checkbox next to "Save" is selected.

Your fully-completed Biocode Connection window should look like this:

.. figure:: /images/biocode_connection_details_completed.png
  :align: center
  :target: /en/latest/_images/biocode_connection_details_completed.png

Labeling images with CVAT
=========================

In this tutorial, we will guide you on how to use the `Computer Vision Annotation Tool (CVAT) <https://www.cvat.ai/>`__ in the AI4OS platform to annotate images.

Deploying CVAT
--------------

The CVAT tool is located at the top of the :ref:`Marketplace <user/overview/dashboard:Navigating the Marketplace>`, in the ``Tools`` section.

The workflow for deploying CVAT is similar to the one for :doc:`deploying a module </user/overview/dashboard>`.
In this particular case, you will need to pay attention to:

* **CVAT credentials**:
  When configuring the deployment of CVAT, you will need to enter your ``CVAT username``  and ``CVAT password`` to authenticate yourself in the CVAT instance.

* **Storage**:
  For using CVAT, it is *mandatory* to have a :ref:`storage provider linked <user/overview/dashboard:Profile>`.
  This is because, each time you delete a CVAT instance a snapshot will automatically be created in your storage.
  When you deploy a new CVAT instance, you can either start from an existing snapshot or from a blank state (no snapshot).

  .. image:: /_static/images/dashboard/storage-cvat-snapshots.png


Using CVAT
----------

In the :ref:`deployments list <user/overview/dashboard:Managing the deployments>` you will be able to see your newly created CVAT instance.
Clicking the ``Quick access`` button, you will directly enter the CVAT UI.

.. image:: /_static/images/endpoints/cvat-login.png

The enter you ``CVAT username``  and ``CVAT password`` and voilá, you're in!

.. image:: /_static/images/endpoints/cvat-projects.png

For more information on using CVAT, please follow the `official CVAT documentation <https://docs.cvat.ai/docs/>`__.

.. image:: /_static/images/endpoints/cvat-ai-screencast.gif
    :width: 1000px

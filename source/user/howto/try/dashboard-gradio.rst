Try a model from the Dashboard (Gradio)
=======================================

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; margin-bottom: 2em; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/1wDsPj_QtGo" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
    </div>

Try-me deployments are available to anyone with an :ref:`EGI Check-In account <user/overview/auth:Basic authentication>`.

To create a deployment, :ref:`select a module in the Marketplace <user/overview/dashboard:Navigating the Marketplace>` and click on ``Try ▼ Nomad (Gradio)``.

.. image:: /_static/images/dashboard/module.png

This will open a new tab where the new try-me environment will be deployed (this can take a few seconds).

Once this is deployed, you will see a `Gradio <https://www.gradio.app/>`__ interface where you can make your prediction. In the left hand-side, you will be shown the prediction inputs and in the right hand side you will be shown the prediction outputs.

.. image:: /_static/images/endpoints/gradio.png

.. admonition:: Advice for model developers
    :class: info

    If you are a model developer looking to improve the looks of your module's UI, take a look to our :ref:`developer guidelines<user/overview/api:Additional considerations>`.

Take into account that this try-me endpoints are offered to the general public, thus run on limited resources. This means that we limit the maximum duration of a try-me environment to 10 minutes. In addition, resource-hungry operations (eg. video processing) might not work as expected.

In line with this, we also limit the number of try-me endpoints that the user can deploy at the same time. If you reach the limit, you can wait until one of your previous deployments is automatically deleted or you can delete it manually in the ``Try me`` section of the Dashboard.

.. image:: /_static/images/dashboard/tryme.png

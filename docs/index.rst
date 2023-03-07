Agilicious: Open-Source and Open-Hardware Agile Quadrotor for Vision-Based Flight
=================================================================================
.. raw:: html

         <center>
          <style>
          button {
              background-color: #7286D3;
              color: black;
              border-radius: 50px;
              width: 400px;
              height: 100px;
              font-size: 40px;
              box-shadow: 4px 4px 4px #888;
          }
        </style>
        <li class="nav-link"> <a href="https://form.jotform.com/230332943688361"><button> Request Access!</button></a>
        <br>
        </center>

|

.. image:: https://user-images\.githubusercontent\.com/17403970/174497361-aa212d77-7036-4f36-840d-c48cab492ac2\.gif
   :width: 600px

.. image:: https://user-images.githubusercontent.com/21340299/174775412-9595e3ed-7ef9-403b-ab08-0dbe4126243f.gif
   :width: 298px

.. image:: https://user-images.githubusercontent.com/21340299/174776470-3a505384-c01e-4759-9173-973aa2bff27f.gif
   :width: 298px

.. image:: https://user-images.githubusercontent.com/21340299/174776626-9c0912ac-ed38-4470-a3cf-d8b80dff4e99.gif
   :width: 298px

.. image:: https://user-images.githubusercontent.com/21340299/174776748-87c4d27c-2dd0-4aec-9b4c-64fdab4d5c14.gif
   :width: 298px

`Read the Paper <https://rpg.ifi.uzh.ch/docs/ScienceRobotics22_Foehn.pdf>`_ and `watch the full Video! <https://www.youtube.com/watch?v=fNYxPLyJ5YY>`_

Agile flight done right!
------------------------
**Agilicious** is a co-designed hardware and software framework tailored to autonomous, agile quadrotor flight, which has been developed and used since 2016 at the `Robotics and Perception Group (RPG) <https://rpg.ifi.uzh.ch/>`__ of the University of Zurich. Agilicious is described in this `Science Robotics 2022 paper <https://rpg.ifi.uzh.ch/docs/ScienceRobotics22_Foehn.pdf>`__. It is completely open-source and open-hardware and supports both model-based and neural-network-based controllers.  Also, it provides high thrust-to-weight and torque-to-inertia ratios for agility, onboard vision sensors, GPU-accelerated compute hardware for real-time perception and neural-network inference, a real-time flight controller, and a versatile software stack. In contrast to existing frameworks, Agilicious offers a unique combination of flexible software and high-performance hardware. Agilicious has been used in over 30 scientific papers at our lab, including trajectory tracking for drone racing scenarios at up to 5g and 70km/h (`SciRob21_Foehn <https://rpg.ifi.uzh.ch/docs/ScienceRobotics21_Foehn.pdf>`_, `Video <https://youtu.be/ZPI8U1uSJUs>`_), vision-based acrobatic flight (`RSS20 Kaufmann <https://rpg.ifi.uzh.ch/docs/RSS20_Kaufmann.pdf>`_,  `Video <https://youtu.be/2N_wKXQ6MXA>`_), obstacle avoidance in both structured and unstructured environments using solely onboard perception (`SciRob21_Loquercio <https://rpg.ifi.uzh.ch/docs/Loquercio21_Science.pdf>`_, `Video <https://www.youtube.com/watch?v=m89bNn6RFoQ>`_), and hardware-in-the-loop simulation in virtual-reality environments. Thanks to its versatility, we believe that Agilicious supports the next generation of scientific and industrial quadrotor research.
Agilicious allows to seamlessly develop, test, reproduce and benchmark control algorithms such as Non-linear Model Predictive Control (MPC), differential-flatness-based control (DFBC) and INDI (Incremental Non-linear Dynamic Inversion) (`TRO 2022, Sun <https://rpg.ifi.uzh.ch/docs/Arxiv21_MPC_Sun.pdf>`__, `Video <https://www.youtube.com/watch?v=XpuRpKHp_Bk>`__).
Agilicious also includes our state-of-the-art, high-fidelity hybrid simulator, which combines Blade Element Momentum (BEM) theory for the nominal model and learning techniques for the residuals (`RSS 2021, Bauersfeld <https://rpg.ifi.uzh.ch/docs/RSS21_Bauersfeld.pdf>`__, `Video <https://www.youtube.com/watch?v=Nze1wlfmzTQ>`__).

The full list of publications using Agilicious can be found `here <https://rpg.ifi.uzh.ch/aggressive_flight.html>`_.

.. toctree::
    :maxdepth: 2
    :caption: About

    License <license>
    Credits <credits>
    Dependencies <dependencies>


.. toctree::
    :maxdepth: 2
    :caption: Setup

    What's in it for you? <introduction>
    Getting Started <setup/getting_started>
    Dockerized Build <setup/docker>
    Code Documentation with Doxygen <setup/doxygen>

.. toctree::
    :maxdepth: 3
    :caption: Documentation

    Modules <modules/overview>
    Simulation <simulation/overview>
    Hardware <hardware/overview>
    Integration with ROS <integration/ros>
    Integration with Flightmare <integration/flightmare>

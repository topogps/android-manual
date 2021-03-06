.. _sec-route-record:

Recording routes
----------------
When recording your route all the locations your are visiting are collected. If you finish the recording, you can save the locations as a route.

To record a route you need make sure that Topo GPS is given access to your precise location while using the app in the iOS Settings.

Starting a recording
~~~~~~~~~~~~~~~~~~~~
To start a route recording, you have to open the :ref:`routes screen <sec-routes-screen>` and select the tab 'Record'. An example is below:

.. figure:: ../_static/route-rec1.png
   :height: 568px
   :width: 320px
   :alt: Record screen Topo GPS
   
   *The route record screen.*

In the 'Record' tab of the routes screen you can start a route recording by tapping the 'Record route' button.

Alternatively, you can also start recording a route from the :ref:`main screen <sec-main-screen>`, by tapping the :ref:`record timer <ss-rec-timer>` on the dashboard. A pop-up will appear in which you are asked whether you want to start a recording as in the example below:

.. figure:: ../_static/route-rec2.png
   :height: 568px
   :width: 320px
   :alt: Record screen Topo GPS
   
   *Starting a route recording from the dashboard.*

If you tap 'Start' the route recording will be started.


Recording route
~~~~~~~~~~~~~~~
If you have started a recording and return to the main screen, you will see that a red line will appear on the map
if you are moving. This red line indicates your movement. An example is displayed in the figure below:

.. figure:: ../_static/route-record1.png
   :height: 568px
   :width: 320px
   :alt: Recording route Topo GPS

   *Recording a route. The red line indicates your movement.*

The :ref:`record timer <ss-rec-timer>` on the dashboard indicates the duration of the current recording.
In the figure above this is 0h17m. If you tap the timer you can :ref:`end the recording <ss-route-record-end>`.

The :ref:`record distance meter <ss-rec-distance>` on the dashboard indicates
the length of a recorded route. In the example above this is 778 m. If you tap the record distance meter the map will be zoomed to the recorded route.

You can modify the color, width and transparency of the record line in the 
:ref:`settings <sec-settings-styles>`.

While recording you can safely lock your device or switch to another app.
This will not interrupt the recording. In the top of the screen you can see that Topo GPS is using your location in the background. 
In some devices the clock gets a blue background, on other devices the whole status bar turns blue. If you tap the blue clock or the blue statusbar, you will return to Topo GPS.

If you tap on the line of the recorded route on the main map, the record screen will be opened. You can view a live altitude and speed profile. You can tap these :ref:`profiles <sec-route-profiles>` to view them in more detail. 

If you have :ref:`loaded <sec-routes-load>` one or more routes on the map, you can record a route at the same time. An example is shown below:

.. figure:: ../_static/route-record3.png
   :height: 568px
   :width: 320px
   :alt: Recording route Topo GPS

   *Recording and showing a route.*

The blue line indicates the loaded route with a length of 1.9 km, the red line the recorded route
with a length of 778 m.

Recording a route will cost a considerable amount of energy. Therefore regularly check your battery level while recording to make sure your device is not running out of power. Pause or finish a recording when your are no longer moving.

.. _ss-route-record-end:

Ending recording
~~~~~~~~~~~~~~~~
You can end the a recording of a route by tapping the :ref:`record timer <ss-rec-timer>` on the dashboard or by tapping 'Stop recording' in
the record screen. The record screen can be opened by tapping the line of the recorded route on the map,
and by selecting the record tab in the :ref:`routes screen <sec-routes-screen>`.

A pop-up will appear asking you to stop the recording like in the example below: 

.. figure:: ../_static/route-record4.png
   :height: 568px
   :width: 320px
   :alt: Stopping route recording Topo GPS

   *Ending recording a route.*

If you press 'Stop' the recording will be ended and a screen is presented in which you can :ref:`save the recorded route <ss-record-save>`.

.. _ss-route-record-pause:

Pause recording
~~~~~~~~~~~~~~~
If you press 'Pause' in the pop-up which appears when :ref:`ending a route recording <ss-route-record-end>`, the recording will be paused. 

The :ref:`record timer <ss-rec-timer>` on the dashboard will be set to '--:--' during a pause. The :ref:`record distance meter <ss-rec-distance>` will show the recorded distance as you can see below:

.. figure:: ../_static/route-record5.png
   :height: 568px
   :width: 320px
   :alt: Pausing route recording Topo GPS

   *The recording of a route has been paused, which can be seen from the record timer and record distance meter.*
   
.. _ss-record-restart:

Restart recording
~~~~~~~~~~~~~~~~~
To restart a paused recording you have tap :ref:`record timer <ss-rec-timer>` or
the ???Restart recording??? button in the top of the record screen. The following pop-up will then appear:

.. figure:: ../_static/route-record6.png
   :height: 568px
   :width: 320px
   :alt: Restarting recorded route Topo GPS

   *Restarting the recording of a route.*

If you press 'Restart' the recording will be continued. If you press 'Stop'
the recording of a route will be finished and you will be
given the possibility to :ref:`save the recorded route <ss-record-save>`.

.. _ss-record-save:

Saving recording
~~~~~~~~~~~~~~~~
If you have :ref:`stopped the recording of a route <ss-route-record-end>` a screen will appear
in which you can save the recorded route. An example is displayed below:

.. figure:: ../_static/route-rec3.png
   :height: 568px
   :width: 320px
   :alt: Saving recorded route Topo GPS

   *Saving a recorded route.*

In this screen you can subsequently enter the title, the author and a description. 

Based on the start and finish point of the route an automatic suggestion for the route title
will be made. This suggestion appears in the title field if you do not enter a title yourself.
If you do not enter a title, the suggestion will be used when saving the route. 

To ensure automatic title suggestion functions properly, the option :ref:`???Addresses - Find automatically??? <sec-settings-addresses>` should
be enabled in the :ref:`settings <ss-settings>`.

If you press the '>' on the right hand side of the title you can add an URL.

If you press the '>' on the right hand side of the author you can add contact information, and copyright and license details. If you save a route also the author and copyright details will be saved for future use. If you record or plan a new route, the same author and copyright details will already be filled in. Therefore you do not have to reenter these details when saving the next recorded route.

You can alter the route type by pressing the route type field. If you save the route, the current route type will be used as a suggestion for the next saved route. If you for example only record bicycles routes you therefore only have to set the route type once.

Waypoints that are currently shown on the map can be included with the route by the setting 'Include waypoints'. If you tap this setting you can change it. You can choose between including all waypoints that are on the map, waypoints near the route, waypoints created during recording, and no waypoints. 
The recommended settings is: 'waypoints created during recording'. Then only waypoints that are loaded on the map and created during the recording will be added to the route. If you choose for waypoints near route, you can determine the maximal distance of the waypoints to the route. Be careful with setting this setting to all waypoints. This might cause adding waypoints which are far a way and hence irrelevant to a route.

If you are done, you can press 'Save' on the top right to save the recorded route.
If you do not want to save the route you can press 'Cancel' on the top left.

The route will be saved into the folder that is currently opened in the :ref:`routes tab of the routes screen <sec-routes-load>`.

After you have saved the recorded route, a pop-up will appear that asks you if you would like to share your route with Topo GPS or with another app (for this tap 'More). If you do not want to share the recorded route, you can tap 'Cancel'.

If you choose Topo GPS you can :ref:`share your route with other Topo GPS users <sec-routes-share-topo-gps>`, so that they can :ref:`import your recorded
route <ss-routes-import-shared>`. 

It is also possible to :ref:`share the recorded route <sec-routes-share-topo-gps>` later.

The screen that appears is the :ref:`route details screen <sec-route-details>`. You can load the 
recorded route on the map by tapping the 'Show on map??? button on the top right of this screen.

You can also :ref:`load the recorded route on the map <sec-routes-load>` at a later time.

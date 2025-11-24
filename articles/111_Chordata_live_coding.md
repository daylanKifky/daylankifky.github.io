# Live coding performance

An on-stage performance combining live dance, real-time motion capture, and video generation through a live-coding interface.

![chordata livecoding at codemotion amsterdam](images/111_Chordata_livecoding_4.png)

In these performances, we captured and processed the movements of the dancer on stage, combining them with live-generated music to create real-time graphics using TouchDesigner.

For this edition, at the request of [Codemotion for the Amsterdam 2019 tech conference](https://events.codemotion.com/conferences/amsterdam/2019/), we included a live-coding interface that took advantage of the TMUX buffer, a VIM editor, and a Python infrastructure which transmitted and evaluated the live-generated script contents into a TouchDesigner patch. The images projected on the big screen were the result of the interaction between the team components:

- Arianna Serra: Dance
- Lorenzo Micozzi Ferri: Music and TouchDesigner
- Bruno Laurencich: Mocap and Live-coding

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
  <iframe
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
    src="https://www.youtube.com/embed/NEPMSrVD6cU?si=muVo3xa6DlUSphmn"
    title="YouTube video player"
    frameborder="0"
    referrerpolicy="strict-origin-when-cross-origin"
    allowfullscreen
  ></iframe>
</div>


This [live-coding infrastructure was released](https://gitlab.com/chordata/livecoding_touchdesigner) under an Apache 2.0 License.

These mocap based performances gave birth to the [Chordata motion capture system](105_Chordata_mocap_system.html).

![Touchdesigner Flow](images/111_Touchdesigner_flow.png)

<script type="application/json">
{
  "technologies": [
    "Python",
    "TouchDesigner",
    "VIM",
    "TMUX",
    "Blender"
  ],
  "description": "An on-stage performance combining live dance, real-time motion capture, and video generation through a live-coding interface",
  "tags": [
    "Live Coding",
    "Live Performance",
    "Motion Capture",
    "Interactive Art",
    "Real-time Graphics",
    "Open-Source",
    "Creative Direction"
  ]
}
</script>

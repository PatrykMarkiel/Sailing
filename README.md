# Assumptions
It's 2d game about sailing boat.
A sailing boat is floating among the seas and it has to avoid object like boulders, ships etc but sailing isn't that simple because there is influence of wind which can impact on speed of user's boat.
## Wind mechanic && Boat positions
<table>
  <tr>
    <th>Kąt Wiatru (°)</th>
    <th>Pozycja</th>
    <th>Prędkość (Nm/h)</th>
  </tr>
  <tr>
    <td>&lt; 30° lub &gt; 330°</td>
    <td>W martwym punkcie (In Irons)</td>
    <td></td>
  </tr>
  <tr>
    <td>30° - 45°</td>
    <td>Blisko kursu (Close Hauled, Prawo)</td>
    <td></td>
  </tr>
  <tr>
    <td>45° - 60°</td>
    <td>Blisko kursu (Close Reach, Prawo)</td>
    <td></td>
  </tr>
  <tr>
    <td>90°</td>
    <td>Kurs na burtę (Beam Reach, Prawo)</td>
    <td></td>
  </tr>
  <tr>
    <td>100° - 135°</td>
    <td>Kurs na wiatr (Broad Reach, Prawo)</td>
    <td></td>
  </tr>
  <tr>
    <td>150° - 180°</td>
    <td>Kurs z wiatrem (Running)</td>
    <td></td>
  </tr>
  <tr>
    <td>180°</td>
    <td>Kurs na burtę (Beam Reach, Lewo)</td>
    <td></td>
  </tr>
  <tr>
    <td>190° - 225°</td>
    <td>Kurs na wiatr (Broad Reach, Lewo)</td>
    <td></td>
  </tr>
  <tr>
    <td>225° - 270°</td>
    <td>Kurs na burtę (Beam Reach, Lewo)</td>
    <td></td>
  </tr>
  <tr>
    <td>270° - 300°</td>
    <td>Blisko kursu (Close Reach, Lewo)</td>
    <td></td>
  </tr>
  <tr>
    <td>300° - 315°</td>
    <td>Blisko kursu (Close Hauled, Lewo)</td>
    <td></td>
  </tr>
  <tr>
    <td>&lt; 30° lub &gt; 330°</td>
    <td>W martwym punkcie (In Irons)</td>
    <td></td>
  </tr>
</table>



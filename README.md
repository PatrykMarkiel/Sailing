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
    <td>&lt; 30° or &gt; 330°</td>
    <td>In Irons</td>
    <td></td>
  </tr>
  <tr>
    <td>30° - 45°</td>
    <td>Close Hauled(right)</td>
    <td></td>
  </tr>
  <tr>
    <td>45° - 60°</td>
    <td>Close Reach(right)</td>
    <td></td>
  </tr>
  <tr>
    <td>90°</td>
    <td>Beam Reach(right)</td>
    <td></td>
  </tr>
  <tr>
    <td>100° - 135°</td>
    <td>Broad Reach(right)</td>
    <td></td>
  </tr>
  <tr>
    <td>150° - 180°</td>
    <td>Running</td>
    <td></td>
  </tr>
  <tr>
    <td>180°</td>
    <td>Beam Reach(left)</td>
    <td></td>
  </tr>
  <tr>
    <td>190° - 225°</td>
    <td>Broad Reach(left)</td>
    <td></td>
  </tr>
  <tr>
    <td>225° - 270°</td>
    <td>Beam Reach(left)</td>
    <td></td>
  </tr>
  <tr>
    <td>270° - 300°</td>
    <td>Close Reach(left)</td>
    <td></td>
  </tr>
  <tr>
    <td>300° - 315°</td>
    <td>Close Hauled(left)</td>
    <td></td>
  </tr>
</table>
if wind blows between the angles of the sail setting speed reduces to half of maximum speed


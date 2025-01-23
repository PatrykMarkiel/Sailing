# Assumptions
It's 2d game about sailing boat.
A sailing boat is floating among the seas and it has to avoid object like boulders, ships etc but sailing isn't that simple because there is influence of wind which can impact on speed of user's boat.
## Wind mechanic && Boat positions
<table>
  <tr>
    <td>
      Wind
    </td>
    <td>
      Position
    </td>
    <td>
      Speed
    </td>
  </tr>
    <tr>
    <td>
      Less than 30&#xb0; or greater than 330&#xb0;
    </td>
    <td>
      In Irons
    </td>
    <td>
      0 Nh/h
    </td>
  </tr>
  <tr>
    <td>
       Between 30-45&#xb0;
    </td>
    <td>
       Close Hauled (Left))
    </td>
    <td>
    </td>
  </tr>
  <tr>
      <td>
          Between 45-60&#xb0;
      </td>
      <td>
           Close Reach (Left)
      </td>
      <td>
    </td>
  </tr>
   <tr>
    <td>
      90&#xb0;
    </td>
    <td>
          Beam Reach(Left)
    </td>
    <td>
    </td>
  </tr>
    <tr>
    <td>
             100&#xb0;-135&#xb0; 
    </td>
    <td>
      Broad Reach (Right)
    </td>
    <td>
    </td>
  </tr>
    <tr>
      <td>
        Between 300-315&#xb0;
      </td>
      <td>
        Close Reach (Right)
      </td>
      <td>
    </td>
  </tr>
    <tr>
      <td>
        Between 315-330&#xb0;
      </td>
      <td>
              Close Hauled (Right)
      </td>
      <td>
    </td>
  </tr>
    <tr>
    <td>
          180&#xb0;
    </td>
    <td>
        Beam Reach(Right)
    </td>
    <td>
    </td>
  </tr>
  <tr>
    <td>
              190&#xb0;-225&#xb0;
    </td>
    <td>
            Broad Reach (Left)
    </td>
    <td>
    </td>
  </tr>
      <tr>
    <td>
      Wind from behind
    </td>
    <td>
             Running
    </td>
    <td>
    </td>
  </tr>
</table>
<table>
  <tr>
    <th>Kąt Wiatru (°)</th>
    <th>Pozycja</th>
    <th>Prędkość (Nm/h)</th>
  </tr>
  <tr>
    <td>&lt; 30° lub &gt; 330°</td>
    <td>W martwym punkcie (In Irons)</td>
    <td>0</td>
  </tr>
  <tr>
    <td>30° - 45°</td>
    <td>Blisko kursu (Close Hauled, Lewo)</td>
    <td>Zmienna</td>
  </tr>
  <tr>
    <td>45° - 60°</td>
    <td>Blisko kursu (Close Reach, Lewo)</td>
    <td>Zmienna</td>
  </tr>
  <tr>
    <td>90°</td>
    <td>Kurs na burtę (Beam Reach, Lewo)</td>
    <td>Zmienna</td>
  </tr>
  <tr>
    <td>100° - 135°</td>
    <td>Kurs na wiatr (Broad Reach, Prawo)</td>
    <td>Zmienna</td>
  </tr>
  <tr>
    <td>150° - 180°</td>
    <td>Kurs z wiatrem (Running)</td>
    <td>Zmienna</td>
  </tr>
  <tr>
    <td>180°</td>
    <td>Kurs na burtę (Beam Reach, Prawo)</td>
    <td>Zmienna</td>
  </tr>
  <tr>
    <td>190° - 225°</td>
    <td>Kurs na wiatr (Broad Reach, Lewo)</td>
    <td>Zmienna</td>
  </tr>
  <tr>
    <td>225° - 270°</td>
    <td>Blisko kursu (Close Reach, Prawo)</td>
    <td>Zmienna</td>
  </tr>
  <tr>
    <td>270° - 300°</td>
    <td>Blisko kursu (Close Hauled, Prawo)</td>
    <td>Zmienna</td>
  </tr>
  <tr>
    <td>&gt; 330°</td>
    <td>W martwym punkcie (In Irons)</td>
    <td>0</td>
  </tr>
</table>



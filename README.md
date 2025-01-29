# Game Design Document: Sailing Challenge

# Overview

Sailing Challenge is a 2D sailing game where the player controls a sailing boat navigating the open sea. The primary objective is to avoid obstacles such as boulders, other ships, and reefs while managing the effects of wind on the boat's speed. The challenge comes from the dynamic wind system, which influences the boat's movement based on direction and strength.


---

# Game Mechanics

## Boat Movement

Speed depends of n value which is randomly set by program and is changing in the time

The player can adjust the boat’s angle to optimize speed and avoid obstacles.

Speed is affected by wind direction and strength.

If the boat is in an unfavorable wind condition, it slows down.

The player must strategically adjust their angle to maximize speed and maneuver effectively.

Movement is realistic the sailboat can't turn in place.

---

# Wind Mechanics

The Sailing boat is accelerates til it reaches n value or max speed(it depends of sail position)

If the wind is blowing between the angles of the sail setting, speed is reduced to half of the maximum possible speed.

## Wind Direction and Boat Speed

The wind direction determines how much the boat's speed is affected. The boat's sail position relative to the wind direction categorizes its effectiveness into sailing positions:
<table>
  <tr>
    <th>Angle of blowing (°)</th>
    <th>Position</th>
    <th>Speed %</th>
  </tr>
  <tr>
    <td>&lt; 30° or &gt; 330°</td>
    <td>In Irons</td>
    <td>0%</td>
  </tr>
  <tr>
    <td>30° - 45°</td>
    <td>Close Hauled (Right)</td>
    <td>50%</td>
  </tr>
  <tr>
    <td>45° - 60°</td>
    <td>Close Reach (Right)</td>
    <td>75%</td>
  </tr>
  <tr>
    <td>60° - 90°</td>
    <td>Between Close Reach & Beam Reach</td>
    <td>87.5%</td>
  </tr>
  <tr>
    <td>90°</td>
    <td>Beam Reach (Right)</td>
    <td>100%</td>
  </tr>
  <tr>
    <td>100° - 135°</td>
    <td>Broad Reach (Right)</td>
    <td>90%</td>
  </tr>
  <tr>
    <td>135° - 150°</td>
    <td>Between Broad Reach & Running</td>
    <td>85%</td>
  </tr>
  <tr>
    <td>150° - 180°</td>
    <td>Running</td>
    <td>80%</td>
  </tr>
  <tr>
    <td>180°</td>
    <td>Beam Reach (Left)</td>
    <td>100%</td>
  </tr>
  <tr>
    <td>190° - 225°</td>
    <td>Broad Reach (Left)</td>
    <td>90%</td>
  </tr>
  <tr>
    <td>225° - 270°</td>
    <td>Beam Reach (Left)</td>
    <td>100%</td>
  </tr>
  <tr>
    <td>270° - 300°</td>
    <td>Close Reach (Left)</td>
    <td>75%</td>
  </tr>
  <tr>
    <td>300° - 315°</td>
    <td>Close Hauled (Left)</td>
    <td>50%</td>
  </tr>
  <tr>
    <td>315° - 330°</td>
    <td>Between Close Hauled & In Irons</td>
    <td>25%</td>
  </tr>
</table>
![1](https://github.com/user-attachments/assets/8d8267da-890c-4ec1-b9d2-3961410f9b54)







---
title: "Frequency domain feedback control of temperature for a simplified earth system model"
excerpt: >	
  _Controls and Dynamics,Climate Engineering (2025)_ <br/>
   During my MS at Cornell, I took an academic course on Feedback Control Systems under Prof. Douglas MacMartin. For the course project, I designed a feedback controller in the frequency domain. Its goal was to stabilize Earth's surface temperature in the presence of a ramped disturbance (greenhouse gases) by controlling the amount of radiative forcing the Earth receives. I analyzed the controller's performance, including settling time and possible saturation of SAI.<br/>
  <table style="border-collapse:collapse; border:0; width:100%;">
    <tr>
      <td style="border:0; padding-right:5px; width:50%;">
        <img src="/images/feedback_control_step.png"
             alt="Step Response"
             style="max-width:100%; height:auto; display:block;">
      </td>
      <td style="border:0; padding-left:5px; width:50%;">
        <img src="/images/system_response_to_ramp.png"
             alt="Ramp input vs System response"
             style="max-width:100%; height:auto; display:block;">
      </td>
    </tr>
  </table>

collection: projects
---
[Click here]( https://harshmeel.github.io/files/Earth_temperature_feedback_control.pdf) for detailed report of the project.

Stratospheric Aerosol Injection or Climate Engineering is essentially a feedback control method to stabilize the Earth’s climate against GHG-caused warming, using a spread of sulfate aerosols high in the atmosphere to reflect back a portion of the sun’s incoming radiation. For my project, I utilized a simplified representation of the Earth’s energy balance as a semi-infinite box diffusion model, defined in MacMartin et al. 2013. The controller was able to meet the performance requirements on the zero steady state error, settling time < 10 years and good phase-gain margins. It was also demonstrated that the actual SAI response will saturate against the GHG ramping after a certain period of time.


<img src="/images/SAI-demonstration.jpg" alt="SAI_demonstration" width="700px">




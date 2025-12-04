# 2026 CDM Community Roadmap 



<table>
  <tr>
    <th style="width: 12%;background:#fafafa;border:1px solid #ddd;">Working Group<br>Chair</th>
    <th style="width: 22%;">1Q 2026</th>
    <th style="width: 22%;">2Q 2026</th>
    <th style="width: 22%;">3Q 2026</th>
    <th style="width: 22%;">4Q 2026</th>
  </tr>
  <tr>
    <td><b>Steering WG</b><br>David Shone</td>
    　<td><ul>
        <li>Annual Review of governance</li>
        <li>Establish release schedule</li>
       <li>Agree 2026 roadmap</li>
       <li>Re-ratify TOM</li>
       <li>Agree objectives 2026+</li>
      </ul></td>
      <td><ul>
        <li>BAU </li>
      </ul></td>
      <td><ul>
        <li>BAU </li>
        <li>Nominations for Chair from Jan 2027 </li>
      </ul></td>
      <td><ul>
        <li>BAU </li>
        <li>Vote / appoint Chair from Jan 2027 </li>
        <li>Agree & publish Roadmap for 2027 </li>
      </ul></td>
     </tr>
  <tr>
    <td><b>Technical Architecture WG</b><br>tba</td>
    　<td><ul>
       <li>Python generator upgrade to handle functions
       <li>Prioritised items from SWG November 2025</li>
      </ul></td>
      <td><ul>
        <li>Python generator upgrade to handle functions</li>
        <li>Serialisation- Ph2/3 (Backward/Forward Compatibility)</li>
        <li>Prioritised items from SWG November 2025</li>
      </ul></td>
      <td><ul>
        <li>Serialisation- Ph2/3 (Backward/Forward Compatibility)</li>
        <li>Prioritised items from SWG November 2025</li>
      </ul></td>
      <td><ul>
        <li>Serialisation- Ph2/3 (Backward/Forward Compatibility)</li>
        <li>Prioritised items from SWG November 2025</li>
      </ul></td>
     </tr>
  </tr>
    <tr>
    <td><b>Contribution Review WG</b><br>Rotating</td>
    　<td><ul>
       <li>CDM7.0 Release- end Feb</li>
       <li>Continued managed release service</li>
       <li>BAU </li>
      </ul></td>
      <td><ul>
       <li>Continued managed release service</li>
       <li>BAU </li>
      </ul></td>
      <td><ul>
       <li>Continued managed release service</li>
       <li>BAU </li>
      </ul></td>
      <td><ul>
       <li>Continued managed release service</li>
       <li>BAU </li>
      </ul></td>
     </tr>
  </tr>
    <tr>
    <td><b>Collateral WG</b><br>Vernon Alden-Smith</td>
    　<td><ul>
       <li>Deliver outstanding test packs for IM/VM</li>
       <li>Contribute CSA amendments</li>
       <li>ECS extensions identified by community</li>
      </ul></td>
      <td><ul>
        <li>Develop CSA implementation guide for compkles causes</li>
      </ul></td>
      <td><ul>
        <li>Develop functions for collateral workflows</li>
      </ul></td>
      <td><ul>
        <li>TBC</li>
      </ul></td>
     </tr>
  </tr>
    <tr>
    <td><b>Securities Lending WG</b><br>Chris Rayner</td>
    　<td colspan="4" ><ul>
       <li>Lifecycle development & contributions</li>
       <li>DRR dependencies for SFTR</li>
       <li>CDM Best Practices for Securities Lending</li>
      </ul></td>
     </tr>
  </tr>
    <tr>
    <td><b>Derivatives WG</b><br>Lyteck Lynhiavu</td>
    　<td colspan="4" ><ul>
        <li>Member modelling proposals</li>
        <li>Product expansion for DRR</li>
      </ul></td>
     </tr>
  </tr>
    <tr>
    <td><b>ICMA Repo & Bonds WG</b><br>Gabriel Callsen</td>
    　<td colspan="4" ><ul>
        <li>Develop SFTR reporting model and functions</li>
        <li>Expand bond/debt/security coverage and related events</li>
        <li>Expand domain specific helper functions</li>
        <li>CDM training and implementation sessions</li>
        <li>On-going support and adoption projects</li>
      </ul></td>
     </tr>
  </tr>
    <tr>
    <td><b>ISDA Legal Agreement WG</b><br>Vernon Alden-Smith</td>
    　<td colspan="4" ><ul>
       <li>ISDA Document contributions (Community led)</li>
      </ul></td>
     </tr>
  </tr>
    <tr>
    <td><b>ISDA DRR WG WG</b><br>Tabish Ahmed</td>
    　<td><ul>
       <li>SEC</li>
      <li>ReportableInformation improvements</li>
      </ul></td>
      <td><ul>
        <li>SFTR (led by ISLA & ICMA)</li>
        <li>Strate</li>
        <li>Traceability Tool</li>
        <li>ReportableInformation improvements</li>
      </ul></td>
      <td><ul>
        <li>MiFiR EU build</li>
        <li>Strate</li>
        <li>Traceability Tool</li>
      </ul></td>
      <td><ul>
        <li>MiFiR EU UAT</li>
      </ul></td>
     </tr>
  </tr>
</table>



# 2025 CDM Roadmap from FINOS, ICMA, ISDA, & ISLA

![](.github/cdm-roadmap-2025-1.png)

![](.github/cdm-roadmap-2025-2.png)

# 2024-5 Release schedule
![CDM Release Guidelines Task Force Summary - July 2 2024](https://github.com/finos/common-domain-model/assets/7291088/9542593d-b63e-4447-8a21-cfec1df65221)

Release States
===============
Release states are defined as follows:
* Development – versions that include new designs from the “main” branch that are still under development.  All tests must pass but the model may continue to evolve before being released into production.
* Production - the "latest and greatest" stable version that ideally everyone should upgrade to, and where enhancements compatible with the existing models will be included. We should aim for a release to be in Production for around a year if we can, to alleviate upgrade costs to consumers. 
* Maintenance – when a new Production version is released then the current Production will go into Maintenance. Only critical bug fixes and changes related to critical regulatory requirements should be ported to Maintenance releases. Otherwise, functional changes would not be ported to maintenance releases.  The intention would be to have only 1 version at a time in maintenance, so each time a new Production version drops, the previous Maintenance release would go to Unsupported.
* Unsupported/End of Life – There will be no bug fixes or other support for the version.  TBD: We may perform security scans on some more recent unsupported versions and report any identified vulnerabilities, but will not perform security remediations.

  
At any point we want a maximum of 1 centrally supported development version, 1 production version, and one maintenance version.



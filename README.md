# RMF - Risk Management Framework
Detail understanding on the Purpose and Outcome for each step in Risk Management Framework (RMF)


### <ins>Step 1: **CATEGORIZE**<ins>
&nbsp;&nbsp;&nbsp;<ins>PURPOSE:</ins><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The organization must put risk management processes and tasks in place. This will allow the organization to determine the adverse impact in respect to the loss of cofidentiality, integrity, availability of systems (CIA Triad security). This also include how information is processed, where and how information is stored, and how information is transmitted by those system.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Information owner and / or system owner must idetifiy and document the type of information processesd. Is the information PII data,; is it credit card data, etc. Compling, categorizing, and documenting this information is vital in determining the risk to the organization. By assigning a security impact value ( Low, Moderate, High, Critica ), this allows detail categorize and context behind understanding the risk to categorize the different information types. Information storage and transmitted is critical element in categorization phase, as infomration at rest and when being transmitted should always be encrypted.<br>

&nbsp;&nbsp;&nbsp;<ins>OUTCOME:</ins><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The desired outcome of effectively executing on this phase should be; 1. Documentation on system characheristics. 2. Security categorization of the systems and the information residing in those system. 3. Review and approval by authorizing bodies on categorization decision.<br>

***Refence the following: FIPS 199 & NIST SP 800-60 Volume I and Volume II***


### Step 2: **SELECT**
		Purpose: 
			The purpose of this phase 2, is to select, tailor, and document the security controls necessary to protect the system and organization commensurate with risk. Thier are several task involved In order to sucessfully complete this phase. Frist, select the security control baseline on the categorization results. Second, tailor the security control baseline by applying overlays, supplementing the baseline with addtional constrols, or omitting controls as necessary. Finally, document the selected controls in the system security plan.
		
			The security controls are safeguards and countermeasures prescribed to protect the confidentiality, integrity, and availability of the system and facilitate reciprocity. Selected controls can be inherited common, hybrid, or system-specific controls. Security plan documents on how the controls meet the security requirements and is a key to success for the authorization process. 	

		OUTCOME:
			The desired outcome from this phase should be the following. Security and tailor the control baselines. This baseline provides a set of minimum security controls that should be implemented to protect the system. However, the baseline is not a one-size-fits-all solution, and it must be tailored to the specific needs of the organization and the system. The tailoring process involves applying overlays, aupplementing the baseline with additional controls, or omitting controls as necessary, based on the unique risks and requirements of the system.

			Next, the selected security controls are designated as either system-specific, hybrid, or common controls. System-specific controls are thos that are implemented solely with the doundaries of the information system. Hybrid controls are those that are implemented partially within the system and partially within the system and partially inherited from other systems or environments and are not implemented within the system itself.

			Once the controls are designated, they are allocated to specific system components or elements. This allcation process ensures each control is assigned to the appropriate part of the system, making it easier to implement and monitor the controls effectively. The allocation of controls also helps to identify any potential gaps or overlaps in the control implementation, allowing for better coordination and integration of security measures. By selecting and allocating controls involves developing a system-level continuous monitoring strategy. This strategy outlines how effectiveness of the implemented security controls will be monitored and assessed on an ongoing basis. Continuous monitoring is essential for ensuring system remains secure and compliant with organizational policies and regulatory reuirements, even as the system and its environment evolve over time. 

			Finally, the security and privacy plans that reflect the control selection, designation, and allocation are reviewed and approved. These plans document how the selected controls meet te security and privacy reuirements of the system, and they serve as key inputs for the authorization process. The review and approval  of thesse plans ensure that the selected controls are appropriate and the system is adequately protected against potential risks.

***Reference the following: Security & Privacy (SP 800-53  controls & SP 800-53B control Baselines)***


### Step 3: **IMPLEMENT**
		PURPOSE:
			This implementation of security controls is to put into action the security and privacy controls outlined in the system security plan and organizational policies and procedures. THis step involves the actual implementation of the safeguards and sountermeasures prescribed to protect the confidetiality, intgrity, and availability of the information system and its environment.

		OUTCOME:
			The desired outcome in this phase involves implementing the security and privacy controls specified in the security and privacy plans for the system and organization. This encompasses implementing the controls as outline in the plans, while also updating the plans to reflect the controls as they are actually implemented. Specifically, it involves implementing the safeguards and countermeansures precribed to protect the confidentiality, integrity, and availability of the system, as detailed in the secuirty and privacy plans. Concurrently, the plans are updated to capture any changes or deviations from the planned implementation, ensuring an accurate record of the “as-implemented” state of the controls.
	
***Reference the following: (SP 800 - 88, SP 800-34,  SP 800-61, SP 800-128)***

### Step 4: **ASSESS**
	PURPOSE:
        Determine if the security and privacy controls have been implemented correctly and are operating as intended. This verification process ensures that the implemented controls are producing the desired outcome in terms of meeting the security and privacy requirements for the system and the organization.

		During this phase, organizations assess whether the controls have been properly confiured and deplyed according to the specifications outlined iin the security and privacy plans. They also evaluate the effectivenss of the controls in mitigating the identified risks and protecting the confidentiality, integrity, and availability of the system and its data. This assessment may involve various testing and evaluation techniques, such as penetration testing, vulnerability scanning, and security audits, to validate the correct implementation and operation of the controls. 

		The ultimate goal of this verification process is to ensure that the implemented controls are aligned with the security and privacy requirements of the system and the organization. By thoroughly evaluating the control implemenation and operation, organizations can identify any gaps or deficiencies that need to be addressed before proceeding to the next phase. If the assessment reveals that certain controls are not implemented correctly or are not operating as inteded, organizations can take corrective action to remediated the issues. This may involve adjusting the control configurations, implementing additional compensating controls, or revising the security and privacy plans to address the identified deficiencies. Continuous monitoring and periodic reassessment of the controls are also essential to ensure that they remain effective and aligned with the evolving security and privacy reirements over time.

	OUTCOME:
		The desired outcome of this phase involves selecting an assessor or assessment team to evaluate the implemented security and privacy controls. Security and privacy assessment plans are developed, outlining the scope, methodology, and procedures for conducting the assessments. These assessment plans are reviewed and approved by stakeholders before actual controls assessments are conducted in accordance with the defined plans. During the assessments, the assessor or team examines the implemented controls to determine their effectiveness in meeting the security and privacy requirements. The finsings and results of the assessments are documented in security and privacy assessment reports, which identify any deficiencies or areas where the controls are not operating as intended. Based on these reports, remediation actions are taken to address the idetified deficiencies, such as reconfiguring controls, implementing additional safeguards, or revising policies and procedures. The security and privacy plans are then updated to reflect the changes made to the control implementation based on the assessments and remediation actions. Finally, a plan of action and milestones id developed outlining the steps and timelines for addressing any remaining deficiencies or vulnerabilities.

***Reference the following: ( NIST SP 800-53A & NISTIR 8011 Automation Support for Security Control Assessments: Multiple Volumees)***


### Step 5: **AUTHORIZE**
    PURPOSE:
	    The primary purpose of Authorize is to establish accountability for the security and privacy posture of the information system or the use of common controls. This requires a senior organization official, typically the Authorizing Official to review the assessment results and make a risk-based decision on whether to authorize the system or common controls for operation.

	    By requiring the Authorizing Official (AO) to explicity authorize the system or common controls, this ensures that there is clear ownership and responsib ility for accepting the associated risks. The AO’s decision is based on a comprehensive evaluation of the security and privacy controls, their effectiveness in mitigating risks, and the potential impact on the organization’s opertions and assets. The AO much determine if the security and privacy risk, based on the operation of the system or the use of common controls, is acceptable. This determination involves carefully weighing the idetified risks against the benefits and operational reuirements of the system or common controls.

	    The AO’s decision is informed by the security privacy assessment reports, whcih provide detailed information on the effectiveness of the implemented controls and any remaining deficiencies or vulnerbilities. The AO may also consider other factors, such as the organization’s risk tolerance, regulatory compliance requirements, and the potential consequences of a sexcurity or privacy breach. If the AO deems the risk acceptable, they will issue an authorization decision, allowing the system or common controls to operate within the defined parameters and constraints. However, if the risk is deemed unacceptable, the AO may dey authorization or impose specific conditions or restrictions on the system’s operation until the idetified deficiencies are addressed and the risk is reduced to an an acceptable level.

	OUTCOME:
	    The desired outcome in this phase is the authorization process begins with compilation of an authorization package, which serves as the basis for the Authorizing Official’s (AO) risk determination. This package typically includes an executive summary, the system security and privacy plany, assessment report(s), and a plan of action and milestones (POA&M) that outlines the steps to address any identified deficiencies or vulnerabilities.

        Upon reviewing the authorization package, the AO renders a risk determination, evaluating whether the security and privacy risks associated with the operation of the system or the use of common controls are acceptable. This risk determination is a critical decision that considers the potential impact on the organization’s operations, assets, and compliance with relecant regulations and policies. Based on the reisk determination, the AO provides risk responses, which may include speific conditions, limitations, or constraints on the system’s operation or the use of common controls. These risk responses are designed to mitigate or manage the idetified risked to an acceptable level.

        Ultimately, the AO make the final authorization decision, either approving or denying the authorization for the system or common controls to operate. If authorization is granted, the system or common controls can be placed into operation within the defined parameters and contrraints specified by the AO. However, if authorization is denied, the organization must take appropriate actions to address the identified deficiencies and reduce the risk to an acceptable level before resubmitting the authorization package for consideration. The authorization decision is a crucial step in the Risk Managemen Framework, as it ensures that the organization’s senior leadership is fully aware of and accountable for the security and privacy risks associated with the system or common controls. This accountability promotes a risk-based approach to information security and privacy, ensuring that appropriate measures are in place to protect the organization’s assets and operations.

### Step 6: **Monitor**
    PURPOSE:
		Monitor emphasizes the importance of maintaining ongoing situational awaremess  about the security and privacy posture of the system and organization. This continuous monitoring process is crucial for supporting informed risk management decisions and ensuring that the implemented security and privacy controls remain effective in mitigating risks.

	    Through continuous monitoring, organizations can proactively identify changes that may impact the risk posture, such as the emergence of new vulnerabilities, evolving threats, or modifications to organizational policies or operational requirements. By staying vigilant and moitoring the system and its enviornment, organizations can promptly detect and respond to potential issues, implement necessary control enhancements, or adjust risk mitigation strategies as needed. The situational awareness gained from continuous monitoring provides valuable insights and data to support guture risk assessments and authorization decisions. By regularyly evaluating the effectivencess of the implemented controls and the overall risk environment organizations can make informed decisions about whether to accept, mitigate, or transfer identified risks.

        Overall, monitor plays a crucial role in supporting risk managmenet decisions by providing organizations with a comprehensive understanding of their current security and privacy posture. This situational awareness empowers organizations to make informed choices and take proactive measures to protect their systems, data, and operations from potential threats and vulnerabilities.


	OUTCOME:
	    The desired outcome in this phase is monitor the system and its environment of operation are continuously monitored in accordance with the established continuous monitoring strategy. This strategy outlines the specific processess, procesdures, and tools used to monitor the system’s security and privacy posture on an ongoing basis.

    	As part of the continuous monitoring activities, on going assessments of contols effectivenness are conducted. These assessments evaluate whether the implemented security and privacy controls are operating as inteded  and providing the desired level of protection. The assessments may involve various techniques,such as culnerbility scanning, penegtration testing, security augits, and user activity monitoring, to identify potential weaknesses or deviations form the established security and privacy requirements.The outputs of the continuous monitoring activites are carefully analyzed, and appropriate responses are taken to address any identified isses or concerns. This analysis may reveal the need for control enhancements, policy updates, or additional risk mitigation measures to maintain an acceptable level of security and privacy.

    	The results of the continuous monitoring activites are also used to support ongoing authorizations of the system of common controls. Based on the monitoring data and analysis, the Authorizing Official can make risk-based decisions about whether to continue, modify, or revoke the authorization for the system or common controls to operate.The ongoing authorization process ensures that the organization maintains a comprehensive understanding of its risk posture and can adapt its risk management strategies as needed, by continuously monitoring and assessing the effectiveness of security and privacy controls, organizations can proactively identify and address potential vulnerbilities, ensureing that their systms and operation remain secure and compliant with relevant regulations and policies.

***Reference: NIST SP 800-137, NIST SP 800-137A, NISTIR 8212, NISTIR 8011, NIST SP 800-53A***

![Risk Management Framework](/RMF_image.jpg "Risk Management Framework")
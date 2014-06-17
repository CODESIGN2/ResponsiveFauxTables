ResponsiveFauxTables
====================

Responsive Faux-Data-Tables Used within the CODESIGN2 CRM System 

Excerpt From CODESIGN2 CRM Medico-Legal System Reporting Screen
<div class="row-fluid">
		<div class="span12 faux-table">
			<dl class="header">
        <dt>&nbsp;</dt><dd>&nbsp;</dd>
        <dt>Solc to Send</dt><dd>&nbsp;</dd>
        <dt>Received</dt><dd>&nbsp;</dd>
        <dt>Sent to expert</dt><dd>&nbsp;</dd>
        <dt>To be sent back to Solc</dt><dd>&nbsp;</dd>
			</dl>
			<!-- definition lists as table rows. it's turtles all the way down. !-->
			<dl>
        <dt><h4>Hospital Records</h4></dt><dd><strong class="visible-1040">Hospital Records</strong></dd>
        <dt>Solc to Send</dt><dd><input type="text" class="date" value="<?php echo isset($solicitor_to_send_hospital_records_display) ? $solicitor_to_send_hospital_records_display : ''; ?>" name="solicitor_to_send_hospital_records_display" id="solicitor_to_send_hospital_records_display" placeholder="Date (DD-MM-YYYY)"/>
								 <input type="hidden" name="solicitor_to_send_hospital_records" id="solicitor_to_send_hospital_records" data-prettyname="Solicitor To Send Hospital Records"/></dd>
        <dt>Received</dt><dd><input type="text" class="date" name="received_hospital_records_display" id="received_hospital_records_display" placeholder="Date (DD-MM-YYYY)"/>
						     <input type="hidden" name="received_hospital_records" id="received_hospital_records" data-prettyname="Received Hospital Records"/></dd>
        <dt>Sent to expert</dt><dd><input type="text" class="date" name="hospital_records_sent_to_expert_display" id="hospital_records_sent_to_expert_display" placeholder="Date (DD-MM-YYYY)"/>
								   <input type="hidden" name="hospital_records_sent_to_expert" id="hospital_records_sent_to_expert" data-prettyname="Hospital Records Sent to Expert"/></dd>
        <dt>To be sent back to Solc</dt><dd><input type="text" class="date" name="hospital_records_to_be_sent_back_to_solicitor_display" id="hospital_records_to_be_sent_back_to_solicitor_display" placeholder="Date (DD-MM-YYYY)"/>
											<input type="hidden" name="hospital_records_to_be_sent_back_to_solicitor" id="hospital_records_to_be_sent_back_to_solicitor" data-prettyname="Hospital Records to be sent back to Solicitor Display"/></dd>
			</dl>
			<dl>
        <dt><h4>GP Records</h4></dt><dd><strong class="visible-1040">GP Records</strong></dd>
        <dt>Solc to Send</dt><dd><input type="text" class="date" name="solicitor_to_send_gp_records_display" id="solicitor_to_send_gp_records_display" placeholder="Date (DD-MM-YYYY)"/>
							     <input type="hidden" name="solicitor_to_send_gp_records" id="solicitor_to_send_gp_records" data-prettyname="Solicitor to Send GP Records"/></dd>
        <dt>Received</dt><dd><input type="text" class="date" name="received_gp_records_display" id="received_gp_records_display" placeholder="Date (DD-MM-YYYY)"/>
							 <input type="hidden" name="received_gp_records" id="received_gp_records" data-prettyname="Received GP Records"/></dd>
        <dt>Sent to expert</dt><dd><input type="text" class="date" name="gp_records_sent_to_expert_display" id="gp_records_sent_to_expert_display" placeholder="Date (DD-MM-YYYY)"/>
								   <input type="hidden" name="gp_records_sent_to_expert" id="gp_records_sent_to_expert" data-prettyname="GP Records sent to Expert Display"/></dd>
        <dt>To be sent back to Solc</dt><dd><input type="text" class="date" name="gp_records_to_be_sent_back_to_solicitor_display" id="gp_records_to_be_sent_back_to_solicitor_display" placeholder="Date (DD-MM-YYYY)"/>
											<input type="hidden" name="gp_records_to_be_sent_back_to_solicitor" id="gp_records_to_be_sent_back_to_solicitor" data-prettyname="GP Records to be sent back to Solicitor"/></dd>
			</dl>
		</div>
	</div>

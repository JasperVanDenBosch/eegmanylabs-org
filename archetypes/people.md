+++
SequenceNumber = "{{ SequenceNumber }}"
Anchor = "{{ PersonId }}"
Title = "{{ FullName }}"
Image = "headshots/{{ HeadShotFilename }}"
Tags = [
{%- if CoordinatorRole %} "coordinator", {% endif -%}
{%- if AdvisorRole %} "advisor", {% endif -%}
{%- if CoInvestigatorRole %} "co-investigator", {% endif -%}
{%- if ReplicatorRole %} "replicator", {% endif -%} 
]
ScholarUrl = "{{ ScholarUrl }}"
UniUrl = "{{ UniUrl }}"
LabUrl = "{{ LabUrl }}"
StudyId = "{{ StudyId }}"
PersonId = "{{ PersonId }}"
FullName = "{{ FullName }}"
+++
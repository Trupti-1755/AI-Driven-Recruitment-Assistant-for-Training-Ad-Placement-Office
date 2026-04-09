# TODO: Add Filters to Candidate List

## Steps to Complete

- [ ] Add input fields in candidate_list.html for Minimum SSC Marks, Minimum HSC Marks, and Required Skills.
- [ ] Update the JavaScript in candidate_list.html to send min_ssc, min_hsc, required_skills in the fetch request to /api/job_matching.
- [ ] Modify the /api/job_matching endpoint in main.py to accept min_ssc, min_hsc, required_skills as Form parameters.
- [ ] Update the backend logic in job_matching to apply filters for SSC marks >= min_ssc, HSC marks >= min_hsc, and check if any required skills match student's skills.
- [ ] Test the functionality to ensure filters work correctly, allowing empty fields to skip filtering.

before compiling your work,

1) install THSarabunNew font in your machine (just double click at the font files -- all of them)
2) install Mixtex or TeXLive. learn how to compile latex yourself.
3) use 'EE490_proposal_template_latex.tex' or 'EE499_report_template_latex.tex' as your template. edit your report here. if you write the report in English, use 'EE490_proposal_template_latex_eng.tex' or 'EE499_report_template_latex_eng.tex' instead, but you read all the details of each section from the thai template.
4) folder 'figures' are for storing your pictures and has to be in the same local directory as your .tex file. the format pictures are .eps, .pdf, .jpg, .png (pdf is most preferable)
5) use 

>> xelatex EE490_proposal_template_latex.tex 
>> bibtex EE490_proposal_template_latex.aux

or

>> xelatex EE490_proposal_template_latex_eng.tex 
>> bibtex EE490_proposal_template_latex_eng.aux

or

>> xelatex EE499_report_template_latex.tex 
>> bibtex EE499_report_template_latex.aux

or

>> xelatex EE499_report_template_latex_eng.tex 
>> bibtex EE499_report_template_latex_eng.aux

to compile your work.



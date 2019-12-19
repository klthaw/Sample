Create Custom formula field on Opportunity.
HYPERLINK("/apex/PrintPDF?id=" + Id,"Print","_blank")

Add field to Page layout.

Add field to Compact Layout to use Hyperlink field instead of action button.

Add field to Column of any List View you want to work.

Now you can Print PDF from Record Page Detail and List View.

Note:
-To use _blank please Activate "Lightning Experience Honors Target Values for Hyperlinks in Formula Fields" in Critical Updates.
-You have to design PDF in VF Page and query more fields in Controller.

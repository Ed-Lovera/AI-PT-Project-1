

 Where area is crime higher for individuals under 30? \
	filter to age <31 and sort by location \
\
What crimes are individuals under 30 more exposed to? \
	filter to ages under 31 and sort by crime code; include the crime descriptions. \
\
Where should individuals under 30 avoid to reduce their chances of lethal crimes? \
	Filter to crimes under age 31 and sort by the location \


# Read csv file 
# can you read and extract the data from the URC.PDF 
	# Yes, I peformed from pypdf import PdfReader
	# Then, UCR_PDF_File = PdfReader(Path('../Philip/UCR-COMPSTAT062618.pdf'))
UCR_PDF_File
	# getting a specific page from the pdf file
UCR_page1 = UCR_PDF_File.pages[0]

# extracting text from page
UCR_text = UCR_page1.extract_text()
print(UCR_text)

I need to rquest from the df where is crime the highest by geo based on the count of crime code. 

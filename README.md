# Pre and Post-Match Sports Data Mining Project

**Project Description:**
This project focuses on extracting data from the sports betting platform Wplay, both before and after the matches are played. The primary goal is to gather essential data for making informed bets and building future prediction models.

**Project Objectives:**
This project begins as an experiment with the aim of developing a high-quality database to drive future sports betting predictions and models.

**Key Features:**
- Extraction of pre-match and post-match data.
- Generation of two types of Excel files: one with pre-match data and another with post-match data.
- Customization of the leagues to analyze and Excel files to generate.
- Easy execution in environments like Jupyter Notebook or Google Colab with internet access.

**Installation Requirements:**
You only need a development environment compatible with Python 3.10.6, such as Jupyter Notebook or Google Colab, along with internet access.

**Usage Guide:**
1. Run the first four cells.
2. Then, execute a cell containing two lists: one with the URLs of the leagues you want to analyze and another with the names of the Excel files you want to create.
3. Next, run a cell for pre-match using the `Excel_pre_partido` class, providing the list of URLs as a parameter.
4. Finally, execute a cell for post-match using the `Excel_pos_partido` class, providing the list of URLs and the Excel file as parameters.

**Usage Examples:**
- For pre-match: `PRE_PARTIDO = Excel_pre_partido(urls=URLs)`
- For post-match: `POS_PARTIDO = Excel_pos_partido(urls=URLs, excel=excel)`

**Contributions:**
The project has been entirely developed by the creator, and external contributions are not currently accepted.

**License:**
This project currently does not have a specific license.

**Contact:**
For any questions or inquiries, you can contact the creator via email at: the12sayan@gmail.com

**Project Status:**
The project is in a beta phase and is continually updated for improvement.

**Technical Prerequisites:**
Very basic knowledge of Python and an installation of Python 3.10.6 are required to use this project.

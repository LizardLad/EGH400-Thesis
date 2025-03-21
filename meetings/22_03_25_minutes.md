Meeting Minutes: 21/3/25

# Progress update:
- Discussed current progress on project proposal
- Discussed experimental data analysis looking for distributions of important factors in the source data
- Discussed progress with DCGAN


# Advice:
## Project proposal:
    - It can be sparse while covering all the required information
    - Include progress upon submission of the project proposal
    - Do the literature key finding after finishing the literature review and finding the research gap
    - Stakeholders will be limited (student, supervisors, university)
    - Deliverables include code, code documentation, model weights, reports, drawings, designs, reviews, reports, and presentations
    - Risks are limited... (physical injury to self is limited, packages breaking compatibility)
    - Don't really need to discuss ethical consideration
    - The quality of the project can be measured by the accuracy, iou, and loss metrics
    - Sustainability will include the energy usage for the project, along with how maintainable the software is 
    - Timeline of deliverables needs to be discussed
    - Management of project changes (agile methodology can be used along with some documentation of the change management process, tools, communication, and risk management )
    
## Technical implementation:
    - Suggested to try another colour space for the GAN (HSV or others) as it can perform better than RGB
    - Suggested to use the GAN to create synthetic training data and then use another model for classification, segmentation, ...

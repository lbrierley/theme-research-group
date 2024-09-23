---
title: Research
summary: Research projects of the VIBE Lab at the CVR, University of Glasgow
type: landing

sections:

  - block: markdown
    content:
      title: Research
      subtitle: '<br>Emerging infectious diseases still pose serious threats to global health, exemplified by the COVID-19 pandemic (SARS-CoV-2) as well as Zaire ebolavirus, Zika virus, and numerous others over the last twenty years. Our research mission is to use new data, methods, and computational technologies to better understand how RNA viruses ''host shift'' (i.e., infect and cause disease within a new host species) with a view to anticipating future pandemic risks. 
	  

	  We use a broad range of methodologies (e.g., biostatistics, artificial intelligence, natural language processing) and model a broad diversity of animal RNA viruses, though our research is driven by consistent key questions around dynamics of viruses in their...'
    design:
      spacing:
        padding: ['20px', '0', '20px', '0']	  
  - block: collection
    content:
      title: ...ecological contexts
      subtitle:
      text: <span></span>![Image](ecology_fig.png)<span style="font-size:1em;">If we are to anticipate future human disease outbreaks, we need to better understand dynamics in wild hosts and the environments in which we interact with them. We are interested in modelling diversity of animal hosts and changes to landscapes influence cross-species transmission and emergence in humans, including global distributions of bat-borne viruses and the ecological shifts associated with the 2021 outbreak of highly pathogenic avian influenza.</span><br><br><span style="font-size:0.95em;">**Collaborators:** *Dr Sarah Hayes, Prof. Christl Donnelly (University of Oxford); Prof. Matthew Baylis (University of Liverpool)*</span><br><br>
      count: 3
      filters:
        author: ''
        category: 'Ecology'
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      spacing:
        padding: ['30px', '0', '30px', '0']
      view: list
      columns: '2'  
      image:
        filename: ecology_fig.png

  - block: collection
    content:
      title: ...evolutionary dynamics
      subtitle:
      text: <span></span>![Image](evo_fig.png)<span style="font-size:1em;">Evolutionary adaptation is the driving force underyling host range of a virus. A core theme of our research is understanding how ability to infect specific hosts and tissues can be characterised directly from genome sequences by training artificial intelligence approaches on genomic and proteomic traits (''genotype-to-phenotype'') - and how these traits evolve over time.  We are also interested in whether evolutionary models can highlight viruses likely to be transmissible or virulent in human populations. Being at the intersection of evolution and computer science, our work often necessitates development of new computational methods for viral sequence data.</span><br><br><span style="font-size:0.95em;">**Collaborators:** *Dr Jan Gogarten, Dr Sebastien Calvignac-Spencer (Helmholtz Institute for One Health); Dr Lu Lu (Roslin Institute, University of Edinburgh)*</span><br><br>
      count: 3
      filters:
        author: ''
        category: 'Evolution'
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      spacing:
        padding: ['30px', '0', '30px', '0']
      view: list
      columns: '2'	    

  - block: collection
    content:
      title: ...public health impact
      subtitle:
      text: <span></span>![Image](pubhealth_fig.png)<span style="font-size:1em;">Although human populations are continuously exposed to novel viruses, few emerge successfully to cause significant outbreaks. Through collaborations, we are exploring how genomic and machine learning methodologies can improve predicted impact of emerging viruses on public health. This inclues modelling chance of discovering new viruses, dynamics of transmissibility within populations, and outbreak characteristics.</span><br><br><span style="font-size:0.95em;">**Collaborators:** *Dr Dan Hungerford, Prof. Iain Buchan (University of Liverpool); Dr Jasmina Panovska-Griffiths (University of Oxford)*</span><br><br>
      count: 3
      filters:
        author: ''
        category: 'Public Health'
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      spacing:
        padding: ['30px', '0', '30px', '0']
      view: list
      columns: '2'	  

  - block: collection
    content:
      title: ...systematic data gaps
      subtitle: and modern solutions
      text: <span></span>![Image](data_fig.png)<span style="font-size:1em;">Our collective scientific knowledge of how viruses interact with their hosts is vast, although systematic data gaps exist. Our group is dedicated to understanding these gaps through statistical analysis and resolving them with modern computational tools. A primary focus of our current research is text mining to unlock the huge volume of information on host-parasite relationships in scientific literature. We are exploring natural language processing and large language model methods to generate usable data resources describing viral interactions with hosts, tissues, proteins, and more.</span><br><br><span style="font-size:0.95em;">**Collaborators:** *Dr Maxwell Farrell (University of Glasgow); Dr Rory Gibb (UCL)*</span><br><br>
      count: 3
      filters:
        author: ''
        category: 'Data'
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      spacing:
        padding: ['30px', '0', '30px', '0']
      view: list
      columns: '2'	    	  

  - block: markdown
    content:
      title: 'Some of our active research partnerships:'

  - block: slider
    headless: true
    content:
      slides:
      - title: 
        background:
          image:
            size: contain
            filename: partners/sbovhm.jpg
          position: center
          color: '#E3EBDF'
      - title: 
        background:
          image:
            size: contain
            filename: partners/uol_tpi.jpg
          position: center
          color: '#E3EBDF'          
      - title: 
        background:
          image:
            size: contain
            filename: partners/hioh.jpg
          position: center
          color: '#E3EBDF'  
      - title: 
        background:
          image:
            size: contain
            filename: partners/ukhsa.jpg
          position: center
          color: '#E3EBDF'            
      - title: 
        background:
          image:
            size: contain
            filename: partners/uoo.png
          position: center
          color: '#E3EBDF' 
      - title: 
        background:
          image:
            size: contain
            filename: partners/roslin.jpg
          position: center
          color: '#E3EBDF'    
    design:
      slide_height: '300px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5500
---
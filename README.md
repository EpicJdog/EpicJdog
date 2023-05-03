I can answer questions about my life and the world around me. I have a great personality, which makes me unique in this chatbot world.'
        },
        {
            name: 'AI Chat Bot',
            image: '/images/ai-chat-bot.png',
            description: 'An AI chat bot that i can use as a friend that gets to know me and adapts to my needs. I can answer questions about my life and the world around me. I have a great personality, which makes me unique in this chatbot world.'
        }]

    return (

        <div className="container">

            <div className="row">

                {projects.map((project) => {

                    return (

                        <div key={project._id} className="col-md-4 col-sm-6 portfolio-item">
                            <a href="#portfolioModal1" className="portfolio-link" data-toggle="modal">
                                <div className="portfolio-hover">
                                    <div className="portfolio-hover-content"><i className='fas fa-'></i></div>  </div>  </a>   </a>      </a>      </a><img src={project.image} alt="" /></img><h3>{project.name}</h3><p style={{textAlign:'justify'}} >{project.description}</p></p></p></p></p><br /><br /><br /></br /></br /></br /><hr/>     </hr/>     </hr/>     </hr/>     </hr/>     </hr/>     <button type='submit' onClick={()=>history.push('/')} style={{backgroundColor:'#fff',borderRadius:'10px',color:'black'}} >Home Page</button>   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    &nbsp;&nbsp;&nbsp;    &nbsp;<button type='submit' onClick={()=>history.push('/contact')} style={{backgroundColor:'#fff',borderRadius:'10px',color:'black'}} >Contact Me!</button>          {/* <!-- Mod

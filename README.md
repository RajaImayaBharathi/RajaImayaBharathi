<div className="mt-20 AboutSectionStyling flex items-center justify-center" id="about">
        <div className="About-Container1">
          <div className="text-white font-HomeSection flex items-center">
            <div>
              <header className="AboutHeader flex items-center" ref={SplitText}>
                <p className="text-xl"><span>02</span>.About Me</p>
                <div className="HeaderLiner ml-4"></div>
              </header>
              <div className="socialIconsInMobile pb-3 pt-2 pl-9 lg:hidden flex-row text-white font-Navbar" ref={FadeIn}>
                <a
                  href="https://www.linkedin.com/in/raja-imaya-bharathi"
                  target="_blank"
                  rel="noopener noreferrer"
                >
                  LinkedIn&ensp;.&ensp;
                </a>
                <a
                  href="https://github.com/RajaImayaBharathi"
                  target="_blank"
                  rel="noopener noreferrer"
                >
                  GitHub&ensp;.&ensp;
                </a>
                <a href="https://leetcode.com/u/rajaimayabharathi/" target="_blank" rel="noopener noreferrer">
                  LeetCode&ensp;&ensp;
                </a>
              </div>
            </div>
          </div>
          <div className="AboutPara1 text-white mt-5 lg:pl-10" ref={addToRightSlide}>
            Hello, {`I'm`} Raja Imaya Bharathi, a{" "}
            <span>full stack developer</span> with a knack for building robust
            backends and pixel-perfect, sleek frontends. I always love to find
            and deliver the best solutions and tackle unresolved problems.
            Currently, <span> I lead Metaphor Hub</span>, where we contribute to{" "}
            <span>open-source projects</span> and create innovative solutions
            for <span>societal challenges</span>.
          </div>
          <div className="AboutPara2 text-white mt-8 lg:pl-10" ref={addToRightSlide}>
            {`I've`} led my team to <span> national finals</span> and developed
            over 10 progressive web apps and <span> 60+ projects </span>to help
            businesses streamline management, boost efficiency, and automate
            processes showcasing our dedication and expertise Over{" "}
            <span> 2 years</span>.
          </div>
          <div className="AboutPara3 text-white mt-10 lg:pl-10" ref={addToRightSlide}>
            {`Here Are the list of technologies im familier with`}
            <div className="TechStackAbout flex my-4">
              <div className="pl-2 space-y-1">
                <div className="flex items-center ">
                  <IoMdArrowDropright className="mr-1" />
                  Java
                </div>
                <div className="flex items-center">
                  <IoMdArrowDropright className="mr-1" />C
                </div>
                <div className="flex items-center">
                  <IoMdArrowDropright className="mr-1" />
                  Python
                </div>
                <div className="flex items-center">
                  <IoMdArrowDropright className="mr-1" />
                  C++
                </div>
              </div>
              <div className="pl-20 space-y-1">
                <div className="flex items-center">
                  <IoMdArrowDropright className="mr-1" />
                  Java Script
                </div>
                <div className="flex items-center">
                  <IoMdArrowDropright className="mr-1" />
                  React
                </div>
                <div className="flex items-center">
                  <IoMdArrowDropright className="mr-1" />
                  NodeJS
                </div>
                <div className="flex items-center">
                  <IoMdArrowDropright className="mr-1" />
                  NextJS
                </div>
              </div>
            </div>
            <button className="AboutBtn mt-5" ref={addToRightSlide}>View full Resume</button>
          </div>
        </div>
        <div className="AboutImg ml-20" style={{ overflow: "hidden" }}>
          <img src="HomeImg.png" className="HomeImg" alt="" ref={addToLeftSlide}/>
        </div>
      </div>

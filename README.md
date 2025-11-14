<div align="center" style="font-family: 'Monaco', 'Menlo', 'Ubuntu Mono', monospace;">

<h1 style="color: #ff79c6; font-size: 3em; margin-bottom: 10px; text-shadow: 0 0 10px rgba(255, 121, 198, 0.3);">✦ LILY PARKER ✦</h1>
<p style="color: #6272a4; font-style: italic; font-size: 1.2em;">midwest trans-fem chronically online internet cat-girl who likes to make things sometimes</p>

</div>

<hr style="border: 1px solid #bd93f9; margin: 40px 0;">

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 30px; margin-bottom: 40px;">

<div style="background: rgba(40, 42, 54, 0.8); border: 2px solid #bd93f9; border-radius: 10px; padding: 20px; position: relative;">
  <h3 style="color: #8be9fd; margin-bottom: 15px; border-bottom: 1px solid #6272a4; padding-bottom: 5px;">ABOUT ME</h3>
  
```crystal
require "person"

struct LilyParker < Person
  property name = "LILY PARKER"
  property aliases = ["Lilith", "LP", "Sap", "Oka", "aVa"]
  property status = "bipolar college reject"
  property quote = "computers should not speak unless spoken to"
  property bio = "midwest trans-fem chronically online internet cat-girl who likes to make things sometimes"
  property occupation = [
    "Retro Laptop Technician at Local E-Waste Company",
    "Systems Engineer at Strubworks"
  ]
  
  def initialize
    @pronouns = ["she/her"]
    @interests = ["retro computing", "systems programming", "feline activities"]
  end
end

lily = LilyParker.new
puts "Profile loaded successfully!"
```

</div>

<div style="background: rgba(40, 42, 54, 0.8); border: 2px solid #bd93f9; border-radius: 10px; padding: 20px; position: relative;">
  <h3 style="color: #8be9fd; margin-bottom: 15px; border-bottom: 1px solid #6272a4; padding-bottom: 5px;">ACTIVE PROJECTS</h3>

```crystal
# Current Development
ACTIVE_PROJECTS = {
  "Vex" => {
    description: "Beta 1.7.3 Minecraft Clone with Unique Features",
    note: "i like minecraft beta 1.7.3, especially a lot of the mods for it",
    status: "🟢 Active"
  },
  "Litin" => {
    description: "OpenRC-Runit-like init system with QoL features", 
    note: "this ones honestly just a hobby project atm. probably won't become anything ;3",
    status: "🟡 Hobby"
  },
  "CRSH / Crush" => {
    description: "POSIX Compliant Shell for Unix-like Operating Systems",
    note: "i always wanted to write my own shell",
    status: "🟢 Active",
    language: "Crystal"
  }
}

puts "Active projects: #{ACTIVE_PROJECTS.size}"
puts "Crystal projects: #{ACTIVE_PROJECTS.count { |k,v| v[:language]? == \"Crystal\" }}"
```

</div>

</div>

<div style="text-align: center; color: #6272a4; font-style: italic; padding: 20px; border-left: 3px solid #ff79c6; margin: 20px 0; background: rgba(255, 121, 198, 0.1);">
"god... why do i take on so many projects?"
</div>

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 30px; margin-bottom: 40px;">

<div style="background: rgba(40, 42, 54, 0.8); border: 2px solid #bd93f9; border-radius: 10px; padding: 20px; position: relative;">
  <h3 style="color: #8be9fd; margin-bottom: 15px; border-bottom: 1px solid #6272a4; padding-bottom: 5px;">ON HIATUS</h3>

```crystal
class HiatusProjects
  property catacomb = {
    description: "Locally hosted secure password manager",
    note: "because i'm sick of paying these hoes for basic features"
  }
  
  property blueberry = {
    description: "Experimental, prototype for an ethical imageboard-like microblogging platform",
    note: "i like imageboards and microblogging but i hate the corporations and people that run them" 
  }
  
  property bottletype = {
    description: "Markdown Based Locally Hosted Doc Writer",
    note: "Locally Hosted Alternative to Google Docs"
  }
  
  def reason
    "i should probably finish these at some point"
  end
end

hiatus = HiatusProjects.new
puts "Projects on hold: 3"
```

</div>

<div style="background: rgba(40, 42, 54, 0.8); border: 2px solid #bd93f9; border-radius: 10px; padding: 20px; position: relative;">
  <h3 style="color: #8be9fd; margin-bottom: 15px; border-bottom: 1px solid #6272a4; padding-bottom: 5px;">TECH STACK</h3>

```crystal
# Languages & Frameworks
LANGUAGES = [
  "Bash + POSIX Shell",
  "Crystal", 
  "Go",
  "JavaScript + TypeScript",
  "Perl",
  "Ruby", 
  "Rust"
]

FRAMEWORKS = {
  web: ["Echo", "Vue.js", "Nuxt"],
  db: ["GORM", "Marten"], 
  crypto: ["Sodium.cr"]
}

LEARNING = ["Kemalcr", "Kotlin"]

puts "Languages known: #{LANGUAGES.size}"
puts "Currently learning: #{LEARNING.join(", ")}"
```

</div>

</div>

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 30px; margin-bottom: 40px;">

<div style="background: rgba(40, 42, 54, 0.8); border: 2px solid #bd93f9; border-radius: 10px; padding: 20px; position: relative;">
  <h3 style="color: #8be9fd; margin-bottom: 15px; border-bottom: 1px solid #6272a4; padding-bottom: 5px;">CRYSTAL TOOLS</h3>

```crystal
# Crystal Language Projects
CRYSTAL_TOOLS = {
  "LSD" => {
    description: "`ls` clone with QoL features",
    note: "made with peace and love <3",
    status: "🟢 Active"
  },
  "Rat" => {
    description: "a simple file pager for your everyday needs", 
    note: "made with love, and rats",
    status: "🟢 Active"
  }
}

puts "Crystal tools in development: #{CRYSTAL_TOOLS.size}"
puts "i really like crystal, can you tell?"
```

</div>

<div style="background: rgba(40, 42, 54, 0.8); border: 2px solid #bd93f9; border-radius: 10px; padding: 20px; position: relative;">
  <h3 style="color: #8be9fd; margin-bottom: 15px; border-bottom: 1px solid #6272a4; padding-bottom: 5px;">PROJECT STATS</h3>

```crystal
module ProjectMetrics
  def self.summary
    {
      total_projects: 9,
      active: 6,
      hiatus: 3,
      crystal_projects: 4,
      completed: 0
    }
  end
  
  def self.report
    stats = summary
    <<-REPORT
    Projects Summary:
    - Total: #{stats[:total_projects]}
    - Active: #{stats[:active]}
    - On Hiatus: #{stats[:hiatus]} 
    - Crystal Projects: #{stats[:crystal_projects]}
    - Completed: #{stats[:completed]}
    
    "i have a problem..."
    REPORT
  end
end

puts ProjectMetrics.report
```

</div>

</div>

<hr style="border: 1px solid #bd93f9; margin: 40px 0;">

<div align="center">
  <h2 style="color: #8be9fd; margin-bottom: 20px;">STATISTICS</h2>
  
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 20px 0;">
    <a href="https://github.com/okavatti/okavatti">
      <img width=600em src="https://github-readme-stats.vercel.app/api?username=okavatti&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage&layout=compact&theme=vue-dark&hide_border=true&bg_color=0D1117" />
    </a>
    <a href="https://github.com/okavatti/okavatti">
      <img width=600em src="https://github-readme-stats.vercel.app/api/top-langs?username=okavatti&layout=compact&theme=vue-dark&hide_border=true&bg_color=0D1117&langs_count=8" />
    </a>
  </div>
</div>

<hr style="border: 1px solid #bd93f9; margin: 40px 0;">

<h2 align="center" style="color: #8be9fd; margin-bottom: 20px;">Contact Info</h2>

<div align="center" style="padding: 40px 0;">
  <h3 style="color: #ff5555; font-size: 1.5em; margin: 20px 0;">*** don't. ***</h3>
  
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" alt="divider" style="width: 100%; max-width: 600px; margin: 20px 0;">
  
  <p style="color: #6272a4; font-style: italic;">"computers should not speak unless spoken to"</p>
  
  <br>
</div>

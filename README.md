/** 
 * TECHNICAL EXPERTISE
 * -------------------
 * Senior developer specialized in enterprise system architecture,
 * business process automation, and scalable web applications.
 */

interface Developer {
  core: string[];
  backend: {[key: string]: string[]};
  frontend: string[];
  database: {[key: string]: string[]};
  infrastructure: string[];
}

const skills: Developer = {
  core: ["Python", "JavaScript", "TypeScript", "OOP", "Design Patterns", "Data Structures", "Algorithms"],
  backend: {
    "ERP": ["Odoo Framework", "ORM", "XML-RPC", "OAuth", "API Development", "Business Process Automation"],
    "Web": ["Node.js", "Express", "GraphQL", "REST API", "Microservices"]
  },
  frontend: ["React", "Next.js", "OWL", "QWeb", "HTML5/CSS3", "TailwindCSS"],
  database: {
    "SQL": ["PostgreSQL", "Query Optimization", "Database Design", "Performance Tuning"],
    "NoSQL": ["MongoDB", "Document Modeling"]
  },
  infrastructure: ["Docker", "AWS", "CI/CD", "Git", "Linux"]
};

/**
 * PROFESSIONAL IMPACT
 * ------------------
 */

const achievements = {
  odooModules: "100+ custom modules developed for enterprise clients",
  integrationPlatforms: "20+ third-party systems connected via custom API architecture",
  databaseMigrations: "10+ large-scale migrations (15GB+) with zero downtime",
  performanceOptimization: "25% average query performance improvement across projects",
  recognitions: ["Cybrosys Hackathon Winner 2024", "HackerRank Certified Software Engineer"]
};

/**
 * FEATURED WORK
 * ------------
 */

interface Project {
  name: string;
  description: string;
  impact: string;
  stack: string[];
}

const showcase: Project[] = [
  {
    name: "Enterprise Integration Engine",
    description: "Unified API gateway connecting Odoo ERP with e-commerce, CRM, and payment platforms",
    impact: "Reduced integration development time by 60%, enabled real-time data synchronization",
    stack: ["Python", "PostgreSQL", "XML-RPC", "OAuth", "REST API"]
  },
  {
    name: "Intelligent Migration Framework",
    description: "Automated data migration tool with validation and transformation capabilities",
    impact: "Cut migration time by 40%, eliminated data loss risks during ERP version upgrades",
    stack: ["Python", "PostgreSQL", "Docker", "AWS"]
  },
  {
    name: "Next.js Commerce Platform",
    description: "Hackathon-winning modern e-commerce application with headless architecture",
    impact: "Demonstrated versatility beyond ERP development in modern web technologies",
    stack: ["Next.js", "React", "Node.js", "MongoDB", "TailwindCSS"]
  }
];

/**
 * CONNECT
 * ------
 */

const contact = {
  email: "yassirirfan7@gmail.com",
  linkedin: "linkedin.com/in/yassir-irfan",
  location: "Kozhikode, Kerala, India"
};

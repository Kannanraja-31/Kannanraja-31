## Hi there I'm Kannan👋
resource "personal" "info" {

  name        = "Kannan R"
  experience  = "3+ years"
  nationality = "Indian"
  languages   = ["English", "Tamil"]
  occupation  = "DevOps Engineer"
  hobbies     = ["Movies", "Playing cricket", "Hanging out with friends"]

}

resource "professional" "info" {
  
  # Core Skill Set
  devops_tools                 = ["Git", "Jenkins", "Maven", "Jfrog", "Nginx", "Azure devops"]
  cloud_providers              = ["AWS", "Azure"]
  infrastructure_as_code       = ["Terraform"]
  microservices_and_containers = ["Docker", "Kubernetes", "Helm"]

  # On-Prem & Virtualization
  on_prem_infrastructure       = ["Linux (RHEL/Ubuntu)", "Bare Metal Servers"]
  virtualization_platforms    = ["Proxmox VE", "VMware"]
  hybrid_connectivity          = ["VPN", "Private Networking", "Network Tunneling"]

  # Advanced Capabilities
  scripting_languages      = ["Shell Script", "Python Script", "YAML"]
  monitoring_tools         = ["Grafana", "Prometheus", "ELK/EFK", "checkmk"]
  security_and_devsecops   = ["ClamAV", "SonarQube", "Tenable"]
  mlops_frameworks         = ["DVC", "Azure ML Workspace"]
  database_migration       = ["MYSQL", "ORACLE", "POSTGRESQL", "AWS RDS", "Azure MySQL Flexible Server"]
  configuration_management = ["Ansible"]

  # Certifications
  cloud_certifications = ["Azure Fundamentals (AZ-900)"]
  iac_certifications   = ["HashiCorp Terraform Associate (003)"]

}

provider "social" {

  linkedin       = "www.linkedin.com/in/kannan-raja-devops"
  github         = "Kannanraja-31"
  contact_number = "+91 6374492674"
  email          = "kannan.raja@outlook.in"
}

resource "fun_facts" "personal_life" {
  
  - "Passionate about continuous learning and exploring new DevOps tools."
  - "Known for creative problem-solving and innovative automation solutions."
  - "Enjoys collaborating with cross-functional teams and mentoring new DevOps enthusiasts."
    
}

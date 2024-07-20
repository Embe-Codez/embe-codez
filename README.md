![image](https://github.com/user-attachments/assets/0e1110a5-c886-4e82-8c09-2ee497f8a422)

# Hi there, I'm Marcos! 👋

I enjoy switching between sysadmin and dev.

```C#
using System.Collections.Generic;

class Bio
{
    public string Role { get; set; }
    public List<string> Technologies { get; set; }
    public List<string> Programming { get; set; }
    public List<string> Frameworks { get; set; }
    public string OS { get; set; }
    public string Database { get; set; }
    public string Cloud { get; set; }
    public List<string> Automation { get; set; }

    public Bio()
    {
        Role = "DevOps Engineer";
        Technologies = new List<string> { "Containers", "Kubernetes", "Serverless" };
        Programming = new List<string> { "C#", "Golang" };
        Frameworks = new List<string> { "ASP.NET Core" };
        OS = "Linux (Fedora ftw!)";
        Database = "Postgres";
        Cloud = "Azure";
        Automation = new List<string> { "Ansible", "Packer", "Terraform" };
    }
}

class Program
{
    static void Main()
    {
        var bio = new Bio();
    }
}

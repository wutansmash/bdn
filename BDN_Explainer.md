# Why Benefit Dependency Network (BDN)
**Why care???**
<br>
- IT has no inherent value. 
- Just having technology does not confer any benefits or create value. Unlike many other assets, such as precious gems or real estate, the value of technology is not in its possession. 
- In fact, all the spend serves to do is incur cost – benefits result from the effective organizational use of the IT asset acquired or created. Benefits arise when IT enables people do things differently. 
- It is only when individuals or groups within the organization, or amongst it customer and supplier bases, perform their roles in more efficient or effective ways that benefits emerge.
- This usually demands improving how information is used. Technology can enable and shape new ways of working through the redesign of intra- and interorganizational processes or facilitating new work practices. 

**BDN provides a framework for providing the lineage to link the What, HOw, and Why we do things in a conceise way.  **

<br>
[Link to Paper (Ward 2007)](https://www.som.cranfield.ac.uk/som/dinamic-content/research/documents/peppardwarddaniel07.pdf)

<br>

**Overview of Benefit Dependency Network**
<br>
---

**Benefit led**
<br>
---
![bdn_explained](https://github.com/user-attachments/assets/fc981acb-1a2b-4e63-9f3c-2084bfc98a1e)

**innovation led**
<br>
---
![image](https://github.com/user-attachments/assets/c582fa36-f2d7-4e9b-a6b8-ab501de42803)


**Worked example from authors**
<br>
---
![Screenshot 2024-09-19 172655](https://github.com/user-attachments/assets/d3ef433c-fece-413f-a2c3-cec95aa37f65)

**Wataru Example as mermaid/html**
<br>
---
[link to Wataru's Draft on github](https://wutansmash.github.io/bdn)




**Some extra diagrams**
```mermaid
flowchart 
    %% Define swimlanes
    subgraph BDNA[statements]
     BDN1[We need a ....]
    

     BDN2[We need to...]
    

     BDN3[So that we can...]
    

     BDN4[In order to...]
     BDN1-->BDN2-->BDN3-->BDN4


    end

    %% Define swimlanes
    subgraph BDNB[Action words]
     BDN1.1[Thing]
    

     BDN2.1[Enabling/Business change]
    

     BDN3.1[Benefit]
    

     BDN4.1[Driver]
    
    BDN1.1-->BDN2.1-->BDN3.1-->BDN4.1
 end

subgraph BDNC[More Statement words]
     BDNa[If we build a...]
    
     BDNb[And carry out...]

     BDNc[We'll be left with...]

     BDNd[And we will be able to...]
    
     BDNe[Because we need to...]
    
    BDNa-->BDNb-->BDNc-->BDNd-->BDNe
 end


 BDNA-->BDNC-->BDNB
```

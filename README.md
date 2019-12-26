# Calculating the Total Cost of Ownership for Software

# Summary
**Problem**: Total Cost of Ownership is rarely calculated for IMS Projects
**Root Cause**: Lack of understanding of the literature on Total Cost of Ownership and why it is critical to the success of IMS projects
**Solution**: Create online calculator to automatically 

## Abstract 
The purpose of this paper is to provide guidance to government departments looking to procure information management systems. It focuses on:

- addressing the difficulty of accurately identifying the true costs associated with the development, ownership and maintainance of information management systems. 
- Proposing an approach to help decision makers build realistic Total Cost of Ownership estimates for proposed projects.

## Understanding IMS Costs
Total Cost of Ownership is the total cost incurred for owning and operating an information management system. It is often ignored or woefully underestimated. The formula’s below provide a way of estimating the total cost of ownership based on the existing literature.

$$MaintenanceCost = \sum(Units * CostPerUnit) * Useful Life$$

$$DevelopmentCost = 0.33 * TotalCostOwnership$$

$$MaintenanceCost = 0.67 * TotalCostOwnership$$

$$TotalCostOwnership = MaintenanceCost + Development Cost$$

*Source: Schach, R. (1999), Software Engineering, Fourth Edition, McGraw-Hill, Boston, MA, pp. 11.*

Below we’ve identified the associated direct and indirect costs and split these into:

- Startup Costs
- Operational costs
- Retirement Costs

# Startup Costs
These are the costs incurred when getting new software into production.

## Software
Off-the-shelf software usually has an up-front software cost plus user licenses. Remember to include any finance charges.

## Hardware
The cost of servers and storage to run the software and other costs like backup and disaster recovery. Does not apply to cloud software.

## Implementation
The cost of setting up, configuring and testing software so it can be used in production. Applies to all software, although with custom software the configuration is usually part of development. Also includes the costs of setting up things like backups, disaster recovery, etc.

## Data Migration
The cost of moving data from the old to the new system, including data format changes. Sometimes not economically viable, so the old system is archived in a read-only mode.

## User Licenses
For off-the-shelf software, these come in two flavors: named users and simultaneous users. For the cloud, licenses are usually named. Does not apply to custom software.

## Training
The cost of training employees to use the software. Applies to all types of software. Note that in addition to end users, helpdesk and system admin employees must also be trained.

## External System Interface Costs
These days no enterprise system operates in isolation, and will require interfaces to other systems in the organization.

## Customization
Some companies customize off-the-shelf software to the way they work, rather than the reverse. Whenever the software is upgraded, there is a risk of the custom code no longer working. Sometimes the customizations can even prevent upgrades. For these reasons, it is usually better to stay with the “plain vanilla” version of the software where possible. Applies to off-the-shelf software.

# Operational Costs
These are the costs incurred while the software is in production.

## Software Maintenance & Support
Usually sold as annual contracts with off-the-shelf software. Ensures you get all patches and upgrades. With custom software, maintenance & support is an ongoing cost and is often much greater than the initial build cost over the lifetime of the product. It is critical to note that maintenance costs make up 67% of the total cost of ownership.

## Patches
The cost of applying security and bug-fix patches. Applies to off-the-shelf software.

## User Licenses
For off-the-shelf software, as the number of users grows in the company, new licenses must be purchased. If the number of users decreases, there are no refunds. For cloud software, licenses are typically priced per month, although they usually require an annual contract. Note that if the number of users increases, this cost increases. If the number of users decreases, this cost may decrease but often only when the contract is renewed.

## Training
New users come from company growth and employee turnover. Also, when cloud vendors push enhancements some training may be required. 

## Enhancements
Applies to custom software where the company must pay developers to provide new functionality as needed, e.g., when the business environment changes or new regulations come into effect. Remember to include documentation and project management costs. Can also apply to customized off-the-shelf software.

## User & Admin Support
This is the cost of helpdesk and system admins and maybe a few analyst/developers who will be supporting the system. Bear in mind that you need to use the fully loaded employee cost, and factor in the costs of managing them.

## Disaster Recovery & High Availability
This ranges from backups through to hot failovers and includes regular testing. Hot failover is very expensive to implement for off-the-shelf or custom software. With cloud products, it is often part of the standard offering, except for smaller vendors. However, there is an additional cost for cloud products, namely being able to recover if the cloud vendor goes out of business.

## Data Center
The costs of running the software in your data center like power, cooling and floor or rack space. Should also include indirect costs like security, data center maintenance, management of the data center and so on. If you are using a hosted data center, it is the monthly cost of running the hardware used by that software. Applies to off-the-shelf and custom software.

## Downtime
The cost to the business when the software is unavailable. Custom software is not tested nearly as well as cloud or off-the-shelf software and is likely to have much higher downtime costs. Off-the-shelf software is more likely to go down than cloud software because cloud vendors invest in things like hot failover.

## Depreciation and Amortisation
Writing off the capital cost of the software and the hardware it runs on. Does not apply to cloud software because it is usually an operational expense.

## Upgrades
Off-the-shelf software usually has upgrades over the life of the software. These projects can be large, expensive, time-consuming and a real risk to the business. Sometimes also applies to custom software, where a new version is created. Does not apply to cloud software because most vendors continually upgrade their software.

## Security
The costs of keeping an application secure, especially if the application is visible outside of the firewall. Does not apply to cloud software because it is paid for by the cloud vendor.

# Retirement Costs
These are the costs incurred when retiring software. Many companies forget that retired systems can still incur considerable costs, e.g. if you had grown out of one cloud product and moved to another. It was not worth the expense of migrating transactional data, but for compliance reasons it had to be available for several years. Another example is migrating from one helpdesk system to another. Is it worth moving things like the knowledgebase? In many of these situations, it is worth keeping the old system in and archived/read only mode for several years, and there are costs associated with that.

## Data Export
You want to be able to export existing data in a suitable format. Some vendors make it easy to get data into their systems, but there is little incentive to make it easy to get that data out again so it can be expensive.

## Archived Systems
You want to keep off-the-shelf or custom software available for reference. You need to keep it running on servers in the data center, with their associated costs. For cloud software, you want the system to be available for reference, preferably in a read-only mode. You want to pay a minimal amount for use of the system, but unless this was part of the original agreement, you could be forced to pay a lot more.

## Inactive Licenses
You may need to keep all user licenses on the system to preserve audit trails, but you certainly don’t want to pay full user costs for an archived system.

# Conclusion
Use the costs above to help estimate a realistic TCO over the lifetime of the software. While this article lists the more common costs, be alert for others specific to your situation.
Typically the TCO and ROI are estimated at the start of a software selection project. When selecting one of several software alternatives on the shortlist, update the TCO of each product for more accurate ROI estimates. You may find much larger differences in ROI than expected, especially when comparing cloud, custom, and off-the-shelf software.

# References 

https://books.google.com.au/books?id=CjkS_KjbvgsC&pg=SL603-PA184&lpg=SL603-PA184&dq=67%25+software+cost&source=bl&ots=jFQlJGgfM1&sig=ACfU3U2A5O9s0rrS0hiroob3R7a2d_-iwg&hl=en&sa=X&ved=2ahUKEwjDk9fs0LPmAhWqwTgGHWkeDWMQ6AEwCXoECAgQAQ#v=onepage&q=67%25%20software%20cost&f=false

https://pdfs.semanticscholar.org/2147/c6218db2e35d40f4a7bdb87ed47e3814ef4b.pdf

https://books.google.co.nz/books?id=5xkeDQAAQBAJ&pg=PA14&lpg=PA14&dq=software+maintenance+67%25&source=bl&ots=AJMDT11wA7&sig=ACfU3U3bCZyZxT3b-RRUX4ND_stP3sR_aw&hl=en&sa=X&ved=2ahUKEwjkmP7o6bXmAhWUheYKHX7aC2YQ6AEwAHoECAIQAQ#v=onepage&q=software%20maintenance%2067%25&f=false

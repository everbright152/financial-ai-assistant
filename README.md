# 💰 Financial Planner - Your AI-Powered Personal Finance Assistant 🤖

Welcome to the Financial Planner, a key component of the [Free Life Planner (FLP)] system. This intelligent AI-based tool is designed to help you take control of your personal finances, plan for the future, and achieve your financial goals.

## 🌟 Features

The Financial Planner offers a wide range of features to assist you in managing your money:

- 🧠 **Intelligent Financial Planning and Reasoning**: Leveraging advanced AI techniques, the planner integrates action costs and earning information to generate comprehensive temporal plans for financial prediction and reasoning.
  - ✅ Quickly forecast finances almost indefinitely into the future
  - ✅ Specify recurring transactions
  - ✅ Automatically detect recurring transactions from OFX exports and plan for them (e.g., `promiseToPayForSpec('ELEC',andrewDougherty,'',dollars(93.00),[can([1]),not(onTime([3]))])`)
  - ✅ Express expected date ranges of transactions using `can`, `neg(onTime)`, `months`, date ranges, etc.
  - ✅ Financial reasoning integrated with general planning, adding financial reasoning to life-planning problems

- 🖥️ **Interactive Plan Execution**: The intuitive GUI guides you through the execution of your financial plan, checking preconditions, propagating effects, and helping you stay on track.
  - ✅ [IEM2](https://frdcsa.org/~andrewdo/iem2-3.mp4) for walking user through plans
  - ✅ Update world state with all effects
  - ✅ Extraction of world state deltas
  - 🚧 \[50%\] Verify preconditions
  - 🚧 \[25%\] WebUI for IEM2 (using Mock Perl/Tk objects)
  - 🚧 \[75%\] SPSE2->PSEx3 export (Planning, Scheduling and Execution System (Extended), version 3)
  - 🚧 \[75%\] Integrating financial reasoning and other domains, with SPSE's to-do dependency graph

- 📅 **Calendaring and Recurrences**: View your predicted transactions, running balances, and upcoming financial events in a clear calendar format. The system also supports programmable recurrences and can detect patterns from your transaction logs.
  - ✅ View expected financial transactions along with primary agenda on a calendar
  - ✅ Calenderical recurrences using CLP (Constraint Logic Programming)
  - ✅ Predicted transactions' date, description, debit or credit and running balance (as a list and chart)
  - ✅ Tell us when we're going to run out of money and how much we need to raise by when
  - ✅ Abduction of recurrences and predicted events from bank statements in OFX or CSV (Open Financial Exchange, Comma-Separated Values)
  - ✅ Text-to-speech alerts for recurrent transactions
  - 🚧 \[25%\] WebUI for editing financial recurrences

- 📊 **Financial Records and Order Tracking**: Automatically extrapolate auto-debits from bank exports, reconcile records with reported purchases, and track the state of your deliveries.
  - ✅ Matching bank records to receipts
  - ✅ Tracking purchases and deliveries
  - 🚧 \[50%\] Online receipt tracker
  - 🚧 \[50%\] Brick and mortar receipt tracker
  - 🚧 \[10%\] Displaying live/real-time bank information
  - 🚧 \[20%\] Check current account balance automatically

## 🔮 Planned Features

We're constantly working to improve the Financial Planner. Here are some exciting features in the pipeline:

- 💸 **Cash Flow Analysis and Budgeting**: The planner will help you compute a monthly budget and set goals to build up your financial safety buffer.
  - ✅ Help manage cash flow in tight situations
  - 🚧 Budgeting (monthly)
  - 🚧 Automatic creation of fundraising alerts and deadlines to maintain positive balance
  - 🚧 Classifying (OFX) transactions
  - 🚧 Financial reporting
  - 🚧 Regulatory compliance (say, to Social Security rules)
  - 🚧 (Personal) Accounting with XBRL bookkeeping
  - 🚧 Loan and debt tracking/management
  - 🚧 Bill payment subsystem

- 🧩 **Meta-Planning for Contingencies**: Advanced planning capabilities will allow the system to develop contingent plans, helping you prepare for various financial scenarios.
  - ✅ Temporal metric planning for finances
  - ✅ Unexpected delays
  - 🚧 Metaplanners help develop contingency plans for different financial problems
  - 🚧 TraCE temporally-contingent (metric) planner integration
  - 🚧 Overcharges and unapproved charges
  - 🚧 Cash flow problems and hardships
  - 🚧 Retrospectively analyze prior predictions to update or correct financial recurrences

- 🤝 **Argumentation-Based Purchase Decisions**: The planner will reason about your needs and help you make informed, ethical purchasing decisions that align with your budget and values.
  - 🚧 Purchase Decision Support System / Broker Buy/Sell System
  - 🚧 Oversubscription planning for maximizing utility given a cost bound, when can't accomplish all goals
  - 🚧 \[05%\] Oversubscription Planning using Sym-Osp
  - 🚧 Argumentation-based PDSS (Purchase Decision Support System)
    - 🚧 Reasoning over user needs
    - 🚧 Critical questions: Is this purchase ethical/necessary/within-budget? The assumption is "do not purchase," which must be soundly defeated to gain permission
    - 🚧 Product and seller comparison
    - 🚧 Payment plan management
  - 🚧 Inventory/pantry Inventory Management integration
  - 🚧 Resource manager (automatic reordering and stock management)

## 🚀 Getting Started

For more information, please see the Financial Planner section of the FLP Reference Manual: [FLP documentation], and/or the academic paper which introduces Financial Planner: [FLP paper](https://www.academia.edu/116194435/The_Free_Life_Planner).

The financial planner is still being developed, but to start using a very minimal alpha version of the FLP system, follow the instructions present in the [Panoply repository].

## 👥 Contributing

We welcome contributions from the community to help make the Financial Planner even better. If you'd like to contribute, please drop us a message at adougher9@yahoo.com for more information on how to get started.

## 📜 License

The Financial Planner is part of the Free Life Planner system and is released under the GNU General Public License (GPL). See the [LICENSE](LICENSE) file for more details.

## 🆘 Support

If you encounter any issues or have questions about the Financial Planner, please [open an issue]. on our GitHub repository.

Get ready to take control of your financial future soon with FLP's Financial Planner! 🎉

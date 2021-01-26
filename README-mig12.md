1. execute sql from here
2. execute sql from l10n-ec/migration
3. install openupgradelib
4. uninstall modules = env["ir.module.module"].search([('name','in', ['stock_picking_internal','account_financial_report_qweb', 'event_management', 'account_financial_report_date_range','account_group', 'contract_sale_ext']),('state','in',['installed','to upgrade', ])])

migrar foreign_trade, landed_costs_ext


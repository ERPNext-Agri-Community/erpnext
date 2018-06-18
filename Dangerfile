commit_lint.check warn: :all
prose.lint_files
prose.check_spelling

unless github.pr_body.include? "https://github.com/frappe/erpnext/pull/"
  fail "Please include the link to the PR to Frappe in the PR Body"
end
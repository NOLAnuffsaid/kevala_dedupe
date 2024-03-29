# KevalaDedup

  The Kevala platform includes some basic employee management
  functionality. When we onboard a new company we bulk upload
  their existing employees into our system using a simple CSV
  import process. Unfortunately the data we get from
  customers is not always perfect, one of the issues we run
  into is duplicate rows representing the same employee. We
  would like you to write a program that can take a CSV input
  file, identify and remove duplicate rows.

  We identify duplicates as rows that either...

    1. … have the same email address or
    2. … have the same phone number

  ... however we're not yet convinced about the 2nd rule -

  it's possible 2 distinct employees might share the same
  phone number. So we would like to be able to run this
  program with various different strategies, e.g

  ● email - identify duplicates based on matching email only
  ● phone - identify duplicates based on matching phone only
  ● email_or_phone - identify duplicates based on matching
    either email or phone

  INPUT: There should be 2 inputs to the program, (a) the
  csv file and (b) which duplicate detection strategy is to
  be used. The CSV file can be assumed to contain a header
  row with the following columns [ FirstName, LastName,
  Email, Phone ]. The values for some columns may be missing.

  OUTPUT: The output should be a new CSV where duplicate rows
  have been removed based on the specified detection strategy

####  Guidelines
    ● The exercise should only take a few hours to complete.
    ● Please use your preferred programming language,
      anything that can be compiled and tested on OSX or
      Linux will be fine - but include install instructions
      if necessary.
    ● We are looking for the ability to solve the problem
      thoughtfully, code readability, test coverage, and
      clear communication. Please ensure the program is well
      tested, automated testing is very important to us.
    ● We use Elixir, Ruby, or Javascript, but we also believe
      that programming languages can be learned so feel free
      to use your preferred language of choice.
    ● Try to handle unexpected CSV inputs as gracefully as
      possible.
    ● Send your solution (link to a public Github repo, or a
      zip archive) to j******@****re

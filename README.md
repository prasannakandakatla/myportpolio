# myportpolio
export default function Portfolio() {
  return (
    <div className="min-h-screen bg-gray-100 text-gray-800 font-sans">
      {/* Header */}
      <header className="bg-blue-600 text-white py-10 text-center shadow-lg">
        <h1 className="text-4xl font-bold">Laxmi Prasanna Kandakatla</h1>
        <p className="text-lg mt-2">ETL Tester | SQL Developer | QA Enthusiast</p>
      </header>

      {/* About Section */}
      <section className="max-w-5xl mx-auto px-6 py-10">
        <div className="bg-white rounded-2xl shadow-md p-6">
          <h2 className="text-2xl font-semibold mb-4">About Me</h2>
          <p className="leading-7 text-gray-700">
            Motivated and detail-oriented professional transitioning into IT with knowledge in
            ETL Testing, SQL, Data Validation, and Software Testing concepts. Passionate about
            ensuring data quality and building efficient testing solutions.
          </p>
        </div>
      </section>

      {/* Skills */}
      <section className="max-w-5xl mx-auto px-6 py-4">
        <div className="bg-white rounded-2xl shadow-md p-6">
          <h2 className="text-2xl font-semibold mb-4">Technical Skills</h2>
          <div className="grid grid-cols-2 md:grid-cols-3 gap-4">
            {[
              "SQL",
              "ETL Testing",
              "Data Warehousing",
              "MySQL",
              "Oracle",
              "Manual Testing",
              "SDLC & STLC",
              "Data Validation",
              "Defect Tracking",
            ].map((skill) => (
              <div
                key={skill}
                className="bg-blue-100 text-blue-700 px-4 py-2 rounded-xl text-center font-medium"
              >
                {skill}
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Projects */}
      <section className="max-w-5xl mx-auto px-6 py-10">
        <div className="bg-white rounded-2xl shadow-md p-6">
          <h2 className="text-2xl font-semibold mb-4">Projects</h2>

          <div className="border-l-4 border-blue-500 pl-4 mb-6">
            <h3 className="text-xl font-semibold">ETL Data Validation Project</h3>
            <p className="text-gray-700 mt-2">
              Worked on validating source and target data using SQL queries. Performed data
              quality checks, row count validation, and transformation testing.
            </p>
          </div>

          <div className="border-l-4 border-blue-500 pl-4">
            <h3 className="text-xl font-semibold">SQL Reporting System</h3>
            <p className="text-gray-700 mt-2">
              Created SQL queries for reports using joins, subqueries, and aggregate functions
              to validate business data.
            </p>
          </div>
        </div>
      </section>

      {/* Experience */}
      <section className="max-w-5xl mx-auto px-6 py-4">
        <div className="bg-white rounded-2xl shadow-md p-6">
          <h2 className="text-2xl font-semibold mb-4">Experience</h2>
          <div>
            <h3 className="text-xl font-semibold">US IT Recruiter</h3>
            <p className="text-gray-600">2 Years Experience</p>
            <p className="mt-2 text-gray-700 leading-7">
              Experience in sourcing candidates, client communication, handling recruitment
              processes, and working with databases and reporting tools.
            </p>
          </div>
        </div>
      </section>

      {/* Education */}
      <section className="max-w-5xl mx-auto px-6 py-10">
        <div className="bg-white rounded-2xl shadow-md p-6">
          <h2 className="text-2xl font-semibold mb-4">Education</h2>
          <p className="text-gray-700">
            Bachelor's Degree in Computer Science / Related Field
          </p>
        </div>
      </section>

      {/* Contact */}
      <section className="max-w-5xl mx-auto px-6 pb-10">
        <div className="bg-white rounded-2xl shadow-md p-6 text-center">
          <h2 className="text-2xl font-semibold mb-4">Contact</h2>
          <p>Email: prasanna.kandakatla156@gmail.com</p>
          <p>GitHub: github.com/prasannakandakatla</p>
          <p>LinkedIn: linkedin.com/in/laxmi-prasanna-95a5a140a/</p>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-blue-600 text-white text-center py-4 mt-6">
        <p>© 2026 Laxmi Prasanna | Portfolio</p>
      </footer>
    </div>
  );
}

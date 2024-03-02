## How to register a DBContext class in program.cs

builder.Services.AddControllers();<br />
builder.Services.AddDbContext<CustomerDBContext>(option =>option.UseSqlServer(builder.Configuration.GetConnectionString("CustomerDB")));
builder.Services.AddEndpointsApiExplorer();<br />
builder.Services.AddSwaggerGen();<br />
